# Latent Space Upscaling Guide!Currently outdated !!!![Will be updated in a few hours]!!
# **This guide will teach you how to use latent Space upscaling! via Automatic1111**
![Hosioka!GITHUB](https://s1.fileditch.ch/wwuuQMKxwmkZfobXwdA.png)
### **This feature runs by scaling the latent sample of the image, and then running a second pass of img2img which results in insane quality boost!**

## This guide was made for Automatic1111Webui!
## Pros & Cons of Latent space upscaling
 # Pros 
 - A tremendous quality boost               
 
 # Cons
 - Can sometimes make the output image more deformed 
    
 ## This guide was tested using [BakaDiffusion](https://huggingface.co/Hosioka/Baka-Diffusion)
 to exactly replice what i did. use the Fp16 Model from my HuggingFace Repo above!

![Hosioka!GITHUB](https://s1.fileditch.ch/gmcfyZGPMWRErjxoLFg.png)
## We'll call this the **Misato test!**


#### **Step 1**

![HosiokaGit](https://user-images.githubusercontent.com/118495208/208976686-81a8423b-be4e-4190-9b56-17d873a99d9a.png)

#### **Step 2**

Let's say you want to latent space upscale an image of Misato Katsuragi for example.
![HosiokaGit](https://s1.fileditch.ch/fvDcURcDNLYunrgNxmHb.png)
```
masterpiece, best quality, 1girl, eye focus, katsuragi misato, ribbed sweater, purple hair, brown eyes
Negative prompt: lowres, (bad anatomy), text, cropped, worst quality, low quality, jpeg artifacts, signature, watermark, username, artist name, (out of frame), black and white, obese, censored, child, loli, long fingernails
Steps: 30, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1506386276, Size: 512x512, Model hash: 63c46c36, ENSD: 31337
```
#### **Step 3**
![HosiokaGit](https://s1.fileditch.ch/fwTAHwYWMRDBtyHTjad.png)
**The rest of the settings will stay the same, We'll be changing out FirstPass and output resolution, We'll be doubling the original resolution(*512x512*) which will become(*1024x1024*) and we'll be pasting our original resolution(*512x512*) into our first pass! and our output into (*1024x1024*)
if everything's done correct it should look like the image above! ⇈**


## Final comparison!
![HosiokaGit](https://s1.fileditch.ch/IougPrFrGmyEFarLJcwg.png)


# MISC
Sweet spot for denoising setting would be around 0.5 to 0.7 for me, Anything lower than 0.5 may give you blurred image



