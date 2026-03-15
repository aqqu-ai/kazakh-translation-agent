# System Architecture Diagram

User Input
   │
   ▼
Language Detection
   │
   ▼
Routing Engine
   │
   ├── Direct Translation
   │        │
   │        ▼
   │   Neural Model
   │
   └── Pivot Translation
            │
            ▼
      Source → Pivot → Target
            │
            ▼
       Neural Model
            │
            ▼
      Confidence Scoring
            │
            ▼
      Translation Output
