# Speech Seperation

A classic problem is the Cocktail Party Problem or the Blind Source Separation.  
Consider yourself at a large party where there are many guests. This is the inspiration for the issue.  
Due to everyone speaking at once, there will be a kind of cacaphony.  
You may now turn off the background noise so you can hear a particular chat.  
Let's codify what we are attempting to do because we also want to do the same.  
Let's assume that there are n microphones that record the signals that are arriving at them and that there are m sources that are producing signals in accordance with some distribution that is independent of one another.  
We make an effort to separate the mixed signals that arrive at the microphones from the underlying source signals.  
To advance, we'll try to tighten the constraints on the issue a bit further.  
The initial presumption is that the source signals are **linearly combined** into the mixed signals.  
The second presumption is that there are the **same number of sources and microphones**.  

## Using ICA to solve the problem for sound signals

To try the code:  
- fork the repository and place the mixed sound signals `sounds/` folder. 
- Run the `preprocess_sound.py` in `sounds/` to get the same sampling rate for each sound signal.(You may have to change the filenames in the code)
- Run `sound_FastICA_FOBI.py`. 
- And that's it you are done! The output will be in the same directory `sounds/` folder.  
- The sounds are labelled so that there is no confusion.
 
### Future Scope
- Take audio visual speech dataset and do the speech seperation.
- To increase acurracy maybe do the lip reading and then identify the speaker.

Enjoy!
