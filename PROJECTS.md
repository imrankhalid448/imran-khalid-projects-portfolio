# Imran Khalid — Complete Project Portfolio & Engineering Catalog (34 Projects)

> Comprehensive catalog of production systems, AI/ML research, enterprise software, and academic engineering projects stored in CareerOS (`data/app.db`).

---

## 1. QuantEye — Smart CCTV Attendance & Workforce Monitoring System
**Tagline:** *Walk In. Get Marked. Zero-touch AI attendance powered by live CCTV and face recognition.*

- **Problem Statement:** Traditional biometric (fingerprint and RFID) attendance systems create bottlenecks during shift changes, fail when hands are wet or dusty on industrial sites, and remain vulnerable to proxy attendance or manual tampering across distributed locations.
- **Detailed Description:** Engineered a real-time Computer Vision workforce attendance platform that connects directly to existing CCTV camera streams. The system detects and recognizes employees as they walk in, verifies site presence with GPS coordinates, logs live monitoring events, and syncs attendance records directly with HRM workflows—eliminating hardware friction and manual roll calls.
- **Tech Stack:** Python, Computer Vision, Face Recognition, FastAPI, Real-Time Video Streaming, GPS & HRM Integration.
- **Repository:** `https://github.com/QIntellect-Technologies/QuantEye-ForknKnives.git`

---

## 2. Scrybix.ai — AI Transcription & Speaker Diarization
**Tagline:** *Multi-speaker audio to structured, speaker-labeled transcripts in seconds.*

- **Problem Statement:** Teams, clinics, podcasters, and researchers spend hours manually transcribing multi-speaker audio because generic speech-to-text tools merge voices together and fail to identify who said what.
- **Detailed Description:** Built a full-stack AI transcription web application that processes uploaded audio files asynchronously, performs high-accuracy transcription paired with speaker diarization, and presents clean, speaker-attributed transcripts in a modern UI. Audio storage and orchestration run on AWS while heavy GPU inference scales serverlessly on Modal.
- **Tech Stack:** React, FastAPI, AWS, Modal GPU Inference, Speech-to-Text, Speaker Diarization.
- **Live URL:** `https://scrybix.ai/`

---

## 3. GenFedRepKG — Drug Repurposing AI for Rare Diseases
**Tagline:** *Privacy-preserving, explainable therapeutic discovery using Generative AI, Knowledge Graphs, and Federated Learning.*

- **Problem Statement:** Rare-disease drug discovery suffers from severe data scarcity, fragmented biomedical knowledge, and strict hospital privacy regulations that prevent institutions from centralizing sensitive patient and clinical datasets.
- **Detailed Description:** Designed a multi-institutional AI research framework combining Generative AI, biomedical Knowledge Graphs, Explainable AI (XAI), and Federated Learning. The system predicts novel drug-repurposing candidates across distributed datasets without exposing raw data, supported by multi-source drug–target–disease integration, three-stage validation, and human-interpretable reasoning paths for scientific trust.
- **Tech Stack:** Generative AI, Knowledge Graphs, Federated Learning, Explainable AI (XAI), Biomedical Data Pipelines.

---

## 4. Swift Sales — ML/NLP Automation & WhatsApp Chatbot
**Tagline:** *24/7 NLP-powered order, stock, and customer automation for pharmaceutical distribution.*

- **Problem Statement:** Pharmaceutical distributors handle hundreds of repetitive daily WhatsApp and website inquiries regarding product availability, pricing, and order status—leading to slow response times, overloaded staff, and manual order errors.
- **Detailed Description:** Developed an end-to-end ML/NLP automation system that understands natural language queries, classifies user intent, and responds in real time to product, service, and order inquiries. Integrated seamlessly with both the company website and WhatsApp to automate routine communication and deliver consistent, data-driven customer engagement.
- **Tech Stack:** Python/Node.js, NLP, ML Intent Classification, Website & WhatsApp Integration.

---

## 5. Alzheimer MRI Detection — Deep Learning Classification
**Tagline:** *Explainable CNN diagnostics for early-stage Alzheimer's classification from brain MRI scans.*

