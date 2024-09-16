# Using LangSAM and Stable Diffusion for Inpainting

This project presents a technique for object detection, segmentation, and inpainting using the LangSAM library alongside the Stable Diffusion model. LangSAM integrates GroundingDino with SAM to achieve precise object segmentation, while the Stable Diffusion InpaintPipeline is employed to inpaint the segmented regions based on user-specified prompts. The process includes setting up dependencies, initializing the models, and executing a comprehensive pipeline that takes an image, performs segmentation, and applies inpainting to transform objects in the image according to user-defined instructions.

# Installation
pip install -r requirements.txt


