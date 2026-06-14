# FemVoice Studio

FemVoice Studio is a Windows desktop application for voice feminization training. It provides real-time acoustic biofeedback, structured exercises, adaptive coaching, and long-term progress tracking — all running locally on your PC.

The app is built around modern clinical voice research. Rather than focusing on pitch alone, FemVoice Studio trains resonance shaping, tonal stability, intonation variation, and vocal health — the factors that most influence perceived vocal femininity.

> FemVoice Studio is a training support tool. It is not a medical device and does not replace a qualified speech-language pathologist or clinician.

---

## What It Does

- Captures real-time voice input from your microphone and displays live pitch and resonance feedback.
- Analyses pitch (Hz), resonance (F1/F2/F3 formants), intonation variation, vocal weight, comfort, and consistency.
- Provides structured exercises for pitch, resonance, intonation, breathing, and practical speech.
- Tracks training sessions and scores over time with trend analysis.
- Adapts training difficulty and focus based on your recent history through SmartCoach.
- Monitors vocal health signals and prompts rest, hydration, and recovery when needed.
- Generates PDF, CSV, and JSON reports for personal review or sharing with a professional.
- Stores all data locally on your computer.
- Supports light mode, dark mode, and system default themes.
- Available in 20 languages.

---

## Who It Is For

FemVoice Studio is primarily designed for transfeminine individuals working toward a more feminine speaking voice. It can also be useful for anyone wanting a structured, self-guided voice practice tool with measurable feedback.

It is not intended to replace clinical voice therapy. Users with vocal health concerns should consult a qualified professional.

---

## Core Training Philosophy

Most voice training apps focus on raising pitch as high as possible. FemVoice Studio takes a different approach.

Pitch matters, but perceived femininity is more strongly influenced by **resonance placement**, **tonal stability**, and **intonation variation**. Chasing pitch without building resonance and comfort often leads to strain, fatigue, and unsustainable habits.

FemVoice Studio is designed to:

- Prioritise resonance shaping over pitch chasing.
- Protect vocal health throughout every session.
- Build habits that are sustainable over weeks and months.
- Adapt to each user's individual baseline and progression rate.
- Discourage pushing, pressing, or forcing the voice.

---

## Main Areas

### Dashboard
The main practice surface. Shows live pitch and resonance feedback, comfort-zone status, current SmartCoach recommendations, session controls, streaks, and quick access to all other tools.

### Exercise Guide
A structured library of practice activities organised by focus area and difficulty level. Exercises cover pitch gliding, resonance placement, intonation patterns, breath control, sentence reading, and conversation simulation. Each exercise includes step-by-step guidance, real-time feedback, and safety notes.

### SmartCoach
An adaptive coaching system that uses your training history, health signals, and progression data to recommend what to focus on each day. SmartCoach adjusts its suggestions based on recovery status, plateau detection, recent scores, and voice health indicators.

### Analysis
Detailed charts and trend views for pitch, resonance, intonation, vocal weight, comfort, and health-related signals. Includes session summaries, score history, and longitudinal trends. These tools are for training feedback and self-reflection — not clinical diagnosis.

### Resonance Analysis
A dedicated window for formant-based resonance inspection. Displays real-time F1/F2 placement, a resonance timeline, and target area overlays. Useful for understanding resonance patterns and forward placement during practice.

### Progression
Shows how your training is developing over time. Tracks level transitions, session consistency, success rates, and whether there is enough data to make meaningful progress estimates.

### Case Review
Allows you to create, review, and complete structured voice session reviews. Useful for personal reflection or for sharing selected notes with a speech therapist or clinician.

### Reports
Generates exportable summaries in PDF, CSV, or JSON format. Report types include a coaching summary, a clinical progress report, a voice development timeline, and an outcome summary.

### Settings
Covers theme, language selection, voice goals, training frequency, accessibility options (calm mode, reduced visual feedback), microphone calibration, monitoring your own voice in real time, backup and restore, and database management.

---

## Supported Languages

FemVoice Studio is fully localised and currently available in:

🇬🇧 English · 🇳🇴 Norwegian · 🇸🇪 Swedish · 🇩🇰 Danish · 🇫🇮 Finnish  
🇫🇷 French · 🇪🇸 Spanish · 🇵🇹 Portuguese (Brazil) · 🇮🇹 Italian · 🇭🇷 Croatian  
🇩🇪 German · 🇳🇱 Dutch · 🇵🇱 Polish · 🇨🇿 Czech · 🇭🇺 Hungarian  
🇷🇴 Romanian · 🇹🇷 Turkish · 🇺🇦 Ukrainian · 🇷🇺 Russian · 🇸🇦 Arabic · 🇬🇷 Greek

The localisation system is built for easy expansion with additional languages in future releases.

---

## Data and Privacy

FemVoice Studio is local-first. All training data, session history, settings, and notes are stored on your own computer. Nothing is sent to external servers.

Exports and support packages are entirely user-controlled. Avoid including personal identifiers or sensitive health information in exports unless you intend to share them.

---

## System Requirements

- Windows 10 (version 1809 or later) or Windows 11
- .NET Desktop Runtime 10
- A working microphone
- A reasonably quiet practice environment

---

## Core Technology

| Component | Details |
|---|---|
| Framework | .NET 10, WPF, MVVM |
| Audio | NAudio — real-time capture and processing |
| Acoustic analysis | FFT-based pitch detection, formant extraction (F1/F2/F3) |
| Architecture | Clean Architecture, dependency injection, event-driven services |
| Data | SQLite via Microsoft.Data.Sqlite |
| Visualisation | OxyPlot |
| Reports | QuestPDF |
| Testing | xUnit with full unit test coverage |

---

## Development Status

| Module | Status |
|---|---|
| Real-time audio processing | ✅ Complete |
| Resonance analysis (F1/F2/F3) | ✅ Complete |
| Adaptive scoring system | ✅ Complete |
| Comfort zone safety controller | ✅ Complete |
| SmartCoach engine | ✅ Complete |
| Exercise library | ✅ Complete |
| Session tracking and progression | ✅ Complete |
| Report export (PDF/CSV/JSON) | ✅ Complete |
| Intelligent exercise biofeedback | ✅ Complete |
| Spectrogram intelligence | ✅ Complete |
| Hydration advisor | ✅ Complete |
| Long-term longitudinal analytics | ✅ Complete |

---

## Safety

Stop or pause immediately if you experience pain, strain, hoarseness, dizziness, or unusual discomfort. The app includes built-in safety systems that monitor vocal load and prompt rest when signals indicate strain — but these are assistive tools, not guarantees.

Use FemVoice Studio as a training aid. For clinical concerns, consult a qualified speech-language pathologist.

---

## Contributing

FemVoice Studio follows Clean Architecture and event-driven design principles. Contributions should maintain:

- UI-independent core logic
- Constructor-injected dependencies
- Thread-safe real-time processing
- Unit test coverage for new behaviour

---

## License

To be defined.