- **Problem Statement:** Detecting early-stage Alzheimer's disease from structural MRI scans is subtle, time-intensive, and sensitive to scanner/patient variability, while standard black-box deep learning models lack the visual transparency clinicians require.
- **Detailed Description:** Built a complete medical-imaging deep learning pipeline encompassing MRI preprocessing, denoising, data augmentation, and class balancing. The CNN architecture accurately classifies disease stages across varied patient scans and generates Grad-CAM heatmaps highlighting affected brain regions to support clinical research and diagnostic review.
- **Tech Stack:** PyTorch / TensorFlow, Convolutional Neural Networks (CNNs), Medical Image Processing, Grad-CAM.

---

## 6. VoiceStudio — AI Voice Generator
**Tagline:** *Browser-based studio for rapid AI voice synthesis and creative audio previews.*

- **Problem Statement:** Content creators, educators, and product teams need natural-sounding voiceovers quickly without setting up complex DAWs or expensive studio recording pipelines.
- **Detailed Description:** Built a responsive React + Vite + Tailwind web application integrated with Google GenAI APIs (`@google/genai`), enabling users to script, generate, and preview AI voiceovers directly in the browser with a clean, modern creator interface.
- **Tech Stack:** React, Vite, Tailwind CSS, `@google/genai`, Lucide React.

---

## 7. Missed-Scan-Agent (ScanGuard AI)
**Tagline:** *Automated anomaly detection and analytics for catching missed operational scans before they cost revenue.*

- **Problem Statement:** In high-volume logistics, warehouse, and retail workflows, missed barcode or package scans frequently go unnoticed until downstream billing discrepancies, lost inventory, or delivery failures occur.
- **Detailed Description:** Built ScanGuard AI, pairing a Python backend with a React + Recharts analytics dashboard that surfaces missed-scan events, visualizes operational trends, and helps operations teams audit and resolve scan gaps before downstream impact.
- **Tech Stack:** Python Backend, React, React Router, Recharts, Lucide React.

---

## 8. QI-Leads — B2B Sales Management System
**Tagline:** *Fast, single-laptop B2B CRM built for teams selling AI and hardware-software systems.*

- **Problem Statement:** Technical sales teams selling enterprise solutions (such as AI Attendance Systems and GPS Tracking) lose track of follow-ups, demos, and proposals when leads are scattered across spreadsheets and WhatsApp chats.
- **Detailed Description:** Engineered a high-performance, local-first B2B sales CRM tailored specifically for tracking enterprise leads, demo schedules, and deal stages on a single laptop with zero cloud bloat.
- **Tech Stack:** CRM Architecture, B2B Lead Pipeline Management.

---

## 9. EDI-Project (AS2 Gateway)
**Tagline:** *Enterprise-grade standalone AS2 gateway for encrypted, signed X12 EDI file exchange.*

- **Problem Statement:** Enterprise supply-chain partners (such as D&H Distributing Co.) enforce strict AS2 cryptographic standards—AES-256 encryption, SHA-256 signing, X.509 certificate verification, and synchronous/asynchronous MDN receipts—before accepting automated X12 invoices and orders.
- **Detailed Description:** Built a standalone Node.js + MongoDB + Redis AS2 gateway supporting `POST /as2` inbound decryption/verification, outbound signed EDI transmission, X.509/OpenPGP key management, RBAC/2FA, dead-letter queues, audit logs, and partner readiness diagnostics.
- **Tech Stack:** Node.js, Express, MongoDB (Mongoose), Redis (`ioredis`), `node-forge`, `asn1js`, `pkijs`, `openpgp`, `node-x12`.

---

## 10. Transport Accounting 2.0
**Tagline:** *Streamlined fleet accounting, trip ledgers, and automated PDF invoicing with GenAI assistance.*

- **Problem Statement:** Regional transport and logistics operators struggle with manual trip ledgers, fragmented expense tracking, and time-consuming invoice/statement generation.
- **Detailed Description:** Built a full-stack React + Express accounting application featuring structured trip/expense ledgers, automated `jsPDF` + `jspdf-autotable` financial report generation, and `@google/genai` integration for smart operational summaries.
- **Tech Stack:** React, Vite, Tailwind CSS, Express, `jsPDF`, `@google/genai`.

---

## 11. Audit Clean (AS2 Gateway Audit Build)
**Tagline:** *Isolated verification and compliance-audit build for enterprise AS2/EDI interoperability.*

