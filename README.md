# 🎥 Awesome Sora Watermark Removal Tools

A curated collection of **open-source** and **online tools** for removing or enhancing Sora-generated videos and images.
Whether you’re researching AI inpainting, improving video quality, or exploring watermark detection, this list keeps everything organized.

---

## ⚠️ Legal & Ethical Notice

Removing AI watermarks may violate platform terms or copyright law.
This repository is intended **for research, education, and authorized content only**.
Always confirm you have the right to process the media before using any tool.

---

## 🧰 1. Open-Source Tools

Below are open-source projects you can self-host, modify, or use offline:

| No. | Name                  | Link                                                               | Stars                                                                                                   | Last commit                                                                                     | Description                                                                                                                                                   | License     | Notes                                                                                               |
| --- | --------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | --------------------------------------------------------------------------------------------------- |
| 1   | SoraWatermarkCleaner  | [GitHub](https://github.com/linkedlist771/SoraWatermarkCleaner)    | ![GitHub stars](https://img.shields.io/github/stars/linkedlist771/SoraWatermarkCleaner)    | ![Last commit](https://img.shields.io/github/last-commit/linkedlist771/SoraWatermarkCleaner)    | Removes Sora 2 video watermarks using YOLO-based detection and LaMA inpainting; supports batch processing, Colab-ready, one-click portable version available. | Apache 2.0  | Works well on most Sora 2 videos; new watermark with username works better with updated YOLO model. |
| 2   | Sora2WatermarkRemover | [GitHub](https://github.com/GitHub30/Sora2WatermarkRemover)        | ![GitHub stars](https://img.shields.io/github/stars/GitHub30/Sora2WatermarkRemover)        | ![Last commit](https://img.shields.io/github/last-commit/GitHub30/Sora2WatermarkRemover)        | Removes Sora 2 video watermarks using LaMA inpainting; Colab-ready.                                                                                           | MIT         | Doesn’t work fully; only removes Sora’s cloud watermark, text remains.                              |
| 3   | Sowaker               | [GitHub](https://github.com/JuliaGomesRoel/Sora-Watermark-Remover) | ![GitHub stars](https://img.shields.io/github/stars/JuliaGomesRoel/Sora-Watermark-Remover) | ![Last commit](https://img.shields.io/github/last-commit/JuliaGomesRoel/Sora-Watermark-Remover) | AI-powered watermark, logo, and text removal for photos/videos; Claude + GPT-5 hybrid engine; preserves textures and edges; fast GPU processing.              | Proprietary | Works well for personal photos/videos; highly realistic results, no blur or artifacts.              |
| 4   | Sweeta                | [GitHub](https://github.com/Kuberwastaken/sweeta)                  | ![GitHub stars](https://img.shields.io/github/stars/Kuberwastaken/sweeta)                  | ![Last commit](https://img.shields.io/github/last-commit/Kuberwastaken/sweeta)                  | AI-powered Sora 2 video watermark removal using LaMA inpainting; supports GUI, CLI, Colab; preserves original quality.                                        | Apache 2.0  | Recommended specs: Windows/macOS/Linux, 16GB+ RAM, NVIDIA GPU 4GB+; fast and accurate removal.      |
| 5   | Sora2 Watermark Remover | [GitHub](https://github.com/YourOrg/Sora2-Watermark-Remover) | ![GitHub stars](https://img.shields.io/github/stars/YourOrg/Sora2-Watermark-Remover) | ![Last commit](https://img.shields.io/github/last-commit/YourOrg/Sora2-Watermark-Remover) | AI-powered desktop/web tool for Sora-generated videos; frame-by-frame inpainting with interactive masking; supports multi-format and batch processing. | MIT     | Local processing only; supports MP4/MOV/MKV/WebM; includes manual mask editor and batch queue. |



---

## 🌐 2. Online Tools

Web-based tools for quick watermark removal without installation:

| No. | Name                                 | Link                                                                                               | Description                                                                                          | Notes                                                                                               |
| --- | ------------------------------------ | -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| 1   | MagicEraser – Sora Watermark Remover | [magiceraser.org/sora-watermark-remover](https://magiceraser.org/sora-watermark-remover/)          | AI-powered online tool to remove Sora 2 video watermarks in seconds; no installation required.       | Works entirely online; upload and one-click removal; free trial available.                          |
| 2   | ImgUpscaler – Sora Enhancer          | [imgupscaler.ai/sora-enhancer](https://imgupscaler.ai/sora-enhancer/)                              | Online AI enhancer that upscales and restores Sora videos to higher resolution and improved clarity. | Focused on quality enhancement rather than watermark removal; ideal for Sora 2 content restoration. |
| 3   | Sider.ai – Sora Video Downloader     | [sider.ai/create/video/sora-video-downloader](https://sider.ai/create/video/sora-video-downloader) | Online tool for downloading and saving Sora-generated videos directly from the web.                  | Download utility, not watermark removal; check content rights before use.                           |

---

## 🧩 Usage Tips

* 🧠 **Try open-source first** for privacy and reproducibility.
* ☁️ **Use online tools** for quick testing or small media.
* 💾 Keep backups of original videos before processing.
* ⚙️ GPU acceleration improves LaMA or iopaint-based models significantly.
* 🚫 Avoid removing watermarks from copyrighted or third-party content.

---

## 🧡 Credits & References

* [IOPaint](https://github.com/Sanster/IOPaint) – Base implementation for LaMA inpainting
* [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) – Watermark detection backbone
* [ComfyUI](https://github.com/comfyanonymous/ComfyUI) – Frame-level inpainting workflow
* [Shields.io](https://shields.io) – Dynamic badges for stars & commits

---

## 🚀 Contribution

Want to add a new Sora-related watermark or enhancement tool?
Open a PR or submit an issue with:

* Project name
* Repository or website link
* License type
* Short description (≤ 100 chars)

---

## 🏁 License

This list is released under the **CC BY 4.0 License** — attribution required.
Each tool retains its own individual license (MIT, Apache 2.0, Proprietary, etc.).

---

**Maintained by the community.**
⭐ Star this repo to support updates and discover new Sora watermark tools!
