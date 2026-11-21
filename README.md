<div align="center">

# Muhammed Rasal

### Full-stack AI product engineer

Building automations, local video generation, games and apps.

I take AI from a model on a GPU to a shippable product: React and Node, job queues, credits, storage, and the GPU workers doing the heavy lifting.

[Portfolio](https://github.com/MhdRasal/portfolio) · [Nikah Invitation — live](https://nikah-invitation-kunjimol.vercel.app) · [Tiny Swords — live](https://tinyswordsweb.vercel.app/) · [Wan2GP Finetune](https://github.com/MhdRasal/Wan2GP-finetune)

![Public repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FMhdRasal&query=%24.public_repos&label=public%20repos&color=2ea44f&style=flat-square)
![Private builds](https://img.shields.io/badge/private%20builds-13-6e40c9?style=flat-square)
![AI products](https://img.shields.io/badge/AI%20products-6-blue?style=flat-square)

</div>

---

## About me

I'm a full-stack AI product engineer. My work sits between product engineering and GPU pipelines: React frontends, Node/Express APIs, MongoDB and Supabase backends, asynchronous job systems, cloud storage, and the models doing the heavy lifting.

I care about the unglamorous parts — queue workers, retries, credits, storage fallbacks, live logs — because that is what makes generative tools feel like real products instead of demos.

- Building **SocialAgent**, an AI content workforce for creators
- Building **WanStudio**, a cloud video generation studio
- Maintaining **Wan2GP Finetune**, my open-weight generative stack for local and cloud GPU
- Exploring real-time **3D digital humans** with NVIDIA Audio2Face-3D
- Shipped my first game, **Tiny Swords: Arena Survivor**, in one week

## Live now

- **Nikah Invitation** — digital invitation with RSVP, admin dashboard and Supabase backend: [nikah-invitation-kunjimol.vercel.app](https://nikah-invitation-kunjimol.vercel.app)
- **Tiny Swords: Arena Survivor** — my first game, Godot 4 web build: [tinyswordsweb.vercel.app](https://tinyswordsweb.vercel.app/)

## AI products

| Product | What it is | Stack | Status |
| --- | --- | --- | --- |
| **SocialAgent** | AI content workforce: agent campaigns, multi-platform publishing, batch and Drive imports, content calendar, live job tracking, encrypted provider keys and API access. | React, Express, MongoDB, OAuth, SSE | AI product · private |
| **WanStudio** | Full-stack video generation studio: model profiles, text/image-to-video, batch jobs, credits and billing, admin dashboard, Kaggle free tier and Modal paid GPU, GCS output. Renamed from WanVideo 2nd stage. | React, TypeScript, Express, MongoDB, Modal, Kaggle | AI product · private |
| **Wan2GP Finetune** | Open-weight video, image, audio and 3D generation for local or cloud GPUs. Built around finetunes, LoRAs and custom checkpoints on low VRAM. | Python, PyTorch, WanGP, Kaggle | Open weights · public |
| **Lightning Control** | Operations console for the generation stack: Kaggle account pools, templates, start/stop jobs and live logs. | React, Express, MongoDB, GCS | AI ops · private |
| **3D Digital Human** | Real-time talking avatar with NVIDIA Audio2Face-3D, ElevenLabs TTS, LLM-driven gestures and 52 ARKit blendshapes. | Three.js, TypeScript, NVIDIA NIM, Modal | AI product · private |
| **WanVideo** | First-stage AI video generator powered by Wan2GP and Kaggle GPU resources — the base layer that grew into WanStudio. | React, Kaggle, Wan2GP | AI product · private |

## UI and full-stack work

| Product | What it is | Stack | Status |
| --- | --- | --- | --- |
| **Nikah Invitation** | Digital wedding invitation with animated invite, countdown, RSVP and decline flows, admin dashboard, Supabase backend and Google Sheets sync. | React, TypeScript, Supabase, Tailwind | Live · [open](https://nikah-invitation-kunjimol.vercel.app) |
| **WanVideo — Vercel first stage** | Vercel build of the first-stage generator UI and free-tier flow. | React, TypeScript, Vercel | Private |
| **Portfolio** | Personal portfolio built from a reference design, with AI product case studies and live links. | React, Vite, Tailwind CSS, Framer Motion | [Public](https://github.com/MhdRasal/portfolio) |
| **Tiny Swords** | My first game: arena survival built with Godot 4 in one week, exported to web and Android with a live leaderboard. | Godot 4, GDScript, Vercel, MongoDB | Live · [play](https://tinyswordsweb.vercel.app/) |

## Deployment notes

SocialAgent and WanStudio are long-running Express/MongoDB services with background workers, scheduled jobs and SSE streams. That architecture belongs on a Node host, not Vercel serverless functions, so the Vercel builds stay frontend-only. Nikah Invitation and Tiny Swords are live on Vercel because their backends are Supabase and serverless functions.

<sub>Several product repositories are private. Happy to walk through the architecture and code on request. See [CREDITS.md](https://github.com/MhdRasal/MhdRasal/blob/main/CREDITS.md) for upstream credits.</sub>

## The journey

1. **Web apps** — React, Node and MongoDB. Learning by shipping small products end to end.
2. **WanVideo** — wired Wan2GP into Kaggle notebooks and built the first AI video generator.
3. **WanStudio** — turned that pipeline into a real studio: cloud GPUs, credits, storage, billing and admin.
4. **SocialAgent + Lightning Control** — added the automation and ops layers that make generation usable every day.
5. **Digital humans and games** — now exploring real-time avatars and taking my first steps into game development.

## Toolbox

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white)

---

<div align="center">

<sub>Always building. Somewhere between a render queue and a UI polish pass.</sub>

</div>
