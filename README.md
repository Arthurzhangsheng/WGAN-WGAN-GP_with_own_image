# WGAN-WGAN-GP_with_own_image
using own image data to train a wgan and wgan-gp

# statement
I clone this repo from other people when I was a newcomer， however I can't find the original source now， so I upload this repo again.  

# usage
 put your image data (*.jpg*)  in `data/yourdatasetname/`  
 and modify the code  
 `flags.DEFINE_string("dataset", "celebA", "The name of dataset [celebA, mnist, lsun]")`   
 into  
 `flags.DEFINE_string("dataset", "yourdatasetname", "The name of dataset [celebA, mnist, lsun]")`  
 then run the `main.py`
