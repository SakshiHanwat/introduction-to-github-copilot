# Set Up, Configure, and Troubleshoot GitHub Copilot ⚙️🤖

This unit explains how to sign up for GitHub Copilot, configure it using Visual Studio Code (VS Code), and troubleshoot common issues.

GitHub Copilot works as an extension inside your development environment and can be customized according to your workflow.

---

## Sign Up for GitHub Copilot

Before using GitHub Copilot, you must enable it for your GitHub account.

### Steps to Sign Up

1. Open **GitHub.com**
2. Click on your **profile photo**
3. Select **Settings**
4. In the left menu, find **Copilot** under  
   *Code, planning, and automation*
5. Choose a **Free trial** or **subscription plan**

After signing up, GitHub Copilot becomes available for your account.

---

## Supported Environments

GitHub Copilot supports multiple platforms:

- GitHub.com (no extension required)
- Visual Studio Code (VS Code)
- Visual Studio
- JetBrains IDEs
- Neovim

📌 In this module, the focus is on **Visual Studio Code**, which is also used in the next exercise.

---

## Configure GitHub Copilot in VS Code

### Install GitHub Copilot Extension

1. Open **Visual Studio Code**
2. Go to **Visual Studio Marketplace**
3. Search for **GitHub Copilot**
4. Select **Install**
5. When prompted, select **Open VS Code**
6. On the extension page, click **Install**

If VS Code is not authorized with GitHub:
- Select **Sign in to GitHub**
- Complete the sign-in process in the browser

After installation, GitHub Copilot starts suggesting code automatically.

---

## Enable or Disable GitHub Copilot in VS Code

GitHub Copilot can be enabled or disabled directly from the VS Code status bar.

### Steps

1. Look at the **bottom-right status bar** in VS Code
2. Click on the **GitHub Copilot icon**
3. Select:
   - **Enable**
   - **Disable**

When disabling, VS Code gives two options:

- **Disable completions globally**
- **Disable completions for a specific language**

This flexibility allows you to control Copilot behavior per language.

---

## Enable or Disable Inline Suggestions

Inline suggestions can be customized in VS Code settings.

### Steps

1. Open **File > Preferences > Settings**
2. Select **Extensions**
3. Choose **GitHub Copilot**
4. Find **Editor: Enable Auto Completions**
5. Check or uncheck the box to enable or disable inline suggestions

You can also:
- Enable or disable Copilot for specific programming languages
- Customize how Copilot behaves inside the editor

---

## Troubleshoot GitHub Copilot in VS Code

If GitHub Copilot is not working correctly, log files can help diagnose issues.

### View Copilot Log Files

1. Open **Command Palette**
   - Mac: `Shift + Command + P`
   - Windows/Linux: `Ctrl + Shift + P`
2. Enter:
   - **Developer: Open Log File**
   - or **Developer: Open Extensions Logs Folder**

These logs help identify connection or extension-related issues.

---

## View Electron Logs (Advanced)

In rare cases, errors may not appear in standard logs.

To view Electron logs:
1. Open **VS Code**
2. Select **Help**
3. Choose **Toggle Developer Tools**

This allows deeper inspection of extension and process-level errors.

---

## Collect Diagnostics Information

Network restrictions, firewalls, or proxy settings can interfere with GitHub Copilot.

To collect diagnostic information:

1. Open **Command Palette**
2. Enter **Diagnostics**
3. Select **GitHub Copilot: Collect Diagnostics**

This opens a new editor containing diagnostic details that can be:
- Reviewed by you
- Shared with GitHub support if needed

---

## Key Takeaway

GitHub Copilot is easy to set up and highly configurable.

- Proper setup ensures smooth functionality
- VS Code settings allow fine-grained control
- Logs and diagnostics help resolve issues quickly

Understanding setup and troubleshooting ensures uninterrupted productivity when using GitHub Copilot.
