# Credits

This profile and the products behind it build on open-source work. Credit where it is due.

## Wan2GP Finetune

Built on [WanGP](https://github.com/deepbeepmeep/WanGP) by DeepBeepMeep, the open-source generative model suite for running video, image, audio and 3D models on consumer GPUs. The upstream documentation, model support and low-VRAM tooling are his work; this repository is my finetune-oriented build and workflow on top of it.

## Tiny Swords

2D assets from [Tiny Swords by Pixel Frog](https://pixelfrog-assets.itch.io/tiny-swords), used under the asset pack license. Engine: [Godot](https://godotengine.org/).

## 3D Digital Human

Avatar pipeline uses NVIDIA Audio2Face-3D and NVIDIA NIM. Speech generation uses ElevenLabs. The public `audio2face-3d-nim` repository contains the container and FastAPI bridge I built around NVIDIA's service.

## WanStudio / WanVideo

Built on the Wan model family and WanGP. Model weights remain under their original licenses.

## Note on credentials

No API keys, tokens or other credentials are stored in this repository or its history. Secrets stay in environment variables on the deployment host.
