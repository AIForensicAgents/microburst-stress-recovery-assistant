┌─────────────────────────────────────────────────────────────────────┐
│                        DATA COLLECTION LAYER                        │
│  Voice Prosody │ HR/HRV │ Typing/Motion │ Calendar │ Ambient Noise │
└────────┬───────┴────┬───┴───────┬───────┴─────┬────┴───────┬───────┘
         │            │           │             │            │
         ▼            ▼           ▼             ▼            ▼
┌─────────────────────────────────────────────────────────────────────┐
│               MULTIMODAL FUSION & ANOMALY DETECTION                 │
│         On-device ML  ·  Real-time signal processing                │
│         Stress-spike classification  ·  Context inference           │
└──────────────────────────────┬──────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────┐
│                 PERSONALIZATION & DECISION ENGINE                    │
│     Contextual Bandits  ·  Reinforcement Learning                   │
│     Environment assessment  ·  Privacy mode selection               │
│     Intervention ranking  ·  Sequence optimization                  │
└──────────────────────────────┬──────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    INTERVENTION DELIVERY LAYER                       │
│       Haptic patterns │ On-screen prompts │ Audio guidance           │
│       Duration: 1–3 min │ Opt-out always available                  │
└──────────────────────────────┬──────────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    FEEDBACK & LEARNING LOOP                          │
│   Post-intervention HR/HRV tracking  ·  Self-report micro-surveys   │
│   Model update (on-device or federated)  ·  Habit pattern analysis  │
└─────────────────────────────────────────────────────────────────────┘