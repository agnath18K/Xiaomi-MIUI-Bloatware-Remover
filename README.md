# Xiaomi MIUI Bloatware Remover

The Xiaomi MIUI Bloatware Remover is a handy tool designed to help you disable or remove unwanted apps from Xiaomi devices running the MIUI (Xiaomi's custom Android skin) operating system. If you're looking to clean up your device by getting rid of pre-installed or unwanted applications, this tool simplifies the process for you.

## Prerequisites

Before using the Xiaomi MIUI Bloatware Remover, make sure you have the following prerequisites in place:

1. **Xiaomi Device**: You should own a Xiaomi device with the MIUI operating system.

2. **USB Debugging Enabled**: Ensure that USB debugging is enabled on your device. You can do this by going to your device's Developer Options and enabling USB debugging.

3. **ADB (Android Debug Bridge)**: You should have ADB installed on your computer. You can install ADB platform tools to your computer if it's not already installed. A quick online search will guide you on how to do this.

## Usage

Follow these simple steps to remove or disable unwanted apps from your Xiaomi device using the Xiaomi MIUI Bloatware Remover:

1. **Connect Your Device**: Connect your Xiaomi device to your computer via USB cable, making sure that USB debugging is enabled.

2. **Download the Script**: Download the Xiaomi MIUI Bloatware Remover script to your computer.

3. **Run the Script**: Run the script, press any key to start the process. (./script.sh)

4. **Customization (Optional)**: If there are specific apps you want to keep, you can remove their package names from the script file before running it. This allows you to retain the apps you want while removing the ones you don't.

5. **Enabling Apps (Optional)**: If you accidentally remove an app you want to keep or need to enable a package again, you can do so using the following methods:
    - Run the shell command: `adb shell pm enable <package name>`
    - Enable it from the device's app settings.

6. **Uninstalling Packages (Advanced)**: If you want to completely uninstall packages, you can use the command: `adb shell pm uninstall <package_name>`. Be cautious when using this command, as it will permanently remove the app.

## Important Note

- Make sure you use this tool with caution. Removing or disabling system apps can potentially affect the stability and functionality of your device.

- It's recommended to create a backup of your device or important data before using this tool, in case something goes wrong.

- This tool is intended for advanced users who understand the implications of removing or disabling apps on their Xiaomi device.

- The script provided assumes you have ADB installed or run the script alongside ADB platform tools.

By following these steps and keeping these important notes in mind, you can efficiently manage and optimize your Xiaomi device by removing unwanted bloatware and freeing up storage space.
