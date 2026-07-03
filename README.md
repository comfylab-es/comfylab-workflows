# ComfyUI Workflows — comfylab.es / comfylab.dev

Colección de workflows de ComfyUI para generación de imágenes y vídeos con IA, optimizados para GPUs modestas (4-8GB VRAM) y probados en RTX 3090 (24GB).

Todos los workflows están documentados en **[comfylab.es](https://comfylab.es)** (español) y **[comfylab.dev](https://comfylab.dev)** (inglés) con guías paso a paso.

---

## Workflows disponibles

| Archivo | Descripción | Guía |
|---|---|---|
| `controlnet-union-workflow.json` | Control de poses y composición con ControlNet Union Pro | [Ver guía](https://comfylab.es/blog/workflows/guia-controlnet-union-pro/) |
| `flux-kontext-character-edit-comfylab.json` | Edición de personajes con Flux Kontext | [Ver guía](https://comfylab.es/blog/workflows/flux-kontext-comfyui/) |
| `flux-sdxl-universal-uncensored.json` | Generación de imágenes con Flux / SDXL sin censura | [Ver guía](https://comfylab.es/blog/workflows/generar-imagenes-comfyui/) |
| `hunyuanvideo-t2v-cinematic-comfylab.json` | Generación de vídeo cinemático con HunyuanVideo | [Ver guía](https://comfylab.es/blog/workflows/generar-videos-comfyui/) |
| `img2img-lora-workflow.json` | Img2img con LoRA para transformar imágenes | [Ver guía](https://comfylab.es/blog/workflows/img2img-comfyui/) |
| `ltx-2-3-uncensored-workflow.json` | Generación de vídeo con LTX 2.3 sin censura | [Ver guía](https://comfylab.es/blog/workflows/ltx-2-3-sin-censura-comfyui/) |
| `qwen-image-poster-texto-espanol-comfylab.json` | Pósters con texto en español usando Qwen | [Ver guía](https://comfylab.es/blog/nodos/nodos-esenciales-comfyui/) |
| `shareable-workflow-validation-template-comfylab.json` | Plantilla para validar y compartir workflows | [Ver guía](https://comfylab.es/blog/guias-pro/validar-workflow-comfyui/) |
| `stable-audio-open-v1.json` | Generación de audio con Stable Audio Open | [Ver guía](https://comfylab.es/blog/workflows/generar-audio-comfyui/) |
| `upscaling-4k-workflow.json` | Upscaling a 4K con nitidez profesional | [Ver guía](https://comfylab.es/blog/workflows/guia-upscaling-4k-comfyui/) |
| `wan-21-i2v-cinematic-comfylab.json` | Animación imagen a vídeo con Wan 2.1 | [Ver guía](https://comfylab.es/blog/workflows/wan-21-i2v-comfyui/) |
| `wan-video-2-1-pro.json` | Generación de vídeo con Wan 2.1 Pro | [Ver guía](https://comfylab.es/blog/workflows/generar-videos-comfyui/) |
| `krea2-turbo-flat-comfylab.json` | Krea 2 Turbo, grafo plano (sin bug de subgrafo) | [ES](https://comfylab.es/blog/guias-pro/krea-2-comfyui-guia-modelo-turbo/) · [EN](https://comfylab.dev/blog/guides-pro/krea-2-comfyui-guide-turbo-model/) |
| `ltxv-2.3-t2v-comfylab.json` | Texto a vídeo + audio con LTXV-2.3 distilled | [ES](https://comfylab.es/blog/workflows/ltxv-2-3-rtx-super-resolution-comfyui-workflow-real/) · [EN](https://comfylab.dev/blog/workflows/ltxv-2-3-rtx-video-super-resolution-comfyui-workflow/) |
| `rtx-super-resolution-upscaler-comfylab.json` | Upscaling 4K del vídeo de LTXV-2.3 con RTX Super Resolution | [ES](https://comfylab.es/blog/workflows/ltxv-2-3-rtx-super-resolution-comfyui-workflow-real/) · [EN](https://comfylab.dev/blog/workflows/ltxv-2-3-rtx-video-super-resolution-comfyui-workflow/) |
| `scail2-character-replacement-comfylab.json` | Reemplazo de personaje en vídeo con SCAIL-2 | [ES](https://comfylab.es/blog/workflows/scail-2-character-replacement-comfyui-workflow/) · [EN](https://comfylab.dev/blog/workflows/scail-2-character-replacement-comfyui-workflow/) |
| `wan21-i2v-boxer-replication-comfylab.json` | Imagen a vídeo con Wan 2.1, réplica de escena de boxeo | [ES](https://comfylab.es/blog/workflows/wan-2-1-i2v-vs-ltxv-2-3-comfyui-misma-escena/) · [EN](https://comfylab.dev/blog/workflows/wan-2-1-i2v-vs-ltxv-2-3-comfyui-same-scene-test/) |
| `wan22-i2v-boxer-replication-comfylab.json` | Imagen a vídeo con Wan 2.2 MoE (HighNoise+LowNoise), misma escena | [ES](https://comfylab.es/blog/workflows/wan-2-2-i2v-vs-ltxv-2-3-comfyui-misma-escena/) · [EN](https://comfylab.dev/blog/workflows/wan-2-2-i2v-vs-ltxv-2-3-comfyui-same-scene-test/) |
| `ltx-director-mars-astronaut-comfylab.json` | Texto a vídeo con audio, nodo comunitario LTX Director (WhatDreamsCost) | [ES](https://comfylab.es/blog/workflows/ltx-director-comfyui-astronauta-marte/) · [EN](https://comfylab.dev/blog/workflows/ltx-director-comfyui-mars-astronaut/) |

---

## Cómo usar estos workflows

1. Descarga el archivo `.json` del workflow que necesites
2. Abre ComfyUI en tu navegador (`http://localhost:8188`)
3. Arrastra el archivo JSON a la interfaz de ComfyUI
4. Consulta la guía correspondiente en [comfylab.es](https://comfylab.es) para instrucciones detalladas

## Requisitos

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) instalado
- GPU con mínimo 4GB VRAM (algunos workflows requieren 8GB+)
- Los modelos necesarios se indican en cada guía

---

Hecho con ❤️ en [comfylab.es](https://comfylab.es) — tutoriales de ComfyUI en español
