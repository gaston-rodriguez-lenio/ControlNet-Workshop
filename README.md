# ControlNet-Workshop

Source: [paper](https://arxiv.org/abs/2302.05543) and [Repository](https://github.com/lllyasviel/ControlNet)


# Installation Guide:

Is posible to use the original version from the repository above but is eassier to use with the Automatic 1111 web app.

1. Install Automatic 1111 and download SD model weights:
You have to install the Automatic 1111 web App and download the desire Stable Diffusion model. Follow the steps on this [tutorial video](https://www.youtube.com/watch?v=sF77S664AHg)
Note: be carefull with the specific version you download or the base version of the finetunned model. Different versions requiers specific controlnet models.

2. Install the extension for Automatic 1111:
Follow the steps on the original repository of Controlnet for Automatic 1111. Link to [installation guide](https://github.com/Mikubill/sd-webui-controlnet#installation)

3. Download ControlNet models:

a. You have to download the Controlnet specific models, for example to use pose estimation download open-pose model.
You need to download model files ending with ".pth"
Here is a link to download sd 1.5 compatibile from [hugghing-face](https://huggingface.co/lllyasviel/ControlNet-v1-1/tree/main). For sd XL check this [link](https://github.com/Mikubill/sd-webui-controlnet/tree/main#download-models-for-sdxl)

b. Put models in your "stable-diffusion-webui\extensions\sd-webui-controlnet\models". You only need to download "pth" files.


4. ENJOY GENERATING IMAGES!

# Usefull links

[QR Monsters](https://huggingface.co/monster-labs/control_v1p_sd15_qrcode_monster)
