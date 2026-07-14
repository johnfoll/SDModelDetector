With the lack of Standards, and the lack of good documentation relating in many Stable Diffusion ComfyUI models, it is very dificcult to know somethimes if the model contains vae or text_encoders for checkpoints. 
If the model is missing something it will not run unless the missing components are added. Just adding a text_encoder or vae to an existing checkpoint may or may not work right if it already contains these things. 
Adding an components to one that is already conceivably bloats the memory requirements to run the model. So it is important to be dead certain what it contains or not.

It is hoped that this SDModelDetector.py can be dead accurate in reporting the contents of and Stable Diffusion model.
