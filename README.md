<h1 align="center">Anti-Comic-Chaos-Tool</h1>
<h3 align="center">Tame your comic collection.</h3>

<p align="center">
  <img src="https://comixz.github.io/acct-comic-collection-software-main-window.jpg" alt="Anti-Comic-Chaos-Tool main window: comic collection list with front and back covers, grouped series and collection status counters">
</p>

<p align="center">
  <a href="https://github.com/ComixZ/Anti-Comic-Chaos-Tool/releases/latest"><strong>⬇️ Download v1.11.2026</strong></a>
  &nbsp;·&nbsp;
  <a href="https://comixz.github.io/">Website</a>
</p>

<p align="center"><em>Free · portable · Windows 10/11 · no installer</em></p>

---

**Bring order to your comic, manga, and graphic novel collection – no installation, no subscription, no cloud required.**

Anti-Comic-Chaos-Tool (ACCT) is a lightweight, portable desktop application that keeps precise track of which comics, manga, single issues, and collected editions you already own. Whether you have 10 volumes or thousands of items, it gives you the overview that a spreadsheet or your memory eventually can’t. And unlike collection software made for stamps or books, ACCT understands the quirks of comics.

A proper desktop program in delightfully quirky, old-school style, but with a modern engine, and it’s proud of it. No mobile app, no swipe, no pinch-to-zoom, no “tap here to rate us”. It runs on a real computer, with a big monitor, a real mouse, a real keyboard, a cup of coffee, and windows that stay exactly where you put them.

## ✨ Why choose ACCT as your comic collection manager?

- **No installation required** – one folder, one .exe. Just launch it and it works. Copy it to a USB stick and your entire collection runs on any other PC too.
- **Completely free, no ads, no tracking** – licensed under the PolyForm Noncommercial License, free for any non-commercial use.
- **Works offline** – no registration, no mandatory cloud usage, and no internet connection required for ACCT (except for optional comic web searches and optional plugins).
- **Web Import** – searches the web for data and cover art for your comics. (Currently only for German comics.)
- **Built for the quirks of comic collections** – not generic inventory lists.
- **Collected editions** – thick omnibus volumes cleanly linked to the individual issues they contain.
- **Anthologies** – multiple stories by different artists/writers within one issue, tracked individually.
- **Special editions** – do you have comics with variant covers, limited editions, or prints? Simply add them.
- **Previews** – always a quick look at the best pages, or even all of them ;)
- **Groups** – bundle series and spin-offs together, including custom images for slipcases, characters, and artwork.
- **Batch creation** – add ten, twenty, or a hundred issues of a series with individual covers in one go instead of typing them in one by one.
- **Modern image formats** – PNG, JPG, WebP, BMP, GIF, TIFF, and AVIF.
- **Self-cleaning collection** – built-in tools find orphaned cover files and duplicates (via image similarity detection, not just filename matching) and automatically repair missing thumbnails.
- **Import & export between databases** – move or copy comics between collections as needed, including automatic duplicate detection.
- **Fast to search & filter** – full-text search, color-coding by collection status, sortable series overview.
- **Backup** – safety first.
- **Accessories** – does your collection also include slipcases, figures, prints, and posters? You can manage those too.
- **CBR/CBZ** – add covers from comic archives.
- **PDF** – add covers from PDF comics. This is optional and can be downloaded separately as a plugin.
- **Upscale** – enlarge and improve the image quality of your covers with AI. This is optional and can be downloaded separately as a plugin.
- **Watermark Eraser** – remove distracting watermarks or price stickers with AI. This is optional and can be downloaded separately as a plugin.
- **Share your comics** – optionally back up your data online, access it from anywhere, or share it with friends and the community.

<p align="center">
  <img src="https://comixz.github.io/acct-comic-cover-zoom-viewer.jpg" alt="ACCT comic cover viewer: zoom into a comic cover in full detail, with pan and close controls">
</p>

## 📦 Getting started

1. [Download the latest release](https://github.com/ComixZ/Anti-Comic-Chaos-Tool/releases/latest)
2. Unzip – `acct.exe`, `comic.ini`, and the corresponding `DB_*` folder must stay in the same directory
3. Launch – done

No admin rights, no installer, no registry entries.

## 🖥️ System requirements

- **Windows 10 or Windows 11** (64-bit)
- **Disk space:** 27 MB for the main program, 193 MB for optional AI plugins.
- **Any ordinary PC:** no special hardware needed for the main program.
- **Graphics card:** optional AI plugins (Upscale, Watermark Eraser): a graphics card is not required. They use any DirectX 12 capable GPU (NVIDIA, AMD or Intel) if available and automatically fall back to the CPU otherwise – just sloooooower.

<p align="center">
  <img src="https://comixz.github.io/acct-comic-database-edit-comic.jpg" alt="ACCT comic database: edit comic dialog with cover price, condition, ownership status and AI cover upscale">
</p>

## 🔧 Development

ACCT is written in Rust using the egui GUI library (0.37.0). It was first released in August 2026 and is under continuous development. A new, revised version is released every one to two months, for as long as I have the time and inclination. Updates are always cumulative and backward compatible. So don’t worry, new features won’t break your database! Oh wait, there’s more … Bugs are just features with zero followers.

## 🔨 In progress

- **Spine** – admire all matching book spines as one complete work
- **Export** – HTML, PDF, CSV
- **Your ideas** – tell me what’s missing

## 💬 Feedback

Your feedback is pure gold: tell me what rocks, what sucks, and what’s still missing. Love it, hate it, or think it’s all junk? Go ahead, the bugs and the zombie squirrel have thick skin. (Almost.) You can help me make ACCT better with every update.

<p align="center">
  <img src="https://comixz.github.io/acct-comic-collection-check-duplicate-covers.jpg" alt="ACCT comic collection software: check covers dialog to find duplicate covers, unused cover files and comics without a cover, next to the layout settings">
</p>

## 💐 Credits

- **Watermark Remover Plugin**
  Model: MI-GAN (ICCV 2023), Picsart AI Research (Andranik Sargsyan and others)
  Project: <https://github.com/Picsart-AI-Research/MI-GAN>
  ONNX export used by ACCT: `migan_pipeline_v2.onnx`
  andraniksargsyan at <https://huggingface.co/andraniksargsyan/migan>

- **Upscale Plugin**
  Model: Real-ESRGAN (x2plus and x4plus). Created by Xintao Wang, Liangbin Xie, and others (Tencent ARC Lab)
  Project: <https://github.com/xinntao/Real-ESRGAN>
  ONNX exports used by ACCT: `RealESRGAN_x2plus.onnx` and `RealESRGAN_x4plus.onnx`
  SceneWorks at <https://huggingface.co/SceneWorks/real-esrgan-onnx>

## 📜 License

ACCT is free to use for any non-commercial purpose, for example managing your own collection, hobby use, or sharing with friends. You may copy and redistribute it as long as you include this license notice. Commercial use is not permitted.

Licensed under the [PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/).

## ⚖️ Disclaimer

This software is provided “as is”, without warranty of any kind. To the extent permitted by law, the author accepts no liability for data loss or corruption, damage to your system or hardware, or any direct, indirect, or consequential damages arising from the use of this software.

Some functions (for example image compression, upscaling and watermark removal) replace existing image files, and this cannot be undone. Use is at your own risk. Please back up your data before use.

## 📢 Contact

Questions? Bugs? Ideas? → **comixz@tuta.io**

<p align="center">
  <img src="https://comixz.github.io/comixz_logo.png" alt="ComixZ" width="160">
</p>
