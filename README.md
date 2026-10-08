<img src="icon.png" width="72" alt="Lapis logo">

# Lapis for Windows

Lapis is a layer-based photo editor with built-in AI. It runs fully offline, needs no account, and your files never leave your computer.

**[Download the latest version](https://github.com/mesdsky/lapis-releases/releases/latest)**: open the release, then download `Lapis-Setup-<version>.exe`.

## What's inside

- Photoshop-style layers, masks, adjustments, filters, brushes, selections, type and shapes
- Figma-style infinite canvas: frames, sections and pages; export any frame as PNG or JPG at 1x–4x
- Built-in AI, all on your device: Remove Background, Select Subject, Object Selection, Remove tool / Content-Aware Fill, Upscale ×2/×4, Lens Blur
- PSD import and export, plugins

## Install

1. Download `Lapis-Setup-<version>.exe` (about 390 MB, because the AI models are included).
2. Run it. The installer isn't code-signed yet, so Windows may show **"Windows protected your PC"**. Click **More info → Run anyway**.
3. Choose a folder and finish. Lapis appears on your desktop and in the Start menu.

Your files are stored in `%APPDATA%\Lapis\data`. Uninstall from **Settings → Apps**.

Requirements: Windows 10 or 11 (64-bit). A GPU with WebGPU support makes the "Best" background removal and Upscale faster, but isn't required.

## Verify the download

Each release lists the SHA-256 of the installer. In PowerShell:

```powershell
Get-FileHash .\Lapis-Setup-1.0.0.exe -Algorithm SHA256
```

## Licences

Lapis bundles open models and libraries under permissive licences: MODNet, SlimSAM, Swin2SR and Depth Anything V2 Small (Apache-2.0); BiRefNet_lite and MI-GAN (MIT); Transformers.js (Apache-2.0); ONNX Runtime Web (MIT); ag-psd (MIT); Electron (MIT).
