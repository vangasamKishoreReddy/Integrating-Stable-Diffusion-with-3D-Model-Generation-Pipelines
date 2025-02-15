# Integrating-Stable-Diffusion-with-3D-Model-Generation-Pipelines

# model_id = "CompVis/stable-diffusion-v1-4"
# model_id = "stabilityai/stable-diffusion-2-1"

Features

Text-to-Image Conversion using Stable Diffusion
Image-to-3D Model Generation using open-source AI models
Customizable Prompts for high-quality 3D outputs
Supports CUDA & CPU for faster rendering

Recommended Prompts
For better 3D generation, use:
"High-quality 3D model of a fantasy castle"
"3D-rendered futuristic spacecraft, ultra-detailed"
"Voxel-style 3D character, game asset ready"

Troubleshooting

1️ "CUDA out of memory" Error
Try running the model in CPU mode by setting torch_dtype=torch.float32.
2️ Low-Quality 3D Output
Experiment with more detailed prompts.
Use higher guidance scale (8.5 - 12.0).
3️ Model Not Loading
Ensure you have installed Hugging Face transformers and authenticate with a Hugging Face token if required.

Contributing
Feel free to submit pull requests for enhancements! Fork the repo and make a PR with your improvements.

References
https://stability.ai/stable-3d
https://huggingface.co/tencent/Hunyuan3D-2
