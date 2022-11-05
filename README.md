# Krita-StableDiffusion-WebUI-Colab

**What is it** - this is Colab script for https://github.com/Interpause/auto-sd-krita (currently used https://github.com/danilw/auto-sd-krita )

### Instruction to use - Go to https://colab.research.google.com/ press Upload and Upload this file `Krita-StableDiffusionUI.ipynb`, then open it in Colab and follow instruction there.

**if you need just WebUI** - use Stable Diffusion WebUI Colab. My [WebUI Colab script](https://github.com/danilw/WebUI-Colab-AUTOMATIC1111-stable-diffusion-webui), using AUTOMATIC1111 repo. (this works, and not depends on Krita modification)

___
# Tested today (nov 5) - works.

### Updated - please redownload if script not working for you!
___
### Contact: [**Join discord server**](https://discord.gg/JKyqWgt)

___

### Backend URL in Krita SD Plugin should look like this:

![2](https://user-images.githubusercontent.com/24825887/197233926-f6a269ec-e5ab-4743-ba14-9d020fabb66d.png)

___

# Encryption note:

By default **everything** that goes FROM and TO Krita Plugin is **NOT encrypted**.

### If you need/want Encryption - I made this small change to this plugin version https://github.com/Interpause/auto-sd-krita/issues/32#issuecomment-1301615542 (follow instruction there)

Using this(above) make prompts and images encrypted, on Collab you just need to replace one file and create text file with *your_encryption_key* as text, mentioned in instruction.

___

### Screenshot: 

(on screenshot working img2img on Google Colab, two result images from different prompt, left and right side)

![1](https://user-images.githubusercontent.com/24825887/197250176-63e99121-215e-44e8-9cc1-0017d57f2adb.png)
