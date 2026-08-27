# Andrew Huang

Full-Stack Software Engineer with 5+ years of production experience across React frontends and Python backends, with additional experience in Java. Architected production-grade backend services — including secure payment infrastructure (Stripe), role-based authentication (Cognito, JWT), and asynchronous, queue-based systems (Celery/Redis) — spanning both AWS-deployed and independently hosted platforms, with a strong grasp of API design, distributed systems, and PostgreSQL schema/query optimization. Independently diagnosed and resolved a live production incident under load, then built observability tooling that cut similar diagnosis time from days to minutes.

## Projects

### VoiceAgent — Real-Time AI Voice Dispatch Agent
Twilio Media Streams → Deepgram STT → Claude tool-calling → ElevenLabs TTS, backed by a FastAPI/SQLAlchemy CRM. Identity-verified booking modification via Twilio Caller ID, 99% backend test coverage. Verified end-to-end over a real phone call.
`Python` `Pipecat` `Anthropic Claude` `Twilio` `FastAPI` `SQLAlchemy` `pytest`
[Repo](https://github.com/azhgit/VoiceAgent)
[Live Demo] Call 778-651-3549

### CarbonTrace — ESG Carbon-Emissions Data & Analytics Platform
Full-stack SaaS for automated ESG carbon-emissions reporting: Playwright browser automation, Celery/Redis async task queue, PostgreSQL-backed REST API. Diagnosed and resolved a production incident involving duplicate scheduled runs via distributed locking and a circuit breaker.
`Python` `Celery` `Redis` `PostgreSQL` `Playwright`
Private repo — client project
[Demo excel for uploading] (https://drive.google.com/drive/folders/1Bf5ZwKwFjsJDyCgUixLO8wb3Y_Zi02TG?usp=drive_link)
[Live Demo] (https://carbontrace.up.railway.app)

### CourseFlow — AI-Powered Knowledge Q&A System
Domain-agnostic RAG-based Q&A system.
`FastAPI` `Gemini` `ChromaDB`
[Repo](https://github.com/azhgit/courseflow)
[Live Demo] (https://courseflow.zeabur.app)

### ICAO Carbon Automation
Multi-threaded automated batch query system for ICAO Carbon Emissions, with Excel support.
`Python`
[Repo](https://github.com/azhgit/icao-carbon-automation)

### BFRB Detection
Deep learning + NLP model for detecting body-focused repetitive behaviors.
`Deep Learning` `NLP`
[Repo](https://github.com/azhgit/bfrb-detection)
