# NOVA on Windows - Simple Setup Guide

A step-by-step guide for anyone. No coding needed. Takes about 10 minutes
(plus the model download).

---

## What is NOVA?

NOVA is an AI assistant that runs **fully on your own computer**. It works
**offline** - nothing is sent to the internet, and nothing leaves your PC.

---

## What you need

- A **Windows 10 or Windows 11** laptop/PC
- About **5 GB free space** (for the app + the AI model)
- Internet **only for the first setup** (to download the model). After that it
  works offline.

---

## Step 1 - Download

Click this link and download the file (about 54 MB):

**https://github.com/rautshivamxyz-beep/NOVA-APK/releases/download/desktop-v2/NOVA-Desktop-Windows.zip**

If Edge says the file might be unsafe, click **Keep** (or Downloads → `...` → Keep).

---

## Step 2 - Unzip

1. Find the downloaded file `NOVA-Desktop-Windows.zip`
2. **Right-click** it → **Extract All...** → **Extract**
3. You now have a folder called **NOVA-Desktop-Windows**

> You can put this folder anywhere - Desktop is fine. But **do not** rename
> things inside it.

---

## Step 3 - Allow it in Windows Defender (important)

Windows blocks apps that are not signed. NOVA's AI engine is not signed, so you
may see a warning.

1. Open **Windows Security**
2. **Virus & threat protection** → **Manage settings**
3. Scroll to **Exclusions** → **Add or remove exclusions** → **Add a folder**
4. Select your **NOVA-Desktop-Windows** folder
5. Click **Yes** when Windows asks

> Also: if you get **"Windows protected your PC"** when running a file, click
> **More info** → **Run anyway**.

---

## Step 4 - Make the Desktop icon

1. Open the **NOVA-Desktop-Windows** folder
2. Double-click **`Create Desktop Shortcut.bat`**
3. Press **F5** on your Desktop (Windows caches icons)
4. You will see a **NOVA** icon on your Desktop

> **Important:** you must do this **on each computer**. A shortcut made on one
> laptop will not work on another.

---

## Step 5 - Open NOVA

1. Double-click the **NOVA** icon on your Desktop
2. A NOVA window opens
3. The first time, NOVA asks you to **pick a model** (the AI brain). Choose one:
   - **Qwen3 1.7B** - better answers - about 1.1 GB
   - **Qwen3 0.6B** - faster - about 0.4 GB
4. Wait for the download (progress bar is shown inside the app)
5. NOVA starts. That's it!

From now on, just double-click the NOVA icon. **No internet needed.**

---

## Already have a model? (optional)

If you already have a `.gguf` file (for example, copied from your phone):

1. Open the **models** folder inside NOVA
2. Put your `.gguf` file there
3. Open NOVA → **Models** screen → click **Use this** → restart NOVA

You can also **drag and drop** a `.gguf` file anywhere onto the NOVA window.

---

## Common problems and fixes

**"Windows protected your PC"**
→ Click **More info** → **Run anyway**. (Do the Defender exclusion in Step 3.)

**The Desktop icon is blank / nothing happens when I click it**
→ The shortcut is pointing at a folder that moved. Delete the Desktop shortcut,
then run **`Create Desktop Shortcut.bat`** again from inside the NOVA folder.
Remember: a shortcut only works on the computer where it was made.

**It asks me to choose a program / asks for python.exe**
→ The `python` folder inside NOVA is missing or was deleted by antivirus.
Do the **Defender exclusion** (Step 3), then **unzip the zip again** into a fresh
folder, and run `Create Desktop Shortcut.bat` once more.

**I want to see what is going wrong**
→ Run **`Start NOVA (show errors).bat`** from inside the NOVA folder. It keeps a
window open and shows the error. Send that text to whoever gave you NOVA.

**It is slow**
→ Use the smaller model (**Qwen3 0.6B**), and close other heavy apps. More free
RAM = faster answers. In NOVA, open **Settings → answer style → Concise** for
shorter, quicker replies.

**How do I stop NOVA?**
→ Open NOVA → **Settings → Quit NOVA**. (If you just close the window, NOVA
stops by itself after a few minutes.)

**Where is my data?**
→ In the **data** folder inside NOVA (notes, memory, documents, reminders).
Use **Settings → Download backup** to save a copy.

---

## What NOVA can do

- Chat, explain, help you study - offline
- Read and summarise your own notes, PDFs and documents
- Make quizzes, flashcards and revision plans
- Reminders, morning briefing, read your notifications
- Look something up online (only when you allow it, and only as text)
- Build its own small tools and skills, and get better over time

## What NOVA cannot do

- Watch videos or listen to audio
- Log into your accounts (YouTube, Instagram, Gmail...)
- Click or scroll apps for you
- Delete or move your files
- Send anything anywhere

---

## For phones

NOVA also runs on Android. Latest APK:

**https://github.com/rautshivamxyz-beep/NOVA-APK/releases/latest**

NOVA is free and open source: https://github.com/rautshivamxyz-beep/NOVA
