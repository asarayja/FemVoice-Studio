FemVoice Studio — Intelligent Voice Feminization Biofeedback System

FemVoice Studio is a real-time, clinically-informed voice training platform designed specifically to support transfeminine individuals (trans girls and women) in developing a more feminine speaking voice in a safe, adaptive, and sustainable way.

Unlike traditional pitch-focused voice apps, FemVoice Studio prioritizes vocal resonance shaping, tonal stability, and vocal health — the primary factors influencing perceived vocal femininity. it will be coming out when done

🌱 Core Training Philosophy

✔ Resonance-first feminization (formant-based, not pitch chasing)
✔ Adaptive progression per individual user
✔ Real-time biofeedback learning
✔ Vocal health protection & strain prevention
✔ Intelligent hydration support (in development)
✔ Research-based aggregate clinical framework

🌍 Multilingual Support

FemVoice Studio is fully localized and currently supports:

🇬🇧 English

🇳🇴 Norwegian

🇸🇪 Swedish

🇩🇰 Danish

🇫🇮 Finnish

🇫🇷 French

🇪🇸 Spanish

🇵🇹 Portuguese

🇮🇹 Italian

🇭🇷 Croatian (Hrvatski)

The localization system is designed to easily expand with additional languages in future updates.

🧠 Core Technology

Built with:

.NET 10

WPF with MVVM architecture

NAudio for real-time audio processing

FFT and formant-based acoustic analysis

Event-driven service communication

Clean Architecture with dependency injection

Comprehensive unit test coverage

🔬 Core Systems
🎯 ResonanceProxyEngine

Extracts formant frequencies (F1/F2/F3), spectral brightness, spacing metrics, and stability to quantify feminine vocal resonance in real time.

📊 FemVoiceScoreEngine

Adaptive composite scoring with personal baselines, long-term trend detection, plateau and regression monitoring.

🧬 ComfortZoneController

Dynamic pitch safety boundaries with automatic expansion, contraction, and strain protection.

🤖 SmartCoachEngine

Context-aware real-time coaching integrated directly into training exercises.

🎧 Real-Time Visual Feedback

Live pitch graph

Live spectrogram with resonance intelligence

Stability and comfort indicators

💧 Vocal Health & Hydration Support

FemVoice Studio includes built-in vocal health monitoring to help prevent strain and fatigue during training sessions.

A planned hydration reminder system will intelligently prompt users to drink water when acoustic signals indicate dryness or increased vocal effort — based on real voice behavior such as:

• rising instability
• darker resonance patterns
• increasing strain indicators
• extended training load

This ensures safe, sustainable voice feminization practice.

📈 Development Status
Module	Status
Real-time audio processing	✅ Complete
ResonanceProxyEngine	✅ Complete
Adaptive scoring system	✅ Complete
Comfort zone safety	✅ Complete
SmartCoach system	✅ Complete
Intelligent exercise biofeedback	🚧 In progress
Spectrogram intelligence	🚧 In progress
Hydration advisor	🚧 Planned
Long-term analytics	🔮 Planned
🎯 Why FemVoice Studio Is Different

Most voice training apps focus only on raising pitch.

FemVoice Studio trains:

✔ vocal tract resonance
✔ tonal stability
✔ safe progression
✔ real-time acoustic awareness

This reflects modern clinical voice feminization research rather than outdated pitch-only training models.

⚙ Localization Architecture (Technical Overview)

FemVoice Studio uses a scalable localization system built on:

🔹 Resource Files (.resx)

Each supported language has a dedicated resource file:

Resources/
  Strings.en.resx
  Strings.no.resx
  Strings.sv.resx
  Strings.da.resx
  Strings.fi.resx
  Strings.fr.resx
  Strings.es.resx
  Strings.pt.resx
  Strings.it.resx
  Strings.hr.resx


Each file contains translated UI strings mapped by shared keys.

🔹 LocalizationService (DI-based, non-static)

Key features:

• No static singletons
• Constructor-injected
• Thread-safe
• WPF binding support
• Live language switching
• Testable with in-memory implementation

Example interface:

public interface ILocalizationService
{
    string GetString(string key);
    void SetLanguage(string languageCode);
}

🔹 Hybrid Configuration

Default language defined in code
User preference override via settings
Persisted per user profile

🔹 Benefits

✔ Easy language expansion
✔ No UI coupling
✔ Unit test friendly
✔ Clean Architecture compliant

⚠ Disclaimer

FemVoice Studio is a training support tool and not a replacement for professional speech therapy.
Users experiencing vocal discomfort should consult a qualified speech-language pathologist.

🤝 Contributing

This project follows Clean Architecture and event-driven design principles.

Contributions should maintain:

• UI-independent core logic
• dependency injection
• unit test coverage
• thread-safe real-time processing

📄 License

(To be defined)
