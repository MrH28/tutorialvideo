# Getting Started: GitHub, Python & VS Code — Setup Guide for Agronomy Students

Welcome! This guide will walk you through everything you need to get started with GitHub and Visual Studio Code (VS Code) — the tools you will use throughout this course. No prior experience is required.

By the end of this guide you will have:
- A GitHub account with a free **Education license** (which gives you access to GitHub Copilot)
- **Python** installed and ready to run
- **VS Code** installed with all essential extensions
- A working project environment to start coding

Estimated time: **30–40 minutes**

---

## Table of Contents

1. [Creating a GitHub Account](#1-creating-a-github-account)
2. [Getting the GitHub Education License](#2-getting-the-github-education-license)
3. [Acceptable Documents for Student Verification](#3-acceptable-documents-for-student-verification)
4. [Installing Python on Windows](#4-installing-python-on-windows)
5. [Installing Visual Studio Code on Windows](#5-installing-visual-studio-code-on-windows)
6. [Setting Up Your Working Environment](#6-setting-up-your-working-environment)
7. [Installing VS Code Extensions](#7-installing-vs-code-extensions)
8. [Activating GitHub Copilot in VS Code](#8-activating-github-copilot-in-vs-code)
9. [Quick-Start: Daily Workflow](#9-quick-start-daily-workflow)

---

## 1. Creating a GitHub Account

GitHub is a platform for storing, sharing, and collaborating on code. You will need a free account to access course materials and to apply for student benefits.

> **Tip:** Use a **personal email address** (e.g., Gmail) as your primary GitHub email — not your university email. University emails often stop working after graduation. You will add your university email later, only for student verification.

### Steps

1. Open your browser and go to [https://github.com](https://github.com).
2. Click **Sign up** in the top-right corner.
3. Enter your **personal email address**.
4. Create a **strong password** (at least 15 characters, or 8+ characters mixing letters, numbers, and symbols).
5. Choose a **username**.

   > **Tip:** Pick something professional — your username appears on your public profile and in links to your work (e.g., `github.com/your-username`).

6. Select your **country/region**.
7. Complete the **puzzle verification** (CAPTCHA).
8. Click **Create account**.
9. GitHub will send a **verification email** to the address you provided. Open it and click the confirmation link.

> 📸 **Screenshot:** The GitHub sign-up form with all fields filled in.

> <img width="1920" height="901" alt="02_signup" src="https://github.com/user-attachments/assets/fd83829f-2a69-4171-808a-2ade357c4354" />



> 📸 **Screenshot:** The email verification screen after account creation.

> <img width="1400" height="648" alt="email confirmation" src="https://github.com/user-attachments/assets/afbaccbf-d329-4ec4-beca-218b787da8e8" />


You now have a GitHub account. Keep it open — you will need it in the next section.

---

## 2. Getting the GitHub Education License

The **GitHub Student Developer Pack** gives students free access to professional developer tools, including:

- **GitHub Copilot** — an AI assistant that helps you write and understand code directly inside VS Code
- Cloud hosting credits (Azure, Heroku, and more)
- Domain names, security tools, learning platforms, and more

All of these are **free while you are an enrolled student**.

### Steps

1. Make sure you are **logged in** to your GitHub account.
2. Go to [https://education.github.com/pack](https://education.github.com/pack).
3. Click **Get student benefits**.
4. Click **Get student benefits** again or **Start application** if prompted.

> 📸 **Screenshot:** The GitHub Education benefits page with the "Get student benefits" button highlighted.

> <img width="1920" height="901" alt="07_after_manual_form" src="https://github.com/user-attachments/assets/a91a26bb-fbf2-4f71-8621-4ca3d2b60f69" />


5. Under **What best describes your academic status?**, select **Student**.
6. In the **School name** field, search for and select your university or institution.
7. Enter your **university email address** (the one ending in your school's domain, e.g., `name@usp.br`).

   > **Note:** If your institution does not provide email addresses, you can still apply using a document as proof (see [Section 3](#3-acceptable-documents-for-student-verification)).

8. Select your **proof type** — for most students, **Dated school ID** works best.
9. **Upload your proof document** (see Section 3 for accepted formats).
10. Enter the **address associated with your institution**.
11. Click **Submit your information**.

> 📸 **Screenshot:** The application form showing the role selector set to "Student" and the school name field.

> <img width="1920" height="901" alt="08_after_submit" src="https://github.com/user-attachments/assets/43ba5ec3-4185-4e37-ba7a-b7ea15b5c682" />


### Enabling Two-Factor Authentication (2FA)

GitHub requires **2FA** to be enabled before your application can be approved. This adds a second layer of security to your login.

1. Go to **Settings** (click your profile picture → **Settings**).
2. In the left sidebar, click **Password and authentication**.
3. Under **Two-factor authentication**, click **Enable two-factor authentication**.
4. Follow the on-screen instructions. The easiest option is to use an **authenticator app** on your phone (e.g., Google Authenticator or Microsoft Authenticator).

> 📸 **Screenshot:** The GitHub Security settings page with the 2FA section highlighted.

> <img width="1920" height="901" alt="09_security_2fa" src="https://github.com/user-attachments/assets/e46122c5-d353-4c6e-ab7f-ee15e988982e" />
> <img width="1920" height="901" alt="10_after_2fa" src="https://github.com/user-attachments/assets/eb04438c-1749-429c-8fac-aa7320aeac54" />





### After Submission

- GitHub will review your application. **Approval can take a few hours to a few days**.
- You will receive a **confirmation email** when approved.
- If rejected, GitHub will explain why and let you resubmit with a different document.

### Confirming Copilot Is Active

Once your Student Developer Pack is approved:

1. Go to **Settings** → **Copilot**.
2. Copilot should be listed as enabled under your student benefits.

> 📸 **Screenshot:** The GitHub Copilot settings page showing it is enabled under the student plan.

> <img width="1952" height="1112" alt="copilot-settings" src="https://github.com/user-attachments/assets/66949f1f-d0c7-4d92-961f-c5db305602df" />
> <img width="1917" height="954" alt="Github + copilot setting" src="https://github.com/user-attachments/assets/b2c8d420-d524-48ba-bda7-d28e39b54a83" />


---

## 3. Acceptable Documents for Student Verification

GitHub requires proof that you are a **currently enrolled student**. Below are the most commonly accepted documents.

### Accepted Documents

| Document | What It Must Show |
|---|---|
| **Dated school/university ID card** *(most common)* | Your name, institution name, and current academic year or expiry date |
| **Official enrollment letter** | Issued by your institution, dated within the current semester |
| **Transcript or grade report** | Your name, institution, and current enrollment status |
| **Tuition payment receipt** | Dated, showing the current semester |
| **Official class schedule** | From your institution's student portal, showing the current term |

### Tips for a Successful Submission

> - The document must be **clearly legible** — no blurry photos or cropped edges.
> - It must show your **full name** and the **institution's name**.
> - It must be **dated within the past year** or show a valid expiry date.
> - Accepted file formats: **PDF, PNG, JPG**.
> - Do **not** upload a general government ID (e.g., national ID or passport) — it must be enrollment-related.
> - If your school ID does not show a date, pair it with an official enrollment letter.

---

## 4. Installing Python on Windows

Python is the programming language you will use in this course. You need to install it before setting up VS Code.

### Option A — Using `winget` (Recommended for Windows 10/11)

`winget` is a built-in Windows package manager. Open **PowerShell** or **Command Prompt** (search for either in the Start menu), paste the command below, and press **Enter**:

```powershell
winget install --id Python.Python.3.12 -e
```

Wait for the installation to finish, then **close and reopen your terminal**.

### Option B — Manual Download

If `winget` is not available:

1. Go to [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/).
2. Click the latest **Python 3.12.x** installer for Windows.
3. Run the downloaded `.exe` file.
4. On the first screen, check **"Add Python to PATH"** before clicking Install.

> **Important:** If you skip the "Add Python to PATH" checkbox, Python will not be recognized in the terminal.

> 📸 **Screenshot:** The Python installer with the "Add Python to PATH" checkbox highlighted.

> <img width="862" height="744" alt="add python to path" src="https://github.com/user-attachments/assets/ea271845-665b-44f3-b807-cd552c545d96" />



### Verifying the Installation

Open **PowerShell** or **Command Prompt** and run:

```powershell
python --version
```

You should see something like:

```
Python 3.12.x
```

> **Troubleshooting:** If you see `'python' is not recognized`, close and reopen your terminal. If it still fails, reinstall Python and make sure **"Add Python to PATH"** is checked.

---

## 5. Installing Visual Studio Code on Windows

Visual Studio Code (VS Code) is a free code editor. It is where you will write code, run notebooks, and use the Copilot AI assistant.

### Option A — Using `winget` (Recommended)

Open **PowerShell** or **Command Prompt** and run:

```powershell
winget install --id Microsoft.VisualStudioCode -e --source winget
```

Wait for the installation to finish.

### Option B — Manual Download

1. Go to [https://code.visualstudio.com](https://code.visualstudio.com).
2. Click **Download for Windows**.
3. Run the downloaded `.exe` file.
4. During installation, check these two options:
   - **Add to PATH** (required — this lets you open VS Code from the terminal)
   - **Add "Open with Code" action to Windows Explorer context menu** (optional but convenient)

> 📸 **Screenshot:** The VS Code installer with the "Add to PATH" checkbox highlighted.

> <img width="1501" height="558" alt="new vs code add to path" src="https://github.com/user-attachments/assets/c483f686-b32c-46e4-adc5-26144d39f87c" />



### Verifying the Installation

Open **PowerShell** or **Command Prompt** and run:

```powershell
code --version
```

You should see a version number printed, for example:

```
1.89.1
```

> **Troubleshooting:** If `code` is not recognized, close and reopen your terminal. If it still fails, reinstall VS Code and make sure **"Add to PATH"** is checked.

---

## 6. Setting Up Your Working Environment

A **virtual environment** is an isolated Python workspace for your project — think of it as a separate toolbox that keeps each project's packages organized and independent from everything else on your computer. This is the standard practice in professional Python development.

### Steps

1. Create a folder for your course projects. For example, in **PowerShell**:

   ```powershell
   mkdir C:\Users\YourName\projects\agronomy
   ```

   Replace `YourName` with your actual Windows username.

2. Open VS Code and go to **File → Open Folder**, then select the folder you just created.

3. Open the integrated terminal inside VS Code with **Ctrl+`** (backtick), then create a virtual environment:

   ```powershell
   python -m venv .venv
   ```

4. Activate the virtual environment:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

   When active, you will see `(.venv)` appear at the beginning of your terminal prompt.

   > **Troubleshooting:** If you get a permissions error, run this command first, then try activating again:
   > ```powershell
   > Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
   > ```

5. Install the core scientific packages you will use in this course:

   ```powershell
   python -m pip install --upgrade pip
   pip install numpy pandas matplotlib ipykernel jupyter
   ```

   This may take a few minutes. You will see a list of packages being downloaded and installed.

> 📸 **Screenshot:** The VS Code terminal with `(.venv)` visible in the prompt after activation.

> <img width="1034" height="593" alt="Vscode +  venv" src="https://github.com/user-attachments/assets/e0fc4d26-b646-4edb-9385-9111c4961096" />


---

## 7. Installing VS Code Extensions

Extensions add features to VS Code — Python support, Jupyter notebook integration, and AI-powered assistance. Install all of the extensions below before starting the course.

### How to Install — Option A (Graphical)

1. Open VS Code.
2. Click the **Extensions** icon in the left sidebar, or press **Ctrl+Shift+X**.
3. In the search bar, type the extension name.
4. Click the **Install** button next to the correct result.

> 📸 **Screenshot:** The VS Code Extensions panel with the search bar and an Install button visible.

> <img width="1008" height="404" alt="Github + extensions" src="https://github.com/user-attachments/assets/23b71ba3-f151-49d7-8015-f4f58864c549" />


### How to Install — Option B (Bulk Install via Terminal)

Open VS Code's integrated terminal (**Ctrl+`**) and paste all the commands below at once:

```powershell
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance
code --install-extension ms-toolsai.jupyter
code --install-extension ms-python.debugpy
code --install-extension ms-python.black-formatter
code --install-extension ms-python.isort
code --install-extension GitHub.copilot
code --install-extension GitHub.copilot-chat
```

### Extensions Overview

| Extension | Extension ID | What It Does |
|---|---|---|
| **Python** | `ms-python.python` | Core support for running Python files |
| **Pylance** | `ms-python.vscode-pylance` | Fast autocomplete and type hints for Python |
| **Jupyter** | `ms-toolsai.jupyter` | Open and run `.ipynb` notebook files in VS Code |
| **Python Debugger** | `ms-python.debugpy` | Set breakpoints and step through code line by line |
| **Black Formatter** | `ms-python.black-formatter` | Automatically formats your Python code when you save |
| **isort** | `ms-python.isort` | Keeps `import` statements organized automatically |
| **GitHub Copilot** | `GitHub.copilot` | AI-powered code completions as you type |
| **GitHub Copilot Chat** | `GitHub.copilot-chat` | Ask Copilot questions and get explanations in a chat panel |

> **Note:** The two Copilot extensions work together — install both. They will only activate after your **Student Developer Pack** is approved (see [Section 2](#2-getting-the-github-education-license)).

### Verify All Extensions Are Installed

1. Press **Ctrl+Shift+X** to open the Extensions panel.
2. Click the **Installed** filter at the top.
3. Confirm you can see all eight extensions listed above.

---

## 8. Activating GitHub Copilot in VS Code

> **Important:** You must sign in to VS Code using the **exact same GitHub account** that has the active Education license. If you sign in with a different account, Copilot will not activate.

### Steps

1. In VS Code, click the **Accounts** icon at the bottom-left of the sidebar (it looks like a person silhouette).
2. Click **Sign in with GitHub to use GitHub Copilot**.
3. A browser window will open asking you to authorize VS Code.

   > **Check:** Before clicking Authorize, confirm that the GitHub account shown in the browser is the one with your active Education license. If it is not, log out of GitHub in your browser first and log in with the correct account.

4. Click **Authorize Visual Studio Code**.
5. Return to VS Code — Copilot is now active.

> 📸 **Screenshot:** The VS Code Accounts menu with the "Sign in with GitHub" option highlighted.
> 

### Using Copilot Chat

1. Open the Copilot Chat panel with **Ctrl+Alt+I**, or click the chat icon in the left sidebar.
2. Type your question in the chat box and press **Enter**.

**Example questions you can ask Copilot Chat:**
- *"What does this function do?"*
- *"Why is my code giving a KeyError?"*
- *"Write a function that reads a CSV file and calculates the average yield per hectare."*

> **Tip:** The more context you give Copilot (open files, selected code), the better its suggestions. You can highlight a block of code and ask Copilot to explain or improve it.

> 📸 **Screenshot:** The VS Code Copilot Chat panel open on the right side, showing a conversation.

> <img width="1608" height="510" alt="github + chat framework" src="https://github.com/user-attachments/assets/2bf797e7-648c-422c-b0c8-f5f1727353f4" />

---

## 9. Quick-Start: Daily Workflow

Once everything is set up, here is how to open and use your environment each day:

1. Open VS Code → **File → Open Folder** → navigate to your course folder.
2. Open the integrated terminal with **Ctrl+`**.
3. Activate your virtual environment:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

   You should see `(.venv)` in the terminal prompt.

4. Open or create a `.ipynb` notebook file from the **Explorer** panel on the left.
5. Click **Select Kernel** (top-right of the notebook) and choose the `.venv` Python environment.

   > **Tip:** If VS Code does not show `.venv` as an option, press **Ctrl+Shift+P**, type `Python: Select Interpreter`, and choose the interpreter inside your `.venv` folder.

6. Run a notebook cell with **Ctrl+Enter** (stays on the same cell) or **Shift+Enter** (runs and moves to the next cell).

> **Tip:** If you see Copilot suggestions appear as grey text while typing, press **Tab** to accept them.

---

*Guide maintained by the course team. If you run into issues not covered here, ask your instructor or open a discussion in the course repository.*
