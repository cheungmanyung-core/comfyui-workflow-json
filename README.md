# 🎨 ComfyUI Professional Workflows

![ComfyUI](https://img.shields.io/badge/AI-ComfyUI-blue)
![Status](https://img.shields.io/badge/Workflow-JSON-orange)
![Category](https://img.shields.io/badge/Style-Tech%203D-purple)

## 📖 Overview
This repository hosts custom **ComfyUI Workflows** designed for generating high-quality UI assets, specifically focusing on **3D Frosted Glass Icons** and **Abstract Tech Backgrounds**.

These workflows utilize advanced node configurations including `ControlNet` for shape guidance and `Ultimate SD Upscale` for high-resolution output.

## 🖼️ Workflow Features
- **Modular Design:** Nodes are grouped for easy customization (Prompt, Style, Upscale).
- **ControlNet Integration:** Ensures generated icons strictly follow the input shape outline.
- **Hires. Fix:** Built-in latent upscaling for crisp edges at 4K resolution.
- **Metadata Embedding:** Automatic prompt saving into PNG chunks.

## 🛠️ Repository Structure

```text
├── workflows/
│   ├── glass_icon_gen.json    # The core workflow file
│   └── cyberpunk_bg.json      # (Coming Soon) Background generator
└── README.md
```
## 💻 How to Use

### 1\. Download

Download the `.json` files from the `workflows/` folder.

### 2\. Import to ComfyUI

1.  Open your local ComfyUI interface.
2.  Click **"Load"** in the menu bar.
3.  Select the downloaded `.json` file.
4.  (Optional) Install missing nodes using **ComfyUI Manager**.

### 3\. Generate

  - Load your preferred Checkpoint (Recommended: `revAnimated` or `DreamShaper`).
  - Click **Queue Prompt**.

## 📊 Parameters

| Setting | Value |
| :--- | :--- |
| **Sampler** | DPM++ 2M Karras |
| **Steps** | 30 - 40 |
| **CFG Scale** | 7.0 |
| **Upscale** | 2x (Latent) |

## 📝 License

MIT License. Feel free to use these workflows in your own projects.

```
