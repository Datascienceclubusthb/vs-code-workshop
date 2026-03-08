# vs-code-workshop
A complete guide for setting up VS Code with essential extensions and settings for the workshop.

# 🚀 VS Code Setup Workshop
Welcome to the workshop! This guide will help you configure **VS Code** with the best extensions and settings for a professional development workflow.

## 📦 Required Extensions
Search for and install these in the VS Code Marketplace:

### General & Frontend
* **Prettier - Code formatter**: The industry standard for clean, consistent code.
* **One Monokai**: A sleek, high-contrast color theme.
* **Material Icon Theme**: Beautiful icons for your files and folders.
* **Image Preview**: Shows image thumbnails in the sidebar.
* **Color Highlight**: Highlights web colors (HEX/RGB) in real-time.
* **Auto Rename Tag**: Automatically renames paired HTML tags.
* **Live Server**: Launch a local development server with live reload.

### Data Science & Python
* **Python**: Essential for running scripts and debugging.
* **Jupyter**: Allows you to open and run `.ipynb` files directly inside VS Code.

---

## ⚙️ Essential Settings
Access settings via `File > Preferences > Settings` (`Ctrl + ,`).

| Setting | Value / Action |
| :--- | :--- |
| **Default Formatter** | Select `Prettier - Code formatter` |
| **Format On Save** | **Enable** (Check the box) |
| **Auto Save** | Set to `onFocusChange` |
| **Tab Size** | Set to `2` |
| **Auto Close Tag** | Ensure it is **Enabled** |

---

## 🎨 Look & Feel
To apply your themes, press `Ctrl + Shift + P` and type:
1. **Color Theme**: Select `One Monokai`.
2. **File Icon Theme**: Select `Material Icon Theme`.

---

## ⚡ Productivity Shortcuts (Master the Keyboard)
* **Duplicate a Line**: `Shift + Alt + Down Arrow` (or Up Arrow).
* **Move (Displace) a Line**: `Alt + Up/Down Arrow`.
* **Split Window**: `Ctrl + \` (Great for comparing code side-by-side).

---

## ⚛️ Next.js Pro Tip: Custom Labels
When working with **Next.js**, multiple `page.js` tabs can be confusing. Let's fix that:
1. Search for **"Custom Labels"** in Settings.
2. Enable **Workbench > Editor > Custom Labels**.
3. Click **"Add Item"** and enter:
   - **Pattern**: `**/app/**/page.js`
   - **Value**: `Page: ${dirname}`
