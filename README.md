# ImageForge Pro v2.0 

Privacy-first alternative to remove.bg, TinyPNG, and Canva.

---

🏷️ Free Web Interface: https://urtworkmail.github.io/ImageForge/

---


## Features 

1. **Background Remover** – Local AI model (RMBG-1.4 via Transformers.js), no upload
2. **Compressor** – JPG/PNG/WebP with quality control, see bytes saved
3. **Resize** – Instagram, LinkedIn, CV presets with aspect lock
4. **Format Converter** – Batch convert to JPG/PNG/WebP, download ZIP
5. **2x Upscaler** – High-quality canvas upscale

## Why it matters

remove.bg charges $0.20/image after free quota and uploads your photos. ImageForge runs the AI model **in your browser**. First load downloads ~40MB model, then works forever offline.

---

### 🆚2.0 New Updates 

Fixes:

Remove BG now uses @imgly/background-removal (the industry standard WASM/ONNX library) instead of the broken Xenova model — this actually works reliably, caches after first download, and produces pro-grade results

New & Upgraded:

Batch Remove BG — process up to 20 images in one go with per-card status
Speed / Precise toggle — chooses model size accordingly
Quick Cutout fallback — instant chroma-key if you don't want to wait for the model
Lanczos-3 Upscaling via a real Web Worker — mathematically correct, far sharper than plain canvas, with Unsharp Mask baked in; 2× or 4×
Color Studio (NEW) — 12 film presets (Kodak Gold, Fuji Velvia, Noir, etc.) with live thumbnails of your actual image + 8 manual sliders (brightness, contrast, saturation, hue, temperature, fade, vignette, grain) + drag split-compare
Inpaint Eraser (NEW) — draw a box over any region (watermark, object, text), BFS-propagation fill reconstructs the background from surrounding pixels
Batch Convert with Download All button
All download buttons work, all edge cases handled

MIT Licensed.
