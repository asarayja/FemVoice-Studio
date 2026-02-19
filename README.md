FemVoice Studio — Intelligent Voice Feminization Biofeedback System

FemVoice Studio is a real-time, clinically-informed voice training platform designed to support safe, effective, and adaptive voice feminization through modern biofeedback technology.

Unlike traditional pitch-focused voice apps, FemVoice Studio prioritizes resonance shaping, stability, and vocal health — the core elements that determine perceived vocal femininity.

🌱 Key Principles

✔ Resonance-first training (formant-based, not pitch chasing)
✔ Adaptive progression per user
✔ Real-time biofeedback
✔ Vocal health protection
✔ Research-based clinical framework
✔ Motor learning focused design

🧠 Core Technology

Built with:

.NET 10

WPF (MVVM architecture)

NAudio for real-time audio processing

FFT + formant analysis

Event-driven service architecture

Clean Architecture with dependency injection

Unit tested adaptive logic

🔬 Core Systems
🎯 ResonanceProxyEngine

Real-time extraction of formant frequencies (F1/F2/F3), spectral brightness, and resonance stability to quantify feminine vocal resonance.

📊 FemVoiceScoreEngine

Adaptive composite scoring with personal baselines, trend detection, plateau and regression monitoring.

🧬 ComfortZoneController

Dynamic pitch safety boundaries with automatic expansion, contraction, and strain protection.

🤖 SmartCoachEngine

Context-aware real-time coaching integrated directly into exercises.

🎧 Real-Time Visual Feedback

Pitch graph

Spectrogram with resonance intelligence (in development)

Stability and comfort indicators

📈 Current Development Status
Module	Status
Real-time audio processing	✅ Complete
ResonanceProxyEngine	✅ Complete
Adaptive scoring system	✅ Complete
Comfort zone safety	✅ Complete
SmartCoach background system	✅ Complete
Intelligent exercise system	🚧 In progress
Spectrogram intelligence	🚧 In progress
Hydration & fatigue advisor	🚧 Planned
Long-term progression analytics	🔮 Planned
🧪 Testing

174+ unit tests passing

No UI-dependent logic in core engines

All real-time systems event-driven and thread-safe

🎯 Why FemVoice Studio Is Different

Most voice training apps focus only on raising pitch.

FemVoice Studio trains:

✔ vocal tract resonance
✔ tonal stability
✔ safe progression
✔ real-time acoustic feedback

This reflects modern clinical voice feminization research rather than outdated pitch-only models.

🚀 Roadmap Highlights

Intelligent real-time exercise feedback

Spectrogram-based resonance visualization

Inline coaching during training

Adaptive hydration & fatigue protection

Predictive progression modeling

⚠ Disclaimer

FemVoice Studio is a training support tool and not a replacement for professional speech therapy.
Users experiencing vocal discomfort should consult a qualified speech-language pathologist.

🤝 Contributing

This project follows Clean Architecture and event-driven design principles.

Contributions should maintain:

UI-independent core logic

Dependency injection

Unit test coverage

Thread-safe real-time processing

📄 License

(To be defined)
