# 🌀 ControlNeXt
**ControlNeXt** is our official implementation for controllable generation, supporting both images and videos while incorporating diverse forms of control information. In this project, we propose a new method that reduces trainable parameters by up to 90% compared with ControlNet, achieving faster convergence and outstanding efficiency. This method can be directly combined with other LoRA techniques to alter style and ensure more stable generation. Please refer to the examples for more details.

> 📢 We are initially releasing our code with weights, and further details will be presented in our upcoming paper. Please stay tuned for updates.

> This project is still undergoing iterative development. The code and model may be updated at any time. More information will be provided later.

# Model Zoo

- **ControlNeXt-SVD** [ [Link](ControlNeXt-SVD) ] :  Generate the video controlled by the sequence of human poses. This can be seen as an attempt to replicate the implementation of [AnimateAnyone](https://github.com/HumanAIGC/AnimateAnyone). However, our model is built upon [Stable Video Diffusion](https://stability.ai/stable-video), employing a more concise architecture.

- **ControlNeXt-SD1.5** [ [Link](ControlNeXt-SD1.5) ] : Controllable image generation. Our model is built upon [Stable Diffusion 1.5](https://huggingface.co/runwayml/stable-diffusion-v1-5). Fewer trainable parameters, faster convergence, improved efficiency, and can be integrated with LoRA.

- **ControlNeXt-SDXL** [ [Link](ControlNeXt-SDXL) ] : Controllable image generation. Our model is built upon [Stable Diffusion XL ](stabilityai/stable-diffusion-xl-base-1.0). Fewer trainable parameters, faster convergence, improved efficiency, and can be integrated with LoRA.

- **ControlNeXt-SD3** [ [Link](ControlNeXt-SD3) ] : Stay tuned.

- **ControlNeXt-CN** [ [Link](ControlNeXt-CN) ] : Stay tuned.


# 🎥 Examples


### [ControlNeXt-SVD](ControlNeXt-SVD)
If you can't load the videos, you can also directly download them from [here](ControlNeXt-SVD/outputs).

<video width="80%" height='auto' style="display: block; margin: 20px auto;" controls autoplay loop src="https://github.com/dvlab-research/ControlNeXt/assets/22709028/c0ec7591-2100-42d9-99dd-cc55c5fa006f" muted="false"></video>

<video width="80%" height='auto' style="display: block; margin: 20px auto;" controls autoplay loop src="https://github.com/dvlab-research/ControlNeXt/assets/22709028/5da1ba44-cb92-49c2-95f4-05b8e02ed6eb" muted="false"></video>

<!-- <video width="40%" height='auto' style="display: block; margin: 20px auto;" controls autoplay loop src="https://github.com/dvlab-research/ControlNeXt/assets/22709028/bc819ca7-81f3-4d63-901a-a1a4b4afc395" muted="false"></video>

<video width="40%" height='auto' style="display: block; margin: 20px auto;" controls autoplay loop src="https://github.com/dvlab-research/ControlNeXt/assets/22709028/adc01423-fcec-467e-a7ab-87a6e1ef5f62" muted="false"></video> -->

<table>
<tr>
    <td width=50% style="border: none">
        <video width="80%" height='auto' style="display: block; margin: 0px auto;" controls autoplay loop src="https://github.com/dvlab-research/ControlNeXt/assets/22709028/bc819ca7-81f3-4d63-901a-a1a4b4afc395" muted="false"></video>
    </td>
    <td width=50% style="border: none">
        <video width="80%" height='auto' style="display: block; margin: 0px auto;" controls autoplay loop src="https://github.com/dvlab-research/ControlNeXt/assets/22709028/adc01423-fcec-467e-a7ab-87a6e1ef5f62" muted="false"></video>
    </td>
</tr>
</table>



### [ControlNeXt-SD1.5](ControlNeXt-SD1.5)

<p align="center">
  <img src="ControlNeXt-SD1.5/examples/deepfashion_multiview/eval_img/DreamShaper.jpg" width="70%" alt="DreamShaper">
</p>
<p align="center">
  <img src="ControlNeXt-SD1.5/examples/deepfashion_multiview/eval_img/Anythingv3_fischl.jpg" width="70%" alt="Anythingv3">
</p>
<p align="center">
  <img src="ControlNeXt-SD1.5/examples/deepfashion_caption/eval_img/chinese_style.jpg" width="70%" alt="Anythingv3">
</p>



### [ControlNeXt-SDXL](ControlNeXt-SDXL)

<p align="center">
  <img src="ControlNeXt-SDXL/examples/vidit_depth/eval_img/DreamShaper.jpg" width="70%" alt="DreamShaper">
</p>
<p align="center">
  <img src="ControlNeXt-SDXL/examples/vidit_depth/eval_img/StableDiffusionXL_glass.jpg" width="70%" alt="Lora">
</p>
