# SikaAI

### Your AI assistant for interview questions and answers

SikaAI is a Windows desktop app that turns spoken questions and screenshots into clear, personalized AI answers. Follow live transcription, get answers with a keyboard shortcut, and tailor responses using your resume, job description, and saved Q&A.

**[Download for Windows](https://github.com/sikaforyou/sika-ai/releases/latest)** | [Visit Website](https://sikaforyou.com/) | [All Releases](https://github.com/sikaforyou/sika-ai/releases)

This repository provides SikaAI installers and release information. It does not contain the application source code.

## Download and Install

1. Open the [latest release](https://github.com/sikaforyou/sika-ai/releases/latest).
2. Under **Assets**, download the Windows installer ending in `.exe`. The **Source code** ZIP and TAR files are not installers.
3. Run the installer and open **SikaAI**.
4. Open **My Account** and activate the app using your SikaForYou User ID.
5. Make sure your account has available credits before starting a session.

### Requirements

- Windows 10 or Windows 11, 64-bit.
- An internet connection for activation, transcription, and AI answers.
- An active SikaForYou account with available credits.
- A working microphone or system audio source for spoken questions.

You do not need to install Python, Node.js, or developer tools.

## Features

- **Live transcription:** Capture speech from your microphone, system audio, or both.
- **Answers on demand:** Generate an answer from the latest transcript with `Ctrl+Tab`.
- **Screenshot answers:** Use `Ctrl+Shift+S` to capture your primary screen and answer the visible question.
- **Personalized responses:** Add your resume and job description to give answers relevant context.
- **Local Q&A Bank:** Save your own questions and answers, search them, and import entries from CSV. SikaAI can use matching entries to respond in your style.
- **Session controls:** Start and stop explicitly, with a visible session timer.
- **Readable answers:** View formatted text and code blocks, copy answers, and browse answer history.
- **Compact window:** Collapse or expand the app and move it using keyboard shortcuts.
- **Private mode:** Control whether the app requests protection from screen capture.
- **Update notifications:** See when a newer release is available from the app's menu.

## Get Started

1. Open the three-dot menu and select **My Account** to check your activation and credits.
2. Add your **Resume Details** and **Job Description** if you want more personalized answers.
3. Click **Start** in the header. The app enables microphone and system audio; switch off either source if you do not need it.
4. Speak or play the audio you want transcribed.
5. Press **Ctrl+Tab** for an answer, or **Ctrl+Shift+S** for a screenshot answer.
6. Click the **Stop** icon when you finish.

Transcription and answer generation require an active session. The session timer includes connected time during silence, so stop the session when you are finished. Check **My Account** for your credit balance.

## Keyboard Shortcuts

| Shortcut | Action |
| --- | --- |
| `Ctrl+Tab` | Generate an answer from the latest transcript |
| `Ctrl+Shift+S` | Generate an answer from a screenshot |
| `Ctrl+O` | Compact or expand the app |
| `Ctrl+Left` | Move the app to the left |
| `Ctrl+Right` | Move the app to the right |
| `Ctrl+Up` | Scroll the answer up |
| `Ctrl+Down` | Scroll the answer down |
| `Ctrl+M` | Open My Account |
| `Ctrl+Q` | Exit SikaAI |

You can also open **App Shortcuts** from the three-dot menu.

## Local Q&A Bank

Open **Local Q&A Bank** from the three-dot menu to add, edit, search, or delete your saved entries. Use its toggle to choose whether SikaAI includes matching saved answers when generating responses.

For CSV imports, include these two column headers:

```csv
question,answer
"Tell me about yourself.","I am a software developer with experience building web applications."
"What is a JavaScript closure?","A closure lets a function access variables from its outer scope."
```

- Questions can contain up to **300 characters**.
- Answers can contain up to **5,000 characters**.
- Put fields containing commas or line breaks inside double quotes.

## Private Mode

Private mode requests screen-capture protection for SikaAI windows. Turn it off when you want the app to appear during screen sharing.

Capture protection depends on Windows and the recording or sharing tool. Check your sharing preview before relying on it; it is not a guarantee of invisibility in every tool.

Private mode controls screen visibility. Transcription and AI answers still require online processing.

## Updating SikaAI

When an update is available, the three-dot menu shows an update badge and a **New Update** option.

Select the update option to open the download link. SikaAI then exits so you can run the downloaded installer. You can also get the installer directly from the [latest release](https://github.com/sikaforyou/sika-ai/releases/latest).

If the app displays **Update Required**, install the latest version to continue.

## Help and Support

- **Website:** [sikaforyou.com](https://sikaforyou.com/)
- **Account dashboard:** [Manage your account](https://sikaforyou.com/dashboard)
- **Credits:** [Buy credits](https://sikaforyou.com/buy-credits)
- **Email:** [support@sikaforyou.com](mailto:support@sikaforyou.com)

When reporting a problem, include your SikaAI version, Windows version, the steps that caused the issue, and any error message shown.