- **Problem Statement:** Enterprise EDI integrations require clean, reproducible security and interoperability audits isolated from active development branches prior to partner certification.
- **Detailed Description:** Maintained a dedicated clean-checkout verification build of the `EDI-Project` AS2 gateway to run cryptographic test suites, certificate expiration checks, and OpenAS2 interoperability validation.
- **Tech Stack:** Node.js, Express, MongoDB, AS2/EDI Test Suite.

---

## 12. CareerOS — Personal LinkedIn & Career AI Agent
**Tagline:** *100% local-first AI Career Studio for grounded LinkedIn posting, profile optimization, and job matching.*

- **Problem Statement:** AI/ML engineers spend hours every week tailoring CVs, drafting authentic LinkedIn posts, reviewing profile positioning, and evaluating job descriptions—while risking privacy if they upload personal data to paid third-party tools.
- **Detailed Description:** Built a modular React + FastAPI + SQLite + Ollama (`qwen2.5:7b`) personal AI agent featuring a pluggable Platform Connector registry, official LinkedIn OAuth 2.0 publishing (`w_member_social`), idempotency locks against duplicate posts, photorealistic post image generation, CV-grounded job scoring, and an autopilot scheduler.
- **Tech Stack:** React, Vite, FastAPI, SQLite, Ollama (`qwen2.5:7b`), Official LinkedIn OAuth 2.0, Pillow, APScheduler.

---

## 13. ai proejct
**Tagline:** *Rapid AI experimentation sandbox for validating model pipelines before production.*

- **Problem Statement:** Moving straight from raw ideas into client production codebases slows down iteration and risks breaking live services.
- **Detailed Description:** Created an isolated AI/ML prototyping workspace under iAXON to test model behaviors, preprocessing logic, and inference flows before promoting them into production applications.
- **Tech Stack:** Python, AI/ML Prototyping.

---

## 14. CodeMate
**Tagline:** *Local Flask + PyTorch + Transformers web assistant for faster developer coding and debugging.*

- **Problem Statement:** Developers lose focus switching between editors, documentation, and search tabs when debugging errors or writing repetitive boilerplate.
- **Detailed Description:** Built a full-stack Flask web application backed by PyTorch and Hugging Face `transformers`, featuring user authentication (`flask-login`), SQLAlchemy persistence, and local transformer inference for code assistance.
- **Tech Stack:** Python, Flask, Flask-SQLAlchemy, PyTorch, Hugging Face `transformers`, Pillow.

---

## 15. finalproject
**Tagline:** *Modular Node.js full-stack application template for rapid web delivery.*

- **Problem Statement:** Repeatedly wiring up project structure, routing, and dependencies from scratch slows down delivery on new web engagements.
- **Detailed Description:** Structured a reusable `node_project` full-stack architecture to accelerate API and frontend setup for client and internal web applications.
- **Tech Stack:** Node.js, JavaScript.

---

## 16. fine_tune_spike
**Tagline:** *Systematic audio/ML fine-tuning and evaluation harness with automated API tests.*

- **Problem Statement:** Off-the-shelf audio and ML models underperform on domain-specific acoustic tasks without structured feature extraction, fine-tuning, and quantitative error analysis.
- **Detailed Description:** Built a FastAPI + Librosa + Scikit-learn fine-tuning and evaluation spike complete with `pytest`/`httpx` async API tests, SQLite persistence, and Matplotlib/Seaborn confusion-matrix and metric visualizations.
- **Tech Stack:** FastAPI, Uvicorn, Librosa, Scikit-learn, NumPy, Matplotlib, Seaborn, Pytest, SQLite.

---

## 17. Fire_project
**Tagline:** *Automated Computer Vision fire and smoke detection for continuous site safety.*

- **Problem Statement:** Industrial warehouses and commercial facilities face severe risk when fast-developing fire or smoke events go unnoticed by human CCTV operators.
- **Detailed Description:** Developed a real-time Computer Vision fire-detection backend pipeline (`Backend_Code`) designed to analyze video frames and trigger early hazard alerts automatically.
- **Tech Stack:** Python, Computer Vision, Backend API.

---

## 18. helmet detecton4
**Tagline:** *Real-time PPE helmet compliance detection for construction and industrial safety.*

