# A fork of the Stable Diffusion Cog model that outputs tileable images

This is an implementation of the [Diffusers Stable Diffusion 1.4](https://huggingface.co/CompVis/stable-diffusion-v1-4) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights [with your Hugging Face auth token](https://huggingface.co/settings/tokens):

    cog run script/download-weights <your-hugging-face-auth-token>

Build a Docker image:

    cog build

Run locally in docker container
