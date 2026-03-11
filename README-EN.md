# Kenzo AI - Desktop Virtual Assistant

Kenzo AI is an intelligent virtual assistant built in Python, focused on productivity and task automation on Windows. With a modern interface and cloud integration, Kenzo does not only respond to voice commands but continuously learns from user preferences.

## Key Features

- **Voice Control & Natural Responses:** Utilizes voice recognition and neural synthesis (Edge-TTS) for fluid background conversations.
- **AI Brain:** Integrated with the Google Gemini API, capable of maintaining context and responding to complex questions.
- **Continuous Learning:** An intelligent system where the assistant learns new rules when corrected by the user, saving the learning data to the database.
- **Cloud Synchronization:** Login system via Firebase. User memories and preferences are saved in the cloud and synchronized across any computer.
- **PC Automation:**
  - Media control (Spotify, YouTube Music, Volume, Pause/Skip).
  - Opening local applications and websites.
  - Windows window control.
- **Time Management:** Intelligent creation of Google Calendar events and setting alarms/timers running in parallel Threads.
- **Background Execution:** Graphical interface built with `customtkinter`, minimizable to the system tray (System Tray) to run silently.
- **Routine creation method (Short):**
  You: "Kenzo, create routine"
  Kenzo: "I understand. What should be the phrase to activate this routine?"
  You: "Study Mode"
  Kenzo: "Right. And what actions should I take when you say Study Mode?"
  You: "Open notepad and play lofi on youtube"

## Technologies Used

- **Language:** Python
- **Interface:** CustomTkinter (GUI) and PyStray (System Tray)
- **Artificial Intelligence:** `google-genai` (Gemini 2.5 Flash)
- **Database:** Firebase Realtime Database & Authentication (`pyrebase4`)
- **Voice and Audio:** `speech_recognition`, `edge-tts`, `pyaudio`, `pygame`
- **Automation:** `pyautogui`, `pywhatkit`, `AppOpener`

## How to run locally
- Download the .exe, run it and call Kenzo to activate it, from there make your requests.
- Use the account:
  login: `teste@kenzo.com`
  password: `123456`
- For feedback send via email: kenaidesign22@gmail.com
