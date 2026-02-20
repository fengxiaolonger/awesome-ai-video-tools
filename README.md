<div align="center">

# 🎬 Awesome AI Video Tools

**The most comprehensive collection of AI video generation tools, organized by what you actually need to do.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Tools](https://img.shields.io/badge/tools-150+-blue?style=flat-square)
![Last Update](https://img.shields.io/badge/updated-February%202026-brightgreen?style=flat-square)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

<br/>

AI video tools are everywhere, but finding the right one is painful. This list is organized by **use case** — what you're trying to do — not by hype cycle. Every entry is verified by people who actually use these tools.

<br/>

[Submit a Tool](https://github.com/fengxiaolonger/awesome-ai-video-tools/issues/new) · [Report Issue](https://github.com/fengxiaolonger/awesome-ai-video-tools/issues) · [Contribute](#contributing)

</div>

---

## Table of Contents

| | | |
|---|---|---|
| [All-in-One Platforms](#all-in-one-platforms) (8) | [Text-to-Video](#text-to-video) (18) | [Image-to-Video](#image-to-video) (14) |
| [Video-to-Video](#video-to-video) (10) | [AI Avatars & Talking Heads](#ai-avatars--talking-heads) (14) | [AI Video Editing](#ai-video-editing) (16) |
| [Short-Form & Social](#short-form--social) (10) | [Music Video & Audio-Reactive](#music-video--audio-reactive) (8) | [3D & VFX](#3d--vfx) (8) |
| [Upscaling & Enhancement](#upscaling--enhancement) (8) | [Subtitles & Captions](#subtitles--captions) (10) | [Face Swap & Deepfake](#face-swap--deepfake) (6) |
| [Screen Recording & Tutorials](#screen-recording--tutorials) (6) | [Open Source Models](#open-source-models) (16) | [ComfyUI Ecosystem](#comfyui-ecosystem) (12) |
| [APIs & Developer Tools](#apis--developer-tools) (12) | [Prompt Templates](#prompt-templates) | [Learning Resources](#learning-resources) (20) |

---

## All-in-One Platforms

Why juggle 10 different tools when one platform aggregates them all? These give you access to multiple AI models through a single interface.

- [**HeyVid AI**](https://heyvid.ai) ⭐ — The Swiss Army knife. 20+ models in one place: Kling, Veo 3, Sora 2, Runway, Seedance, Hailuo, Pika, PixVerse, Vidu, Luma, Wan, Hunyuan, Midjourney, Flux, GPT-4o, DALL-E, Recraft, Ideogram, SD, Qwen. Text-to-video, image-to-video, video-to-video, text-to-image, TTS, AI music. Free tier. Available in [18 languages](https://heyvid.ai). `Free + Credits`
- [Replicate](https://replicate.com) — Run any open-source model via API. 100+ video models. Pay-per-second. Developer-friendly. `Pay-per-use`
- [fal.ai](https://fal.ai) — Fast GPU inference. Kling, Minimax, Wan, LTX-Video, Hunyuan. Optimized routing for lowest latency. `Pay-per-use`
- [Together AI](https://www.together.ai) — Serverless and dedicated endpoints. Good for batch jobs and fine-tuning. `Pay-per-use`
- [Novita AI](https://novita.ai) — Multi-model API. Video + image + LLM in one platform. Wan 2.1, HunyuanVideo, AnimateDiff. `Credits`
- [Segmind](https://www.segmind.com) — Serverless generative AI APIs. Workflow chaining. Competitive pricing. `Pay-per-use`
- [Modelslab](https://modelslab.com) — API access to SVD, AnimateDiff, and custom fine-tuned video models. `Pay-per-use`
- [ComfyDeploy](https://www.comfydeploy.com) — Turn any ComfyUI workflow into a production API endpoint. `Pay-per-use`

## Text-to-Video

Type a prompt, get a video. The core use case that started it all.

### Frontier Models (Best Quality, 2025-2026)

- [**HeyVid AI**](https://heyvid.ai) ⭐ — Compare outputs from Kling, Veo 3, Sora 2, Runway, Hailuo, Pika side-by-side. Pick the best. No model lock-in. `Free + Credits`
- [Google Veo 2](https://deepmind.google/technologies/veo/) — 4K, 8s. Best camera movements and physical understanding. Via Google AI Studio. `Credits`
- [OpenAI Sora 2](https://openai.com/sora) — 1080p, 20s. Strong narrative coherence. Storyboard mode. ChatGPT Plus/Pro required. `$20-200/mo`
- [Kling 2.0](https://klingai.com) — 1080p, 10s. Best human motion and expressions. By Kuaishou. `Free + Credits`
- [Runway Gen-3 Alpha](https://runwayml.com) — 1080p, 10s. Motion Brush for control. Strong creative community. `$12/mo`
- [Minimax / Hailuo](https://hailuoai.video) — 1080p, 6s. Cinematic quality. Good text rendering in video. `Free + Credits`
- [Luma Dream Machine 2.0](https://lumalabs.ai/dream-machine) — 1080p, 5s. Understands 3D and physics. Fast (~30s per clip). `Free + Credits`
- [Pika 2.0](https://pika.art) — Scene ingredients for control. Lip sync. Sound effects generation. `Free + $8/mo`

### Mid-Range (Good Quality, Lower Cost)

- [PixVerse V3.5](https://pixverse.ai) — 1080p, 8s. Great for anime/stylized. Free daily credits. `Free + Credits`
- [Vidu 2.0](https://www.vidu.com) — 1080p, 8s. Multi-subject reference. By Shengshu Technology. `Free + Credits`
- [Seedance](https://seedance.ai) — Character-consistent generation. Dance/motion specialization. By ByteDance. `Credits`
- [Wan 2.1](https://wan.video) — 720p, 5s. Alibaba. Also open-source (self-hostable). `Free + Credits`
- [Genmo Mochi](https://www.genmo.ai) — 720p, 5s. Open-source backbone. Good for experimentation. `Free`
- [Haiper 2.0](https://haiper.ai) — 1080p, 6s. By ex-Google DeepMind researchers. `Free + Credits`
- [Hunyuan Video](https://video.hunyuan.tencent.com) — 720p, 5s. Tencent. Open weights available. `Free`

### Content Marketing Focused

- [Fliki](https://fliki.ai) — Blog → video, script → video. 2000+ AI voices. Best for repurposing content. `$28/mo`
- [Pictory](https://pictory.ai) — Long articles → video highlights. Auto-summarization. Best for blog-to-video. `$19/mo`
- [InVideo](https://invideo.io) — 5000+ templates. AI script writing. Good for marketing teams. `$15/mo`

## Image-to-Video

Bring static images to life. Quality depends on source image and model's motion understanding.

- [**HeyVid AI**](https://heyvid.ai) ⭐ — Multi-model I2V: run the same image through Kling, Runway, Hailuo, Pika, Luma and compare. `Free + Credits`
- [Runway Gen-3 Alpha](https://runwayml.com) — Motion Brush: paint exactly where you want motion. Most precise control. `$12/mo`
- [Kling 2.0](https://klingai.com) — Best at human portraits. Natural cloth physics and hair. `Free + Credits`
- [Luma Dream Machine](https://lumalabs.ai) — Physics-aware. Great for product shots and 3D objects. `Free + Credits`
- [Pika](https://pika.art) — Modify + Animate: edit the image first, then animate. `Free + $8/mo`
- [PixVerse](https://pixverse.ai) — Best anime-style animation. Character reference for style consistency. `Free + Credits`
- [Stable Video Diffusion](https://stability.ai) — Open-source. 4s at 576×1024. Self-hostable. The baseline for custom pipelines. `Free (self-host)`
- [LivePortrait](https://github.com/KwaiVGI/LivePortrait) — Open-source portrait animation by Kuaishou. Stitching + retargeting. `Free`
- [Viggle](https://viggle.ai) — Mix character images with motion. Controllable character animation. `Free + Credits`
- [DomoAI](https://www.domoai.app) — Style transfer animation (cartoon, anime, 3D, pixel art). Via Discord. `$9.99/mo`
- [Kaiber](https://kaiber.ai) — Artistic transformations. Popular for music videos. `$5/mo`
- [Kling Motion Brush](https://klingai.com) — Brush areas to animate, everything else stays still. `Free + Credits`
- [ToonCrafter](https://github.com/ToonCrafter/ToonCrafter) — Open-source. Generate in-between frames for hand-drawn animation. `Free`
- [DragAnything](https://github.com/showlab/DragAnything) — Drag-based motion control for any entity in the image. `Free`

## Video-to-Video

Transform existing footage with AI: change style, swap elements, enhance, or reimagine entirely.

- [**HeyVid AI**](https://heyvid.ai) — Video style transfer and video transitions. Multi-model pipeline. `Free + Credits`
- [Runway Gen-3 Alpha](https://runwayml.com) — Inpainting: remove/replace objects. Expand canvas. Frame-by-frame consistency. `$12/mo`
- [Pika](https://pika.art) — Modify mode: change specific elements in existing video (clothing, background, objects). `Free + $8/mo`
- [Domo AI](https://www.domoai.app) — Video to anime/cartoon/3D/pixel art. Upload video, choose style. `$9.99/mo`
- [Kaiber](https://kaiber.ai) — Transform footage into animated art. Great for music videos. `$5/mo`
- [Topaz Video AI](https://www.topazlabs.com/topaz-video-ai) — Upscale, denoise, deinterlace, stabilize, interpolate. Industry standard. `$199 one-time`
- [ProPainter](https://github.com/sczhou/ProPainter) — Open-source video inpainting. Object removal with temporal consistency. `Free`
- [TokenFlow](https://github.com/omerbt/TokenFlow) — Open-source text-guided video editing. Consistent style transfer. `Free`
- [Rerender A Video](https://github.com/williamyang1991/Rerender_A_Video) — Zero-shot video style transfer. Temporal consistency via cross-frame attention. `Free`
- [FILM](https://github.com/google-research/frame-interpolation) — Google's frame interpolation. Smooth slow-motion from any footage. `Free`

## AI Avatars & Talking Heads

Generate presenter-style videos with AI-generated or cloned humans. Best for training, marketing, and corporate communications.

- [Synthesia](https://www.synthesia.io) — Market leader. 230+ avatars, 140+ languages. Custom avatar from webcam footage. SOC 2 compliant. `$22/mo`
- [HeyGen](https://www.heygen.com) — Instant avatar from 2min video. Real-time streaming. Multi-scene storyboard. `$24/mo`
- [D-ID](https://www.d-id.com) — Creative Reality Studio. Real-time conversational avatars. Enterprise API. `$5.90/mo`
- [Colossyan](https://www.colossyan.com) — Learning & development focused. Auto-translate with lip sync in 70+ languages. `$21/mo`
- [Elai.io](https://elai.io) — 80+ avatars. PowerPoint → video conversion. Team collaboration. `$23/mo`
- [DeepBrain AI](https://www.deepbrain.io) — AI Studios. Real-time conversation. Kiosk deployment for retail/service. `Custom pricing`
- [Hour One](https://hourone.ai) — Enterprise comms. Virtual human presenters. L&D and internal comms focus. `Custom pricing`
- [Vidnoz](https://www.vidnoz.com) — 1000+ avatars, 140+ languages. Generous free tier with daily credits. Template library. `Free + $22/mo`
- [Renderforest](https://www.renderforest.com) — All-in-one creative suite: avatars, templates, branding, video editing. `$9.99/mo`
- [VEED AI Avatars](https://www.veed.io) — Browser-based. Integrates with VEED's editing suite. `$12/mo`
- [Tavus](https://www.tavus.io) — Personalized video at scale. Variable insertion for 1:1 outreach. `Custom pricing`
- [Rephrase.ai](https://www.rephrase.ai) — Text-to-video API for personalized marketing. Dynamic generation per recipient. `Custom pricing`
- [Hedra](https://www.hedra.com) — Character-1 model. Expressive talking heads with good lip sync from audio. `Free + Credits`
- [Captions AI](https://www.captions.ai) — AI twin creation. Clone yourself for content at scale. `$9.99/mo`

## AI Video Editing

AI-powered tools that make video editing faster, smarter, or entirely automated.

### Full Editors

- [Runway](https://runwayml.com) — Generation + editing in one. Inpainting, color grade, green screen, motion tracking. `$12/mo`
- [Descript](https://www.descript.com) — Edit video by editing text. AI filler word removal. Automatic eye contact correction. `Free + $24/mo`
- [CapCut](https://www.capcut.com) — ByteDance's editor. Auto-captions, background removal, effects. Best free editor for short-form. `Free + Pro`
- [Veed.io](https://www.veed.io) — Browser-based. Auto-subtitles (100+ languages). Real-time collaboration for teams. `Free + $12/mo`
- [FlexClip](https://www.flexclip.com) — Template-driven. AI text-to-video, screen recorder, stock library. `Free + $9.99/mo`
- [Filmora](https://filmora.wondershare.com) — Desktop editor with AI tools: auto-reframe, motion tracking, smart cutout. `$49.99/yr`
- [Adobe Premiere Pro](https://www.adobe.com/products/premiere.html) — Industry standard + Firefly AI integration: auto-transcription, scene detection, generative extend. `$22.99/mo`

### Specialized

- [Opus Clip](https://www.opus.pro) — Long → short: AI finds the best moments, adds captions, formats for social. `Free + $15/mo`
- [Kapwing](https://www.kapwing.com) — Browser-based for teams. Auto-subtitles, resize, remove background. `Free + $16/mo`
- [Canva Video](https://www.canva.com/video-editor/) — Design-first video editor. Templates, brand kits, stock footage. `Free + $12.99/mo`
- [Clipchamp](https://clipchamp.com) — Microsoft's free editor. Built into Windows 11. AI voiceover, auto-captions. `Free + $11.99/mo`
- [Invideo AI](https://invideo.io) — Describe what you want in text, get a complete edited video with stock footage, music, voiceover. `$15/mo`
- [Wisecut](https://www.wisecut.video) — Auto-cuts silences. Face tracking for dynamic zoom. Background music auto-ducking. `Free + $10/mo`
- [AutoPod](https://www.autopod.fm) — Premiere Pro plugin. Auto multi-cam editing for podcasts. Jump cut generator. `$29/mo`
- [Gling](https://www.gling.ai) — YouTube video editor. AI removes bad takes, silences, and filler words. `$8/mo`
- [Zubtitle](https://zubtitle.com) — Auto-caption videos. Social-optimized sizing. Headline generation from video. `$19/mo`

## Short-Form & Social

Tools optimized for TikTok, Reels, Shorts, and social media content.

- [Opus Clip](https://www.opus.pro) — Upload a long video, get 10+ shorts with captions and hooks. AI virality score. `Free + $15/mo`
- [Submagic](https://www.submagic.co) — Animated captions with emojis. Trending styles. Batch processing. `$9/mo`
- [Vizard](https://vizard.ai) — AI-powered clip maker. Auto-identifies best moments. Multi-platform formatting. `Free + $16/mo`
- [Klap](https://klap.app) — YouTube → Shorts/Reels/TikTok. AI selects highlights and adds captions. `$29/mo`
- [Munch](https://www.getmunch.com) — AI content repurposing. Extracts engaging clips from long content. `$49/mo`
- [Pictory](https://pictory.ai) — Script or blog → social video with stock footage and AI voiceover. `$19/mo`
- [Lumen5](https://lumen5.com) — Blog-to-video for social. AI matches visuals to text. Brand templates. `$19/mo`
- [Predis.ai](https://predis.ai) — Social media AI. Auto-generate video ads, carousels, reels from product links. `$24/mo`
- [Creatify](https://www.creatify.ai) — URL-to-video ads. Drop a product link, get a UGC-style video ad. `$39/mo`
- [Zebracat](https://www.zebracat.ai) — Text-to-video for marketing. AI-generated scenes + voiceover. `$23/mo`

## Music Video & Audio-Reactive

Generate or sync video to music and audio.

- [Kaiber](https://kaiber.ai) — Upload a track, get an AI music video. Multiple styles. Used by major artists. `$5/mo`
- [Neural Frames](https://www.neuralframes.com) — Stable Diffusion + audio-reactive motion. Per-beat prompt control. `$19/mo`
- [Deforum](https://deforum.github.io) — Open-source audio-reactive SD animation. ComfyUI + A1111 integrations. `Free`
- [HeyVid AI Music](https://heyvid.ai) — AI music generation (Suno) + video creation in one platform. Make soundtrack and visuals together. `Free + Credits`
- [Rotor Videos](https://rotorvideos.com) — Automated music video from your tracks. Beat-synced editing. `$4.99/video`
- [Vizzy](https://vizzy.io) — Real-time music visualization. Live performance visuals from audio. `Free + Pro`
- [Mootion](https://mootion.com) — AI dance/character animation from audio. Text-to-motion. `Free + Credits`
- [Steerable Motion](https://github.com/banodoco/Steerable-Motion) — Open-source audio-driven motion generation for ComfyUI. `Free`

## 3D & VFX

AI tools for 3D generation, visual effects, and volumetric video.

- [Wonder Studio](https://wonderdynamics.com) — Replace actors with CG characters automatically. Lighting + camera match. By Wonder Dynamics (acquired by Autodesk). `$9.99/mo`
- [Luma Genie](https://lumalabs.ai) — Text/image to 3D in seconds. Interactive 3D previews. `Free + Credits`
- [Meshy](https://www.meshy.ai) — Text/image to 3D models. PBR textures. Export to game engines. `Free + $20/mo`
- [Tripo](https://www.tripo3d.ai) — Fast 3D model generation from single images. High-fidelity mesh output. `Free + Credits`
- [Kaedim](https://www.kaedim3d.com) — 2D image to production-ready 3D asset. Game and VFX pipeline integration. `Custom pricing`
- [NeROIC](https://github.com/snap-research/NeROIC) — Neural rendering of objects from online image collections. Open-source. `Free`
- [DreamGaussian](https://github.com/dreamgaussian/dreamgaussian) — 3D generation in 2 minutes using Gaussian splatting. Open-source. `Free`
- [Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) — Real-time radiance field rendering. Foundation for 3D video. `Free`

## Upscaling & Enhancement

Make AI-generated (or any) video look better: higher resolution, smoother, more stable.

- [Topaz Video AI](https://www.topazlabs.com/topaz-video-ai) — Up to 16K. Deinterlace, stabilize, frame interpolation. The industry standard. `$199 one-time`
- [RIFE](https://github.com/hzwer/RIFE) — Open-source. Real-time frame interpolation. Smooth 24→60fps conversion. `Free`
- [FILM](https://github.com/google-research/frame-interpolation) — Google. High-quality frame interpolation. Production-grade slow motion. `Free`
- [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) — Open-source image/video upscaling. Works frame-by-frame with ffmpeg. `Free`
- [HitPaw Video Enhancer](https://www.hitpaw.com/video-enhancer.html) — AI upscaling + denoising. Face enhancement for old footage. `$39.99/mo`
- [CapCut Upscaler](https://www.capcut.com) — Free browser-based upscaling. Good enough for social media. `Free`
- [Waifu2x](https://github.com/nagadomi/waifu2x) — Open-source. Specialized for anime/illustration upscaling. `Free`
- [Video2X](https://github.com/k4yt3x/video2x) — Open-source framework wrapping multiple upscaling engines (RealESRGAN, waifu2x, SRMD). `Free`

## Subtitles & Captions

Automatic transcription, translation, and caption styling.

- [Captions](https://www.captions.ai) — AI captions with animated styles. Trending templates. Auto eye-contact correction. `$9.99/mo`
- [Submagic](https://www.submagic.co) — Emoji-integrated captions. Batch processing. Trending TikTok/Reels styles. `$9/mo`
- [Veed.io Subtitles](https://www.veed.io) — Auto-transcribe in 100+ languages. Translate and burn-in. `Free + $12/mo`
- [Kapwing Subtitles](https://www.kapwing.com/subtitles) — Browser-based. Auto-transcription with style customization. `Free + $16/mo`
- [Descript](https://www.descript.com) — Edit video by editing the transcript. AI speaker detection. `Free + $24/mo`
- [Happy Scribe](https://www.happyscribe.com) — Professional transcription and subtitles. 120+ languages. SRT/VTT export. `€12/mo`
- [Whisper](https://github.com/openai/whisper) — OpenAI's open-source speech recognition. Self-hostable. Best accuracy. `Free`
- [WhisperX](https://github.com/m-bain/whisperX) — Whisper with word-level timestamps and speaker diarization. `Free`
- [Zubtitle](https://zubtitle.com) — Auto-caption + auto-resize for social platforms. Headlines from video content. `$19/mo`
- [Nova AI](https://nova.ai) — Online subtitle editor. Auto-transcription + translation. Team collaboration. `Free + $10/mo`

## Face Swap & Deepfake

⚠️ Use responsibly and ethically. These tools have legitimate uses in filmmaking, localization, and entertainment.

- [FaceFusion](https://github.com/facefusion/facefusion) — Open-source face swapping and enhancement. Best open-source option. Active development. `Free`
- [Akool](https://www.akool.com) — Commercial face swap for marketing. Localization of ad creatives. `$30/mo`
- [DeepFaceLab](https://github.com/iperov/DeepFaceLab) — Open-source. Used in professional VFX. Steep learning curve but powerful. `Free`
- [Roop](https://github.com/s0md3v/roop) — Simple one-click face swap. ComfyUI node available. `Free`
- [SimSwap](https://github.com/neuralchen/SimSwap) — Open-source generalized face swap. Research-grade quality. `Free`
- [Reface](https://reface.ai) — Mobile app. Quick face swap for entertainment. GIF and video support. `Free + $4.99/mo`

## Screen Recording & Tutorials

Create professional tutorial and demo videos with AI assistance.

- [Descript](https://www.descript.com) — Record screen + webcam. Edit by editing text. Remove "ums" automatically. `Free + $24/mo`
- [Loom](https://www.loom.com) — Async video messaging. AI summary. Viewer analytics. Now part of Atlassian. `Free + $12.50/mo`
- [Tella](https://www.tella.tv) — Beautiful screen recordings. Multi-layout. Zoom effects. No editing needed. `Free + $15/mo`
- [Screen Studio](https://www.screen.studio) — macOS only. Auto-zoom, beautiful motion, export presets. `$89 one-time`
- [Guidde](https://www.guidde.com) — Auto-generate step-by-step video guides from screen recordings. `Free + $16/mo`
- [Scribe](https://scribehow.com) — Auto-document processes. Turns clicks into step-by-step guides with screenshots. `Free + $23/mo`

## Open Source Models

Self-hostable models with public weights. Sorted by date, newest first.

### Text-to-Video

- [**Wan 2.1**](https://github.com/Wan-Video/Wan2.1) — Alibaba. 1.3B & 14B params. 480p-720p. Best open-source quality. Apache 2.0. [Paper](https://arxiv.org/abs/2503.20314)
- [**HunyuanVideo**](https://github.com/Tencent/HunyuanVideo) — Tencent. 13B params. 720p. Full attention. Apache 2.0. [Paper](https://arxiv.org/abs/2412.03603)
- [**LTX-Video**](https://github.com/Lightricks/LTX-Video) — Lightricks. Real-time generation. Lightweight. Apache 2.0. [Paper](https://arxiv.org/abs/2501.00103)
- [**CogVideoX**](https://github.com/THUDM/CogVideo) — Tsinghua/Zhipu. 2B & 5B. Expert Transformer. Apache 2.0. [Paper](https://arxiv.org/abs/2408.06072)
- [**Mochi 1**](https://github.com/genmoai/mochi) — Genmo. Asymmetric DiT. Good motion. Apache 2.0.
- [**Pyramid Flow**](https://github.com/jy0205/Pyramid-Flow) — ByteDance. 10s at 768p. MIT. [Paper](https://arxiv.org/abs/2410.05954)
- [**Open-Sora**](https://github.com/hpcaitech/Open-Sora) — Community. Up to 16s at 720p. Apache 2.0. Active development.
- [**Open-Sora-Plan**](https://github.com/PKU-YuanGroup/Open-Sora-Plan) — PKU. Efficient training focus. MIT.

### Image-to-Video & Animation

- [**Stable Video Diffusion**](https://github.com/Stability-AI/generative-models) — Stability AI. 4s at 576×1024. The I2V foundation model.
- [**AnimateDiff**](https://github.com/guoyww/AnimateDiff) — ByteDance. Motion module for any SD checkpoint. Works with existing LoRAs. Apache 2.0.
- [**LivePortrait**](https://github.com/KwaiVGI/LivePortrait) — Kuaishou. Portrait animation. Efficient stitching + retargeting.
- [**ToonCrafter**](https://github.com/ToonCrafter/ToonCrafter) — Cartoon interpolation. In-between frame generation.

### Utilities

- [**ComfyUI**](https://github.com/comfyanonymous/ComfyUI) — Node-based workflow editor. Supports all models above. The hub of open-source AI video.
- [**Diffusers**](https://github.com/huggingface/diffusers) — Hugging Face Python library. `pip install diffusers`. All major models.
- [**ProPainter**](https://github.com/sczhou/ProPainter) — Video inpainting with flow-guided propagation.
- [**RIFE**](https://github.com/hzwer/RIFE) — Real-time frame interpolation.

## ComfyUI Ecosystem

Node packages and workflows for ComfyUI — the open-source backbone of AI video.

- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper) — Wan 2.1 T2V/I2V. LoRA support, controlnet integration.
- [ComfyUI-HunyuanVideoWrapper](https://github.com/kijai/ComfyUI-HunyuanVideoWrapper) — HunyuanVideo with memory optimization.
- [ComfyUI-AnimateDiff-Evolved](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved) — Advanced AnimateDiff. Motion LoRAs, camera controls, prompt travel.
- [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) — Load, combine, split, export videos. Essential utilities.
- [ComfyUI-Frame-Interpolation](https://github.com/Fannovel16/ComfyUI-Frame-Interpolation) — FILM + RIFE for smooth slow-motion.
- [ComfyUI-Advanced-ControlNet](https://github.com/Kosinkadink/ComfyUI-Advanced-ControlNet) — Depth, pose, edge control for guided generation.
- [ComfyUI-LivePortraitKJ](https://github.com/kijai/ComfyUI-LivePortraitKJ) — Portrait animation from reference + driving video.
- [ComfyUI-CogVideoXWrapper](https://github.com/kijai/ComfyUI-CogVideoXWrapper) — CogVideoX T2V/I2V with LoRA support.
- [ComfyUI-LTXVideo](https://github.com/Lightricks/ComfyUI-LTXVideo) — Official LTX-Video nodes. Fast generation.
- [ComfyUI-IP-Adapter](https://github.com/cubiq/ComfyUI_IPAdapter_plus) — Image prompt adapter for style/character consistency.
- [Steerable Motion](https://github.com/banodoco/Steerable-Motion) — Controlled camera + subject motion presets.
- [comfyui-reactor-node](https://github.com/Gourieff/comfyui-reactor-node) — Face swap with frame-to-frame consistency.

## APIs & Developer Tools

### Commercial

- [Runway API](https://docs.runwayml.com) — Gen-3 Alpha. Per-second billing. REST + webhooks.
- [Luma API](https://docs.lumalabs.ai) — Dream Machine. Fast generation. Competitive pricing.
- [Kling API](https://docs.qingque.cn) — Kling 2.0. Free tier available.
- [Minimax API](https://www.minimaxi.com/platform) — Hailuo video. Good docs.
- [Stability AI API](https://platform.stability.ai) — SVD + image models. Credits-based.
- [D-ID API](https://docs.d-id.com) — Talking heads. Real-time streaming.
- [HeyGen API](https://docs.heygen.com) — Avatar video. Webhooks for async.
- [Synthesia API](https://docs.synthesia.io) — Enterprise avatars. Custom avatar support.

### Open-Source Hosting

- [Replicate](https://replicate.com) — `replicate.run("wan-ai/wan2.1-t2v-14b")`. One-line API.
- [fal.ai](https://fal.ai) — Fast inference. Queue management. Low cold starts.
- [Modal](https://modal.com) — Serverless GPU. Define pipelines in Python. Auto-scaling.
- [Banana](https://www.banana.dev) — GPU inference as a service. Custom model deployment.

## Prompt Templates

Copy-paste templates that work across most models. Customize the bracketed parts.

### Cinematic Shots

```
Slow dolly push-in on [subject] in [setting], [lighting] casting [shadow/reflection
description], shallow depth of field, shot on ARRI Alexa, cinematic color grading,
[mood] atmosphere, 24fps
```

```
Aerial drone shot sweeping over [landscape/cityscape] at [time of day], gradually
descending to reveal [key subject], [weather conditions], natural lighting,
National Geographic photography style
```

```
Tracking shot following [character description] walking through [environment],
[background activity], [lighting conditions], handheld documentary style,
subtle camera shake, anamorphic lens flare
```

### Product & Commercial

```
Smooth 360-degree orbit around [product] on [surface material], dramatic rim lighting
revealing [texture/material details], [color] accent light, studio environment,
commercial photography style, 4K
```

```
Extreme close-up macro shot of [product detail], rack focus from [foreground element]
to [product], [liquid/particle effect], clean white background, product photography
```

### Artistic & Abstract

```
[Art style] painting coming to life, [subject] slowly [motion description], colors
bleeding and morphing between [color palette], painterly brushstroke textures visible,
gallery lighting, [artist name] inspired
```

```
Ink drops falling into clear water in extreme slow motion, blooming into [shape]
patterns, morphing from [form A] into [form B], [color palette], macro photography,
ethereal mood
```

### Action & Dynamic

```
[Character description] performing [action] in slow motion, [environmental particles]
frozen mid-air, dramatic [lighting direction] lighting, [camera angle], high-speed
camera effect, 120fps feel, [genre] movie style
```

### Negative Prompt (Use with all)

```
blurry, distorted, deformed, low quality, pixelated, watermark, text overlay,
extra fingers, mutated hands, poorly drawn face, out of frame, duplicate,
temporal flickering, morphing artifacts, inconsistent lighting
```

## Learning Resources

### Getting Started

- [AI Video Generation: Complete Beginner's Guide](https://heyvid.ai/blog) — Covers all major tools with step-by-step instructions
- [Runway Academy](https://academy.runwayml.com) — Free official courses. Gen-3 Alpha and creative workflows
- [Pika Prompt Guide](https://pika.art/blog) — Official tips for better Pika results
- [ComfyUI Examples](https://comfyanonymous.github.io/ComfyUI_examples/video/) — Official video generation workflow examples

### Intermediate

- [AnimateDiff in ComfyUI](https://stable-diffusion-art.com/animatediff-comfyui/) — Setup guide with example workflows
- [Video Upscaling Pipeline](https://stable-diffusion-art.com/video-upscale/) — Generation + upscaling for maximum quality
- [LoRA Training for Video](https://github.com/kijai/ComfyUI-WanVideoWrapper/blob/main/docs/training.md) — Fine-tune Wan 2.1 on custom data

### Developer

- [Replicate Video Guide](https://replicate.com/docs/guides/video-generation) — API integration with Python/Node.js
- [fal.ai Quickstart](https://fal.ai/docs/quickstart) — Deploy video generation in 5 minutes
- [Diffusers Video Tutorial](https://huggingface.co/docs/diffusers/using-diffusers/text-to-video) — Hugging Face library tutorial

### YouTube Channels

- [Olivio Sarikas](https://www.youtube.com/@OlivioSarikas) — In-depth AI video tool reviews
- [Matt Wolfe](https://www.youtube.com/@MattVidPro) — AI tools overview and comparisons
- [Aitrepreneur](https://www.youtube.com/@Aitrepreneur) — Open-source AI workflows
- [Nerdy Rodent](https://www.youtube.com/@NerdyRodent) — Technical deep dives into video models
- [Sebastian Kamph](https://www.youtube.com/@sebastiankamph) — ComfyUI and SD video workflows
- [Theoretically Media](https://www.youtube.com/@TheoreticMedia) — AI filmmaking and creative applications

### Communities

- [r/aivideo](https://reddit.com/r/aivideo) — Main Reddit community. Prompts, comparisons, tutorials
- [r/StableDiffusion](https://reddit.com/r/StableDiffusion) — AnimateDiff and video gen discussions. 1M+ members
- [r/RunwayML](https://reddit.com/r/RunwayML) — Runway community. Gen-3 tips and showcases
- [Civitai](https://civitai.com) — Model hub. Video LoRAs, motion modules, workflows
- [Hugging Face](https://huggingface.co/models?pipeline_tag=text-to-video) — Open model hub. Papers, model cards, Spaces demos
- [ComfyUI Discord](https://discord.gg/comfyorg) — Technical support and workflow sharing
- [Banodoco Discord](https://discord.gg/banodoco) — Steerable Motion and open-source video community

### Benchmarks

- [Artificial Analysis Video Arena](https://artificialanalysis.ai/text-to-video/arena) — Elo ranking from blind human comparisons
- [VBench](https://github.com/Vchitect/VBench) — 16-dimension evaluation suite. [Paper](https://arxiv.org/abs/2311.17982)
- [EvalCrafter](https://github.com/EvalCrafter/EvalCrafter) — Multi-aspect evaluation. [Paper](https://arxiv.org/abs/2310.11440)

---

## Multi-Language Access

AI video tools work best when the interface is in your language:

| | | |
|---|---|---|
| 🇺🇸 [English](https://heyvid.ai) | 🇪🇸 [Español](https://heyvid.ai/es) | 🇫🇷 [Français](https://heyvid.ai/fr) |
| 🇩🇪 [Deutsch](https://heyvid.ai/de) | 🇯🇵 [日本語](https://heyvid.ai/ja) | 🇰🇷 [한국어](https://heyvid.ai/ko) |
| 🇧🇷 [Português](https://heyvid.ai/pt) | 🇮🇹 [Italiano](https://heyvid.ai/it) | 🇷🇺 [Русский](https://heyvid.ai/ru) |
| 🇨🇳 [简体中文](https://heyvid.ai/zh) | 🇹🇼 [繁體中文](https://heyvid.ai/zh-Hant) | 🇹🇷 [Türkçe](https://heyvid.ai/tr) |
| 🇮🇩 [Indonesia](https://heyvid.ai/id) | 🇹🇭 [ไทย](https://heyvid.ai/th) | 🇵🇱 [Polski](https://heyvid.ai/pl) |
| 🇳🇱 [Nederlands](https://heyvid.ai/nl) | 🇩🇰 [Dansk](https://heyvid.ai/da) | 🇳🇴 [Norsk](https://heyvid.ai/nb) |

---

## Contributing

Found a tool that's missing? Information that's outdated? We'd love your help.

1. **Fork** this repository
2. **Add or update** entries following the existing format: `- [Tool Name](url) — Description. \`Pricing\``
3. **Submit a pull request** with a brief explanation

Guidelines:
- Tool must be publicly available and actively maintained
- Include accurate pricing
- Test before submitting — don't add tools you haven't tried
- Check for duplicates

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

CC0 1.0 Universal. Copy, modify, distribute freely.

---

<div align="center">

**⭐ Star this repo if it helped you find the right tool!**

*Maintained by the community. Last verified: February 2026.*

</div>
