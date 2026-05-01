# 👤 git-account-manager - Manage multiple Git profiles with ease

[![](https://img.shields.io/badge/Download-Git_Account_Manager-blue.svg)](https://github.com/mrlabmate/git-account-manager/releases)

git-account-manager helps you maintain separate identities for your work, personal, and hobby projects. Many developers rely on Git to track their code, but swapping between private and work accounts often requires manual configuration. This tool automates the process and removes the need for command-line tweaks.

## 🛠 Why use this tool

Managing Git accounts manually creates friction. You might accidentally push a work project from your personal email or use the wrong SSH key for a repository. This application solves those issues by centralizing your settings. You save time and reduce errors by selecting your active profile before you start coding.

## ⚙️ Key features

- Switch identities in one click.
- Automate updates to your Git configuration file.
- Manage multiple SSH keys for different platforms like GitHub or GitLab.
- Organize accounts into groups.
- View your current active identity on your dashboard.
- Update global settings without typing commands.

## 📥 Getting the software

You need a Windows computer to run this application. Follow these instructions to set up the software.

1. Visit the [official releases page](https://github.com/mrlabmate/git-account-manager/releases) to access the download options.
2. Look for the file ending in `.exe` under the latest release section.
3. Click the file name to start your download.
4. Open your Downloads folder once the file finishes saving to your computer.
5. Double-click the file to launch the installer.
6. Follow the prompts on your screen to complete the installation.

## 🚀 Setting up your first profile

Launch the application using the shortcut on your desktop. The first time you open the tool, you define your primary profile.

1. Click the Add Account button.
2. Enter a name for the account, such as "Work" or "Personal".
3. Provide your name and the email address associated with your Git provider.
4. Select the location of your SSH key file if you use one.
5. Save the profile.

You now see your profile in the main list. Click the radio button next to any profile to make it the active identity. The application updates your Git settings immediately.

## 🔑 Handling SSH keys

SSH keys allow you to connect to services like GitHub without typing your password each time. git-account-manager organizes these keys for you.

When you create an account profile, the app asks for the path to your private key. You create these keys through your Git service documentation. Once you generate a key, keep the file in a secure folder. Point the application to this folder during the profile setup. The software copies the correct key to your system folder whenever you switch accounts.

## 📝 Managing repositories

The application tracks the repositories you link to specific profiles. You can assign a folder on your computer to a specific account. When you enter that folder to work, the app detects the change and prompts you to switch your identity if it does not match. This prevents you from pushing code to the wrong place.

## ❓ Frequently asked questions

**Does this app track my passwords?**
No. The application handles identity and SSH keys. It does not store or process your account passwords.

**Can I run this on other operating systems?**
This version supports Windows systems. Future updates will include support for macOS and Linux.

**What happens if I change my email on GitHub?**
Update the email address in your profile settings within the app. Click save to apply the changes to your local Git configuration.

**Do I need to restart my terminal after switching profiles?**
The software updates your configuration file directly. Changes appear in new terminal windows you open after the switch.

## 📋 System requirements

- Windows 10 or Windows 11.
- Git installed on your computer.
- Basic write access to the folder where you keep your code.
- 50 MB of free disk space.

## 🛡 Security considerations

Store your private SSH keys in a folder that only your user account can access. Do not share your private key files with anyone. The software keeps your information local to your machine. It does not send your data to external servers. Your Git profiles remain on your hard drive, which keeps your configuration secure and private.

## 💡 Support and feedback

This project grows through user feedback. If you find a bug or think of a feature that helps you work faster, submit an issue on the GitHub repository. Provide a description of what you saw and what you expected to happen. Keep your descriptions clear so others can reproduce the problem. Thank you for using the tool to manage your identities.