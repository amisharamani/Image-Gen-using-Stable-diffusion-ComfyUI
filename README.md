# Image Generation using Stable Diffusion & Comfy UI

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/amisharamani/Image-Gen-using-Stable-diffusion-ComfyUI)

A user-friendly AI image generation system that converts text prompts into high-quality images using **Stable Diffusion** and **ComfyUI**. Designed for accessibility and efficiency, this project simplifies AI-driven creativity for both technical and non-technical users.

---

## ✨ Features
- **Text-to-Image Generation**: Create visuals from textual prompts.
- **Real-Time Updates**: Generate new images without refreshing the page.
- **Optimized Performance**: Faster processing with advanced samplers and CUDA GPU support.
- **Customizable Parameters**: Adjust settings for better output control.

---

## 🛠️ Installation & Setup

### Prerequisites
#### Hardware Requirements
- **CPU**: Modern multi-core processor (Intel/AMD).
- **RAM**: 8GB or higher.
- **GPU** (Recommended): NVIDIA GPU with ≥4GB VRAM for accelerated performance.

#### Software Requirements
- **ComfyUI**: [Download ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- **Stable Diffusion Model**: [Download v1-5-pruned-emaonly-fp16.safetensors](https://huggingface.co/Comfy-Org/stable-diffusion-v15-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors)

---

## 🚀 Getting Started

### Step 1: Extract ComfyUI
1. Download the `ComfyUI_windows_portable.zip` file from the [ComfyUI GitHub](https://github.com/comfyanonymous/ComfyUI).
2. Extract the ZIP file to a folder of your choice.

### Step 2: Place the Stable Diffusion Model
1. Navigate to the extracted folder:  
   `ComfyUI_windows_portable → ComfyUI → models → checkpoints`
2. Place the downloaded Stable Diffusion model (`v1-5-pruned-emaonly-fp16.safetensors`) into the `checkpoints` folder.

### Step 3: Run ComfyUI
1. Go back to the `ComfyUI_windows_portable` directory.
2. Choose the appropriate batch file:
   - **For GPU (NVIDIA)**: Double-click `run_nvidia_gpu.bat`  
     *(Recommended for faster performance)*
   - **For CPU-only**: Double-click `run_cpu.bat`
3. Wait for the server to start. A browser window will open automatically at `http://127.0.0.1:8188`.

---

## 🖼️ Usage
1. **Enter a Prompt**: Type your text description in the input field (e.g., "A mystical waterfall in a tropical rainforest").
2. **Generate Image**: Click "Generate" to create the image.
3. **Adjust Parameters** (Optional): Modify sampling steps, CFG scale, or negative prompts for better results.
4. **Download**: Save the generated image to your device.

---

## 📜 References
- [ComfyUI GitHub Repository](https://github.com/comfyanonymous/ComfyUI)
- [Stable Diffusion Documentation](https://huggingface.co/CompVis/stable-diffusion)
- [Project Report PDF](Project%20Report.pdf)

---

## 🙏 Acknowledgments
Special thanks to mentors **Mr. Adharsh P** and **Mr. Jay Rathod** for their guidance during this project. Developed under the **Internship on AI** by Microsoft, SAP, Edunet Foundation and AICTE.
