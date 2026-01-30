# InferenceDesk

InferenceDesk is a **Windows desktop app** by **Local AI Solutions** for running local, on-device inference with llama-compatible open-source models (CPU or GPU).

> **Beta release (free)**
>
> InferenceDesk is currently in **beta** and is **free to use** while I collect feedback, resolve issues, and improve stability.
>
> If you run into issues or have ideas, please email **localmind1234@gmail.com**.

## Download

- **Windows (Installer)**: https://pub-277c819c500843e1b195cb5fa8d0a929.r2.dev/apps/builds/win/InferenceDesk-1.0.0-Setup.exe

By downloading or using InferenceDesk, you agree to the **Terms of Service** and **Privacy Policy**.

- **Terms**: [TERMS.md](./TERMS.md)  
- **Privacy**: [PRIVACY.md](./PRIVACY.md)

> **Windows Defender / SmartScreen notice**
>
> When you run the installer, Windows may show a “Windows protected your PC” screen (SmartScreen).  
> If that happens, click **More info** → **Run anyway**.
>
> I’m in the process of publishing a signed build so this prompt should go away in a future release.

## What you can do with InferenceDesk

InferenceDesk is built for people who want **private, local AI capabilities** on their own machine.

- Run **llama-compatible** open-source models locally (CPU and GPU)
- Run models **side-by-side** for comparisons (A/B)
- **Knowledge / RAG**: upload documents (CSV, TXT, MD, PDF) and use them as context in chat
- Tune **prompt + inference settings** (and other model parameters)
- Customize **appearance** and chat experience
- **Structured output** support (for workflows that need predictable formats)
- **Speculative decoding** support (where compatible)
- **Plugins** (capability support for extending the app)
- **Developer sandbox** with logs and **callable endpoints** so you can invoke the model programmatically
- **Hugging Face integration** for browsing/downloading models
- Engine/runtime support: **CPU, CUDA, ROCm, Vulkan**
- **Harmony framework support** for OSS-GPT style models *(experimental; still in progress)*

## Requirements

- **OS**: Windows 10 or 11
- **Hardware**: Sufficient RAM and disk space for the app and your models  
  - Optional GPU acceleration (NVIDIA CUDA, AMD ROCm, or Vulkan) for faster inference
- **Network**: Optional  
  - Needed for downloading models/runtimes and app updates

## Quick start

1. **Download and install**  
   Run the Windows installer:  
   https://pub-277c819c500843e1b195cb5fa8d0a929.r2.dev/apps/builds/win/InferenceDesk-1.0.0-Setup.exe

2. **Open InferenceDesk**  
   Sign in or continue as guest.

3. **Choose a model**  
   Click **Choose model**, select a model (or open **Models** in the sidebar to add one), and wait until it shows:  
   **Model: \<name\>**

4. **Chat**  
   Type in the message box and click **Send**.

For more detail, see:
- [Getting started](docs/how-to/how-to-get-started.md)
- [User guides](docs/README.md)

## Documentation

- **[User guides](docs/README.md)** — Getting started, running a model, chat, models, downloads, settings, Knowledge, and updates
- **[For developers](docs/plugins-spec.md)** — Plugin specification  
- **[Runtime publishing](docs/runtime-publishing.md)** — How to publish runtimes

## Support / Feedback

- Email: **localmind1234@gmail.com**
- Issues: Use GitHub Issues in this repo (recommended for bugs and feature requests)

When reporting bugs, include:
- InferenceDesk version
- Windows version
- GPU type (if any)
- Steps to reproduce + logs/screenshots if available

## Legal

- [Terms of Service](./TERMS.md)
- [Privacy Policy](./PRIVACY.md)
