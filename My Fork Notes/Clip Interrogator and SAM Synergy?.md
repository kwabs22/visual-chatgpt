# Where do they intersect?

SAM can generate masks for img2img and controlnet use cases

some Info on clip
CLIP Interrogator uses OpenCLIP which supports many different pretrained CLIP models. For the best prompts for Stable Diffusion 1.X use ViT-L-14/openai for clip_model_name. For Stable Diffusion 2.0 use ViT-H-14/laion2b_s32b_b79k

# Therefore the SAM model and the Clip interrogator use the ViT-L and H models but SAM has a custom one

# So if you figure out how CLIP Interrogator uses ViT can it use the SAM version as well?

How do image and text embeddgings mix?

Clip interrogator caption generation
https://github.com/pharmapsychotic/clip-interrogator/blob/f4429b4c9d0044d46d811498e635317d262a2389/clip_interrogator/clip_interrogator.py#L188

Transformers autoproccesor?
https://github.com/pharmapsychotic/clip-interrogator/blob/f4429b4c9d0044d46d811498e635317d262a2389/clip_interrogator/clip_interrogator.py#L85

Caption Models
https://github.com/pharmapsychotic/clip-interrogator/blob/f4429b4c9d0044d46d811498e635317d262a2389/clip_interrogator/clip_interrogator.py#L18