- **Problem Statement:** Construction and manufacturing sites experience preventable head injuries when workers enter active zones without required safety helmets.
- **Detailed Description:** Built and trained a Computer Vision object-detection pipeline to automatically detect whether personnel on camera feeds are wearing safety helmets, enabling automated PPE compliance monitoring.
- **Tech Stack:** Python, Computer Vision, Object Detection.

---

## 19. Object_Detection_Project
**Tagline:** *Interactive Flask web app for testing and demonstrating custom object detection models.*

- **Problem Statement:** Evaluating custom-trained object detection models via raw CLI scripts makes visual inspection and stakeholder demos slow and inconvenient.
- **Detailed Description:** Built a Flask (`app.py`) web interface paired with a custom dataset and static/template UI so users can upload test images, run object detection inference, and inspect bounding-box predictions visually.
- **Tech Stack:** Python, Flask, Computer Vision, Object Detection.

---

## 20. project_3D_developer_portfolio-main
**Tagline:** *Interactive 3D web portfolio designed to showcase AI and software engineering work.*

- **Problem Statement:** Traditional flat PDF resumes and plain static pages fail to capture the technical depth and polish expected by modern engineering teams and founders.
- **Detailed Description:** Built an interactive 3D developer portfolio web application featuring spatial visual scenes, project showcases, and responsive navigation.
- **Tech Stack:** JavaScript, 3D Web Graphics, Modern Frontend.

---

## 21. Scrybix_Project
**Tagline:** *Architecture specs, task breakdowns, and foundational codebase for Scrybix transcription.*

- **Problem Statement:** Scaling an AI audio transcription product required clear functional requirements, milestone breakdowns, and an initial working prototype before full-stack expansion.
- **Detailed Description:** Authored the recalled requirements, technical task breakdown list, and foundational Scrybix transcription codebase that evolved into the production Scrybix.ai platform.
- **Tech Stack:** Speech AI, System Architecture, Python, React.

---

## 22. Youtube_video_Downloader
**Tagline:** *Lightweight Python utility for saving local research and dataset media.*

- **Problem Statement:** Researchers and creators frequently need offline access to educational lectures and video datasets without relying on ad-heavy third-party web downloaders.
- **Detailed Description:** Built a clean Python media utility to fetch and save YouTube video and audio streams locally for offline study and dataset preparation.
- **Tech Stack:** Python, Media Processing.

---

## 23. AI-CRM-DASHBOARD
**Tagline:** *AI-assisted React + Radix UI CRM dashboard for instant pipeline and lead insights.*

- **Problem Statement:** Sales and operations teams struggle to extract clear next actions and summaries from dense, multi-tab CRM data.
- **Detailed Description:** Built a modern, accessible CRM dashboard using React, Radix UI primitives, and Tailwind CSS, integrated with `@google/generative-ai` to summarize lead activity and assist sales workflows.
- **Tech Stack:** React, Radix UI, Tailwind CSS, `@google/generative-ai`.

---

## 24. Antigravity Project
**Tagline:** *Experimental incubator for UI prototypes, portfolios, and the QuantumNexus Simulator.*

- **Problem Statement:** Exploring novel UI patterns, portfolio layouts, and simulation interfaces requires a dedicated sandbox separate from client production repos.
- **Detailed Description:** Built multiple interactive web prototypes including `Portfolio`, `TestingStich`, and `quantumnexus-simulator`.
- **Tech Stack:** React, Node.js, Simulation UI.

---

## 25. ERP SMS (Colony School Management)
**Tagline:** *Unified school ERP and automated SMS communication platform with AI insights.*

- **Problem Statement:** Schools and local institutions manage attendance, fee records, and parent SMS notifications across disconnected spreadsheets and manual messaging.
- **Detailed Description:** Built a React + Recharts + `@google/genai` institutional ERP and SMS dashboard that centralizes student/staff operations, visualizes metrics, and streamlines parent communication.
- **Tech Stack:** React, Recharts, Lucide React, `@google/genai`.

---

## 26. Final_scrybix
**Tagline:** *Production-ready full-stack Scrybix release with admin controls and multi-language support.*

- **Problem Statement:** Early transcription prototypes needed a complete admin panel, multi-language context handling, and unified transcript modal workflows before public launch.
- **Detailed Description:** Delivered the full-stack `Final_scrybix` release integrating `AllTranscripts`, transcript modal components, admin panel fixes, and backend/frontend synchronization.
- **Tech Stack:** React, FastAPI, Full-Stack AI.

