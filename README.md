# AI-Studio

AI-Studio is a local offline AI model runner app for Android devices. It enables anyone to run advanced AI models directly on their device, fully offline, without any internet connection. The app intelligently detects your device's RAM, CPU, and storage to select and run the most suitable model for your hardware.

## Features

- **Fully Offline**: All AI models run locally on your Android device—no internet required after setup.
- **Device-Aware**: Automatically selects the best model size based on your device's RAM, CPU, and storage.
- **Supports .task LLM Files**: Run local Large Language Models (LLMs) in the .task format for text generation and more.
- **Easy Model Management**: Download models directly from Hugging Face within the app, or import models from your local storage.
- **User-Friendly Interface**: Simple UI for browsing, downloading, importing, and running models.
- **Privacy First**: Your data never leaves your device.

## Download

- **[Download the latest AI-Studio APK](https://github.com/your-repo/AI-Studio/releases/latest)**

## Getting Started

### Prerequisites
- Android device (recommended: Android 10 or higher)
- Sufficient storage and RAM for running AI models (requirements depend on model size)

### Installation
1. Download the latest APK from the [Releases](https://github.com/mojahid2021/AI-Studio/releases/download/1.0.3/ai-studio.apk) section.
2. Transfer the APK to your Android device if downloaded on another device.
3. Open the APK file and follow the prompts to install. You may need to enable installation from unknown sources in your device settings.

### Usage
1. Launch the AI-Studio app on your device.
2. Download a model directly from Hugging Face using the in-app browser, or import a local .task LLM file from your device storage.
3. The app will automatically select the optimal model size for your device based on available resources.
4. Once downloaded or imported, you can use the model locally without any internet connection.
5. Interact with the model for text generation and other supported tasks.

## Model Support
- **Supported Model Format**: .task LLM files
- **Model Sources**:
  - Download from Hugging Face directly in the app
  - Import from local storage

## Model Management
- Add new models by downloading from Hugging Face or placing them in the `/AI-Studio/models/` directory on your device.
- The app will scan and list all compatible .task models automatically.

## Troubleshooting
- **App crashes or slow performance**: Try using a smaller model or close other apps to free up memory.
- **Model not detected**: Ensure the model file is in the correct directory and is in .task format.

## FAQ

**Q: Does AI-Studio require an internet connection?**
A: No, all processing is done locally on your device. Internet is only needed for downloading models (if not importing locally).

**Q: Can I use my own models?**
A: Yes, you can import compatible .task LLM files from your device storage.

**Q: What is the maximum model size supported?**
A: This depends on your device's RAM and storage. The app will guide you if a model is too large.

**Q: Where can I get models?**
A: Download models from Hugging Face directly in the app, or import .task files from your local storage.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for bug fixes, new features, or documentation improvements.

## License
This project is licensed under the MIT License.

---

For more information, support, or to report issues, please contact the project maintainer.
