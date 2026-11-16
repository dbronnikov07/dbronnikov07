## Hi there 👋

### 🔒 Featured: [Lock In](https://github.com/Patrick-Lahoud/lockin) · 🥈 2nd place, ONHacks 2026

<a href="https://github.com/Patrick-Lahoud/lockin"><img src="assets/lockin-icon.svg" alt="Lock In" height="64"></a>

**One timer locks your phone and your laptop.** You put your phone in a box and tap Lock In. A servo latch locks it, and social media goes dark on the laptop in every browser. An AI agent reads your notifications while you focus. Real emergencies get through, tasks land on your to-do list, and everything else waits for a summary.

**What I built:**
- 🧠 **AI agent:** a Telegram bot with Gemini triage that sorts notifications into urgent, to-do or noise. It filters noise, merges duplicates and sends a digest every 5 minutes, and it has study Q&A and emergency exits.
- 💻 **Laptop blocker:** a device-wide blocker that works in every browser with no extension. It runs as a root service, fails closed and is hard to get around.
- ⚙️ **Server:** a FastAPI server that holds the single source of truth. It has rate limits, atomic state, an emergency exit that always opens the box, and a notification inbox for the phone.
- 🔐 **Security:** a security audit, plus secret scanning and redaction, an API spend budget and model failover.
- 🧪 **Testing and demo:** a 59-check self-test, a scripted live demo, the system architecture and the pitch deck.

**Stack:** Python · FastAPI · Raspberry Pi 4 · GPIO servo · Gemini API · Telegram Bot API · launchd