---

## 27. QIntellectProjects
**Tagline:** *Multi-product engineering hub for QIntellect Technologies' AI, CRM, and web deployments.*

- **Problem Statement:** Building and deploying multiple client AI systems and web platforms at QIntellect Technologies required centralized organization across active deliverables.
- **Detailed Description:** Consolidated and delivered `AI-Powered-Unified-CRM`, `Distributed_Website`, `AI-Attendence-Old`, and production cPanel deployments under a unified engineering workspace.
- **Tech Stack:** AI Systems, Unified CRM, Full-Stack Web, cPanel Deployment.

---

## 28. scrybix_testing
**Tagline:** *Dedicated Modal GPU diarization and audio-upload test harness for Scrybix.*

- **Problem Statement:** Running speaker diarization on serverless GPUs requires isolated load, upload, and timestamp-accuracy testing before pushing changes to production users.
- **Detailed Description:** Built standalone Python test harnesses (`modal_diarize.py`, `upload.py`) with structured logging and storage verification to benchmark and validate Modal diarization pipelines.
- **Tech Stack:** Python, Modal, Speaker Diarization, Automated Testing.

---

## 29. swift-sales-healthcare
**Tagline:** *Semantic search and AI sales automation platform for healthcare & pharma distribution.*

- **Problem Statement:** Healthcare sales teams need instant, accurate answers across massive medical product catalogs without waiting on manual back-office lookups.
- **Detailed Description:** Built a full-stack Express + Supabase platform powered by Hugging Face Inference, `@xenova/transformers`, and `faiss-node` vector search to deliver fast semantic product matching and automated sales support.
- **Tech Stack:** Node.js, Express, Hugging Face, `@xenova/transformers`, `faiss-node`, Supabase, Framer Motion.

---

## 30. BSCS_22-26
**Tagline:** *Core Computer Science academic foundation across algorithms, systems, and ML.*

- **Problem Statement:** Building reliable production AI requires deep mastery of underlying CS fundamentals—data structures, operating systems, databases, and mathematics.
- **Detailed Description:** Completed 6+ semesters of BSCS coursework, labs, and Coursera certifications spanning algorithms, software engineering, databases, and machine learning.
- **Tech Stack:** Python, C++, SQL, Data Structures & Algorithms, ML Foundations.

---

## 31. IXONE Projects
**Tagline:** *Applied ML and IoT engineering projects bridging predictive models with smart environments.*

- **Problem Statement:** Translating theoretical ML and IoT concepts into working end-to-end systems requires hands-on hardware-software integration and regression modeling.
- **Detailed Description:** Built `Home_Automation_FYP` and `House_Prediction_Linear_Regression` under the iAXON/IXONE engineering track.
- **Tech Stack:** Python, Scikit-learn, Linear Regression, IoT / Home Automation.

---

## 32. Machine Learning
**Tagline:** *ML experimentation notebooks and technical conference presentation materials.*

- **Problem Statement:** Communicating complex ML architectures and QuantumNexus concepts to technical audiences requires reproducible notebooks and clear visual decks.
- **Detailed Description:** Developed Jupyter experimentation notebooks (`test.ipynb`) alongside the `quantumnexus-conference-presentation` technical deck.
- **Tech Stack:** Python, Jupyter Notebooks, Machine Learning.

---

## 33. Self Learning
**Tagline:** *Hands-on numerical computing and classical ML foundation builders.*

- **Problem Statement:** Moving from general programming into AI engineering requires fluent command of vectorized numerical computing, data wrangling, and classical ML pipelines.
- **Detailed Description:** Built structured practice projects mastering NumPy, Pandas, and Scikit-learn workflows.
- **Tech Stack:** Python, NumPy, Pandas, Scikit-learn.

---

## 34. University Projects
**Tagline:** *Full-stack academic web applications spanning Django, React, PHP, and MySQL.*

- **Problem Statement:** Mastering web engineering required building complete, database-backed applications across multiple backend and frontend ecosystems.
- **Detailed Description:** Built `Foodies`, `blushy_petals`, Django, React, and PHP/XAMPP full-stack web applications covering authentication, CRUD workflows, and responsive UI design.
- **Tech Stack:** Django, React, PHP, MySQL, HTML/CSS/JavaScript.
