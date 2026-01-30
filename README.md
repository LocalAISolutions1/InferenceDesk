# InferenceDesk

InferenceDesk is a **Windows desktop app** by **Local AI Solutions** for running local, on-device inference with llama-compatible open-source models (CPU or GPU).

> **Beta release**
>
> InferenceDesk is currently in **beta** and I’m actively looking for feedback.  
> If you run into issues or have ideas, please email me at **localmind1234@gmail.com**.

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

## Why InferenceDesk

- **Local-first**: Run models on your machine.
- **Model flexibility**: Use llama-compatible open-source models.
- **Simple workflow**: Install → pick a model → chat.
- **Knowledge support**: Add documents as context for chats.

## Features

- Run llama-compatible open-source models locally (CPU and GPU)
- Chat interface: multiple conversations; choose and switch models
- Models page: browse, add, pin, and delete models; configure parameters
- Download models and runtimes from inside the app
- **Knowledge**: upload documents (CSV, TXT, MD, PDF) and use them as context in chat
- Settings: General, System (hardware), Engines (runtimes), Models hub, Account
- In-app updates (check and install from **Settings → General**)

## Requirements

- **OS**: Windows 10 or 11
- **Hardware**: Sufficient RAM and disk space for the app and your models  
  - Optional GPU acceleration (NVIDIA CUDA, AMD ROCm, or Vulkan) for faster inference
- **Network**: Optional  
  - Required only for downloading models/runtimes and app updates

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

## Support

If you hit a bug or have a feature request, please open an issue in this repo.

For beta feedback, you can also email: **localmind1234@gmail.com**

When reporting bugs, include:
- InferenceDesk version
- Windows version
- GPU type (if any)
- Steps to reproduce + logs/screenshots if available

## Security & privacy notes

InferenceDesk is designed for **local inference**. Network access is only needed for:
- downloading models/runtimes
- checking/installing updates

Refer to the Privacy Policy for details: [PRIVACY.md](./PRIVACY.md)

## Legal

- [Terms of Service](./TERMS.md)
- [Privacy Policy](./PRIVACY.md)
