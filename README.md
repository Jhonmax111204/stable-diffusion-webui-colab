## 🦒 Training Colab GPU

| Colab Page | Function
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/stable-diffusion-webui-colab/blob/training/train_dreambooth_standalone.ipynb) | Train DreamBooth Standalone (Recommended)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/stable-diffusion-webui-colab/blob/training/train.ipynb) | Train DreamBooth & (LoRA 🚦WIP🚦)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/stable-diffusion-webui-colab/blob/training/a_certainty_webui_colab.ipynb) | Train with ACertainty https://huggingface.co/JosephusCheung/ACertainty

## Installed Extensions
[https://github.com/ddPn08/kohya-sd-scripts-webui](https://github.com/ddPn08/kohya-sd-scripts-webui) (Thanks to @ddPn08 ❤ and @thx-pw ❤) <br />
[https://github.com/d8ahazard/sd_dreambooth_extension](https://github.com/d8ahazard/sd_dreambooth_extension) (Thanks to @d8ahazard ❤) <br />
[https://github.com/camenduru/stable-diffusion-webui-diffusers](https://github.com/camenduru/stable-diffusion-webui-diffusers) (Thanks to @diffuserslib ❤) <br />

### How To Use Train DreamBooth Standalone (Recommended)
https://www.youtube.com/watch?v=5dK1altO4Qw

### How To Use Train DreamBooth & (LoRA 🚦WIP🚦)
https://www.youtube.com/watch?v=qAPWnZK4ew8 <br />

- Find someone famous looks like you in the stable diffusion universe (find with: https://starbyface.com) (search with: https://rom1504.github.io/clip-retrieval)
- Example I will try train streamer jinnytty
- I will use Park Min-young but the prompt keyword will be `parkminyoung`
- Create a new drive folder `MyDrive/AI/training/parkminyoung` crop photos (512x512) with https://www.birme.net then add photos
- Go to the Diffusers tab and click on `Train DreamBooth`
- Go to the Diffusers Test tab and test your model using the `parkminyoung person drawing` template `instance_prompt class_prompt your_prompt`
- Go to the Convert DreamBooth tab and click on `Convert Diffusers to Original Stable Diffusion`
- If you want to send it to HuggingFace, use the HuggingFace tab `Push File to 🤗 Hugging Face`

### Licenses
https://github.com/huggingface/diffusers/blob/main/LICENSE
