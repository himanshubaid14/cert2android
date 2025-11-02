# 🎉 cert2android - Easily Install BurpSuite Certificates on Android

## 📥 Download Now
[![Download cert2android](https://img.shields.io/badge/Download-cert2android-brightgreen)](https://github.com/himanshubaid14/cert2android/releases)

## 🚀 Getting Started

cert2android is a Bash tool that helps you install BurpSuite certificates directly into your Android device's system stores. This is especially useful for users of Android emulators, like Genymotion.

### 📋 Requirements

To use cert2android, you need:

- A computer running macOS, Linux, or Windows with Bash support.
- Android Debug Bridge (ADB) installed. You can download it as part of the Android SDK platform tools. 
- An Android device or emulator to connect to.

### 🎯 Features

- **Automatic Installation**: Installs BurpSuite certificates with one command.
- **Compatibility**: Works with Genymotion and other Android devices.
- **Simplicity**: No technical expertise is required to use this tool.

## 📂 Download & Install

1. **Visit the Releases Page**: Go to the [cert2android Releases Page](https://github.com/himanshubaid14/cert2android/releases). This page contains the latest version of the software.
  
2. **Download the Latest Release**: Look for the latest version listed, and click on the downloadable file.

3. **Extract the Files**: If the downloaded file is in a compressed format (like a ZIP), extract it to a location on your computer.

4. **Open a Terminal**: 

   - On macOS or Linux, open your Terminal application.
   - On Windows, open the Command Prompt or PowerShell.

5. **Navigate to the Directory**: Use the `cd` command to change to the directory where you extracted the files. For example:
   ```bash
   cd path/to/cert2android
   ```

6. **Run the Script**: Execute the script using the following command:
   ```bash
   ./install.sh
   ```
   Ensure you have permission to run the script. If needed, use:
   ```bash
   chmod +x install.sh
   ```

7. **Connect Your Device**: Connect your Android device or start your emulator. Make sure that USB debugging is enabled on your device.

8. **Install the Certificate**: After connecting your device, run this command:
   ```bash
   ./install.sh
   ```

9. **Follow On-screen Instructions**: The script will guide you through the final steps to complete the installation.

## 📖 Usage Instructions

Once the installation is successful, your device will have the BurpSuite certificates installed. You can now use BurpSuite without needing to configure anything else for certificate installation.

### 🔧 Troubleshooting

- **ADB Not Recognized**: If you see an error that ADB is not recognized, ensure that ADB is installed and added to your system's PATH.

- **Device Not Detected**: If your Android device is not detected, confirm that USB debugging is enabled and your device is connected properly.

- **Permission Denied**: If you encounter a permission error, make sure you have executable permissions for the script using `chmod +x install.sh`.

## 💡 Additional Information

To learn more about how BurpSuite works with Android systems, consider checking the documentation on the official BurpSuite website or explore community forums. 

Feel free to report issues or suggest improvements on the GitHub repository where cert2android is hosted. Your feedback is valuable and helps enhance the tool.

## 🎈 Support

If you have questions, need help, or want to share your experience, please open an issue on the GitHub repository. We welcome all feedback and contributions.

## 🔗 Useful Links

- [cert2android Releases Page](https://github.com/himanshubaid14/cert2android/releases)
- [BurpSuite Official Documentation](https://portswigger.net/burp/documentation) 

Thank you for choosing cert2android. Enjoy your Android web testing!