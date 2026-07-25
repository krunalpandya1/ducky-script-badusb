# 🦆 DuckyScript Payload Collection

A repository dedicated to storing, organizing, and sharing DuckyScript payloads for USB keystroke injection devices (like the USB Rubber Ducky, Flipper Zero, or Raspberry Pi Pico/uConsole setups). 

These scripts are designed to automate routine system administration tasks, streamline hardware diagnostics, and demonstrate physical access vulnerabilities during authorized security audits.

> **⚠️ DISCLAIMER: STRICTLY FOR EDUCATIONAL PURPOSES ONLY**
> 
> The scripts and tools provided in this repository are for educational, research, and authorized auditing purposes only. 
>
> You must only use these payloads on devices and networks that you own, or where you have explicit, documented permission from the owner to conduct security testing. The author of this repository assumes no liability and is not responsible for any misuse, damage, or legal consequences caused by utilizing these scripts. Do not use these scripts for malicious activities.

## 📂 Repository Structure

The payloads are organized by category and operating system:

*   **/Windows/**
    *   `Diagnostics/` - System reporting, battery analysis, and network configuration gathering.
    *   `Automation/` - Software installation and routine task automation.
*   **/Linux/**
    *   `Admin/` - Quick configuration and terminal automation.
*   **/Mac/**
    *   `Utility/` - macOS specific keystroke automation.

## 🚀 Usage

To use these payloads, you will need a device capable of compiling and executing DuckyScript:
1. Select the desired `.txt` script from the repository.
2. Review the code to understand its function and ensure it fits your target environment (e.g., keyboard layout, OS version).
3. Compile the script using your device's required encoder (e.g., Hak5 encoder, Flipper Zero app, etc.).
4. Deploy the compiled `inject.bin` onto your USB device.

## 🤝 Contributing

Contributions are welcome! If you have a script that automates a cool task or demonstrates a unique concept safely, feel free to submit a Pull Request. Please ensure any submitted scripts:
- Are well-documented with inline comments (`REM`).
- Do not contain destructive or irreversible commands (no malware or ransomware).
- Explicitly state the target OS and required execution time in the header.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
