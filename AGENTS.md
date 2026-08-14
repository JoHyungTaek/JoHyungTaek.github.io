# AGENTS.md

## 1. Project Purpose

This repository is the personal portfolio website of **HyungTaek Jo (조형택)**.

The purpose of this site is to present HyungTaek Jo as an entry-level **AI Engineer** through concrete project experience, technical problem solving, measurable results, awards, certifications, and implementation experience.

This is not a simple profile website.

The portfolio should answer the following questions clearly:

- What AI projects has he actually built?
- What problem did each project try to solve?
- What role did he take?
- What AI models and technologies did he use?
- What technical problems occurred during development?
- How did he solve those problems?
- What measurable results or improvements were achieved?
- What awards, certifications, and training support his experience?
- Can he connect AI models to actual services?

Because the owner is applying for entry-level AI Engineer positions, **projects and demonstrated outcomes should be treated as the main evidence of capability.**

---

## 2. Owner Profile

### Name

- Korean: 조형택
- English: HyungTaek Jo

### Target Role

**AI Engineer**

### Portfolio Links

- GitHub: https://github.com/JoHyungTaek
- Blog: https://blog.naver.com/circle415

### Career Direction

HyungTaek Jo aims to build AI-powered services by connecting models, data, retrieval systems, APIs, and application infrastructure.

Core technical interests include:

- AI Agent
- RAG
- Embedding
- Vector Search
- Search / Recommendation
- Multimodal AI
- Computer Vision
- AI Service Development
- LLM Application Development

Do not position him as only a model researcher.

The main positioning should be:

> An AI Engineer who builds AI functionality into usable services and improves systems through data, retrieval, model integration, and experimentation.

---

## 3. Portfolio Strategy

This portfolio belongs to an entry-level AI Engineer.

Therefore, the site must NOT focus mainly on years of experience.

Instead, emphasize:

1. Projects
2. Technical problem solving
3. Measurable project outcomes
4. Awards
5. Certifications
6. AI education
7. Actual implementation experience
8. GitHub repositories and technical documentation

The portfolio should make projects function as evidence similar to professional work experience.

---

## 4. Content Priority

Use the following priority when deciding what should visually stand out.

### Priority 1 — Projects

Projects are the most important content on the site.

Each major project must show:

- Project goal
- Problem definition
- Owner's role
- Technical architecture
- AI models / technologies
- Important implementation decisions
- Problems encountered
- How those problems were solved
- Experimental results
- Performance improvement
- Final outcome
- GitHub repository
- Screenshots or architecture diagrams when available

Avoid project cards that only show:

> Python / PyTorch / React / FastAPI

Technology badges alone are not evidence of capability.

Instead, explain how those technologies were used.

### Priority 2 — Results & Achievements

Quantifiable results should be visually emphasized when verified.

Examples:

- Accuracy
- AUC
- F1 Score
- Retrieval performance
- Ranking performance
- Model improvement
- Number of experiments
- Dataset size
- Reduction in errors
- Award received

Never fabricate numbers.

If a value cannot be verified from a repository, notebook, README, experiment log, or other source, do not present it as fact.

### Priority 3 — Awards

Awards should be clearly visible because they provide external validation of project and training performance.

Known awards and achievements:

#### KT AIVLE School

- KT AIVLE Big Project 우수상
- KT AIVLE 우수수료생 — Dean's List
- KT AIVLE 우수 에이쁠 활동증서

These should not be hidden at the bottom of the website.

Create a dedicated **Achievements** section.

### Priority 4 — Certifications

Known certifications:

- 정보처리기사
- SQLD
- AICE Associate

Certifications should support the portfolio rather than dominate it.

Use a clean card or badge layout.

---

## 5. Previous Work Experience

### 협진통신㈜

Period:

**2024.02 – 2025.09**

Duration:

**1 year 8 months**

Role:

- 기술엔지니어
- 통신지원

This was a communications/network-related engineering role before transitioning toward AI engineering.

Do not artificially describe this experience as AI work.

If included on the portfolio, focus on transferable engineering strengths such as:

- technical troubleshooting
- infrastructure understanding
- field engineering
- communication
- responsibility
- working with real operational environments

Keep this section concise because the main portfolio target is AI Engineer.

---

## 6. AI Education

### KT AIVLE School

Period:

**2025.09 – 2026.03**

Track:

**AI Developer**

Duration:

Approximately 6 months

Important outcomes:

- Big Project 우수상
- 우수수료생 — Dean's List
- 우수 에이쁠 활동증서

This section should connect education directly to the projects built during the program.

Avoid presenting AIVLE only as classroom education.

Emphasize:

- project-based development
- AI service implementation
- team collaboration
- model application
- backend / frontend integration
- AI API development

---

## 7. Major Projects

The following projects should form the core of the portfolio.

---

### Project 1 — NuriSori

#### Project Name

**NuriSori**

Alternative description:

**UCS AI Sound Platform**

#### Project Overview

An AI-powered platform for:

- image-to-sound matching
- automatic UCS sound naming standardization
- AI sound generation
- multimodal AI functionality
- chatbot-based assistance

The main idea is to help users find or generate appropriate sound effects from images or textual descriptions.

#### Core Problems

Sound production workflows involve several challenges:

- Finding appropriate sound effects manually is time-consuming.
- Different sound file naming conventions make asset management difficult.
- Visual content does not directly map to sound assets.
- Large sound libraries require effective search and retrieval.

NuriSori attempts to solve these problems with multimodal AI and retrieval.

#### AI Pipeline

Possible flow:

Image

↓

Image understanding / caption generation

↓

Semantic representation

↓

Embedding-based sound retrieval

↓

Candidate ranking

↓

LLM re-ranking

↓

Recommended sound result

This pipeline should be visualized as an architecture or flow diagram.

#### AI Technologies

##### BLIP

Used for:

- image caption generation
- extracting semantic descriptions from images

##### CLIP

Used for:

- image / text semantic similarity
- embedding-based retrieval
- matching visual content to textual or sound descriptions

##### Vision LLM

Used for:

- deeper visual interpretation
- image analysis

##### LLM Re-ranking

Used after initial retrieval to improve candidate ordering.

The portfolio should explain that embedding retrieval provides candidate results and the LLM can perform a second-stage semantic evaluation.

##### RAG

Used in chatbot-related functionality.

##### UCS Standardization

LLM-based processing is used to convert sound names into a standardized UCS-style naming format.

#### Service Architecture

##### AI Server

- Python
- FastAPI
- PyTorch
- Transformers
- sentence-transformers
- CLIP
- BLIP
- laion-CLAP
- librosa

##### Backend

- Java 17
- Spring Boot
- Spring Data JPA
- Spring Security
- JWT
- OAuth2
- MySQL
- AWS S3

##### Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- WaveSurfer.js

##### Infrastructure / External Services

- AWS S3
- Presigned URL
- ElevenLabs
- RunwayML
- Whisper
- OAuth providers

Only display technologies that are actually confirmed in the repository.

#### Important Engineering Story

The portfolio should emphasize that this was not just an isolated AI notebook.

The AI functionality was connected to:

- FastAPI AI server
- Spring Boot backend
- React frontend
- storage
- authentication
- external AI APIs

This project should demonstrate:

> Ability to connect AI models with a real service architecture.

#### Performance / Results

The project has had experiments involving:

- embedding retrieval
- candidate ranking
- LLM re-ranking

There are previous development records indicating that re-ranking improved retrieval quality.

However:

**Do not publish any numerical improvement until the exact value is verified from the repository, experiment output, documentation, or evaluation records.**

When verified, display the result prominently.

Recommended presentation:

Before

`Embedding Retrieval`

↓

After

`Embedding Retrieval + LLM Re-ranking`

↓

`Performance improvement: XX% → XX%`

#### Project Detail Page

The NuriSori project page should contain:

1. Overview
2. Problem
3. My Role
4. Architecture
5. AI Pipeline
6. Main Technologies
7. Technical Challenges
8. Solutions
9. Results
10. Screenshots
11. GitHub Link

---

### Project 2 — AI Teacher Agent

#### Project Name

**AI Teacher Agent**

Repository:

https://github.com/JoHyungTaek/ai-agent-project

#### Overview

A multimodal LLM Agent system that automatically generates lecture content based on PowerPoint material.

Main concept:

> PPT-based automated lecture generation using LLM and multimodal AI.

#### Portfolio Positioning

This project should demonstrate experience with:

- AI Agent systems
- LLM applications
- multimodal processing
- document-based AI
- automated content generation

#### Important Topics to Explain

Where supported by the repository, explain:

- how PPT content is extracted
- how content is divided or chunked
- how prompts are constructed
- whether RAG is used
- whether multiple agents are used
- how the lecture-generation process is structured
- what outputs the system generates
- how the different AI components interact

Do not invent an agent architecture that does not exist in the repository.

#### Project Detail Page

Recommended structure:

1. Problem
2. Why AI Agent
3. Input data
4. Processing pipeline
5. Agent / LLM architecture
6. Output generation
7. Technical challenges
8. Results
9. GitHub

---

### Project 3 — Deepfake Detector

#### Project Name

**Deepfake Detector**

This project focuses on detecting AI-generated or manipulated images.

The project should be presented as an experimental AI engineering project rather than only a classification notebook.

#### Main Technical Approach

Feature extraction using pretrained vision models.

##### CLIP

Model:

`openai/clip-vit-base-patch32`

##### DINOv2

Model:

`facebook/dinov2-base`

Embeddings are extracted from images and used as features.

#### Classification

Classifiers experimented with include:

- Logistic Regression
- MLP

Multiple model outputs are combined using ensemble methods.

#### Evaluation

Possible metrics:

- ROC-AUC
- Accuracy
- Precision
- Recall
- F1 Score
- False Positive
- False Negative

The project also experiments with classification thresholds.

Do not publish an evaluation score unless it matches the final notebook or repository result.

#### Most Important Project Story

The most important part of this project is not just the classifier.

Emphasize the **data problem**.

During development, insufficient and unbalanced data caused incorrect predictions such as:

- real images being predicted as fake
- AI-generated images being predicted as real

This demonstrated that model performance depends heavily on:

- dataset size
- data diversity
- class balance
- domain distribution
- image characteristics

This experience led to additional work involving:

- collecting more real images
- collecting more AI-generated images
- examining False Positives
- examining False Negatives
- tuning classification thresholds
- comparing multiple embedding models
- using ensemble predictions

This is a strong AI Engineer story because it shows understanding that:

> model architecture alone does not determine system performance; data quality and distribution are equally important.

#### Experiment Presentation

Do not simply display a final accuracy score.

Show the development process visually.

Example:

##### Stage 1

Small dataset

↓

Real / Fake misclassification

##### Stage 2

Error analysis

↓

FP / FN inspection

##### Stage 3

Dataset expansion

↓

More diverse real and AI-generated images

##### Stage 4

CLIP + DINOv2 embeddings

↓

Multiple classifiers

##### Stage 5

Ensemble + threshold tuning

↓

Final evaluation

This makes the project more valuable than showing only one metric.

#### Final Metrics

Before publishing the portfolio, inspect the latest notebook and verify:

- final AUC
- final Accuracy
- final Precision
- final Recall
- final F1
- final threshold
- dataset size

Only verified metrics may appear on the website.

---

### Project 4 — AI Book Manager

Repository:

https://github.com/JoHyungTaek/ai-book-manager-repo

This project may be included as a secondary project.

Do not give it the same visual importance as NuriSori, AI Teacher Agent, or Deepfake Detector unless its repository contains substantial technical results.

Use it to demonstrate additional AI service development experience.

---

## 8. Project Card Design

Major project cards should show more than technology names.

Recommended card format:

### Project Name

One-line description.

**Problem**

Short explanation of what problem was addressed.

**Key Contribution**

What HyungTaek Jo implemented or solved.

**Result**

One verified metric or outcome.

**Tech**

Important technologies only.

Buttons:

- View Project
- GitHub

---

## 9. Project Detail Design

Each major project should preferably have a dedicated detail page or modal.

Recommended structure:

### Overview

What was built?

### Problem

What problem motivated the project?

### Role

What did HyungTaek Jo implement?

### Architecture

How does the system work?

### AI / ML

What models and AI techniques were used?

### Challenge

What technical problem occurred?

### Solution

How was it solved?

### Result

What improved?

### Lessons Learned

What engineering insight was gained?

### Repository

GitHub link.

---

## 10. Skills

Skills should not be presented as a giant badge collection.

Organize them by engineering function.

### AI / Machine Learning

Candidate skills:

- Python
- PyTorch
- Transformers
- scikit-learn
- NumPy
- Pandas
- CLIP
- BLIP
- DINOv2
- sentence-transformers

### LLM / Retrieval

Candidate skills:

- LLM
- RAG
- Embedding
- Vector Search
- Prompt Engineering
- Re-ranking
- Multimodal LLM
- AI Agent

Only show technologies actually used in projects.

### Backend

Candidate skills:

- FastAPI
- Spring Boot
- Java
- REST API
- Spring Data JPA
- Spring Security
- JWT
- OAuth2

### Frontend

Candidate skills:

- React
- TypeScript
- Vite
- Tailwind CSS

Frontend should not be positioned as the owner's primary expertise.

It supports the story that he can build complete AI services.

### Database / Storage

Candidate skills:

- MySQL
- AWS S3
- Vector database technologies when verified

### AI / External APIs

Candidate technologies:

- OpenAI API
- ElevenLabs
- RunwayML
- Whisper

Only include APIs that were actually integrated.

### Tools

Candidate tools:

- Git
- GitHub
- VS Code
- Google Colab
- Docker

---

## 11. Skill Presentation Rules

Do NOT use meaningless percentage bars such as:

Python 95%

PyTorch 90%

React 85%

These percentages have no reliable meaning.

Instead use categories such as:

### Primary

Technologies repeatedly used in major projects.

### Experienced

Technologies used to implement project functionality.

### Familiar

Technologies explored or used in smaller scope.

Or simply organize technologies by function without rating them.

---

## 12. Achievements Section

Create a dedicated section titled:

**Achievements**

Recommended content:

### KT AIVLE Big Project 우수상

2026.03

Highlight this as a major external project achievement.

### KT AIVLE 우수수료생

Dean's List

2026.03

### KT AIVLE 우수 에이쁠 활동증서

2026.03

Use concise descriptions.

Where certificate images are available, optionally provide a detail modal.

---

## 13. Certifications Section

Create a section titled:

**Certifications**

Include:

### 정보처리기사

2024.09

### SQLD

2024.09

### AICE Associate

2026.01

Avoid over-explaining certifications.

---

## 14. Recommended Website Structure

Use the following page flow.

### 1. Hero

Show:

**HyungTaek Jo**

**AI Engineer**

Suggested supporting sentence:

> Building AI into real services through models, data, retrieval, and system integration.

Provide:

- GitHub
- Blog
- Projects CTA

Do not use generic phrases such as:

> Passionate developer changing the world with AI.

Avoid cliché portfolio language.

---

## 15. About

Keep the About section relatively short.

It should communicate:

- transition into AI engineering
- interest in building usable AI systems
- hands-on project experience
- focus on AI service implementation

Do not write a long autobiography.

---

## 16. Featured Projects

This should be the largest section of the home page.

Recommended order:

1. NuriSori
2. AI Teacher Agent
3. Deepfake Detector
4. AI Book Manager

NuriSori should receive the strongest visual treatment because it demonstrates:

- multimodal AI
- retrieval
- AI API
- backend
- frontend
- infrastructure
- real service integration

---

## 17. Achievements

Immediately after or near Projects.

Show:

- Big Project Award
- Dean's List
- 우수 에이쁠 활동증서

The visual hierarchy should make external recognition noticeable.

---

## 18. Skills

Display skill categories.

Do not let the skill section visually overpower Projects.

---

## 19. Experience

Timeline format is appropriate.

Recommended order:

### KT AIVLE School

2025.09 – 2026.03

AI Developer Track

### 협진통신㈜

2024.02 – 2025.09

Technical Engineer

---

## 20. Certifications

Display the three verified certifications.

---

## 21. Contact

Provide:

- GitHub
- Blog
- Email

Do not expose unnecessary personal information such as:

- home address
- phone number
- date of birth

even if that information exists in the resume.

The public portfolio should minimize unnecessary personal information.

---

## 22. Visual Style

The desired visual style is:

- modern
- clean
- technical
- minimal
- professional
- developer-oriented

Avoid:

- overly flashy animations
- excessive gradients
- large decorative 3D objects
- excessive glassmorphism
- generic AI-generated illustrations
- excessive floating particles
- meaningless skill charts

The design should make recruiters focus on:

**Projects → Results → Engineering Process**

rather than visual effects.

---

## 23. Color / UI Direction

Use a restrained palette.

Dark mode or a clean light/dark combination is acceptable.

Use visual emphasis for:

- performance metrics
- achievements
- project titles
- key technologies

Cards should have clear spacing and strong hierarchy.

---

## 24. Responsive Design

The website must work properly on:

- desktop
- tablet
- mobile

Project cards and architecture diagrams must remain readable on mobile.

---

## 25. Writing Style

Portfolio copy should feel like it was written by an engineer.

Preferred style:

- concise
- factual
- concrete
- result-oriented
- technical where necessary

Avoid expressions such as:

- 혁신적인 AI 개발자
- AI로 세상을 변화시키는
- 무한한 가능성을 믿는
- 단순히 ~을 넘어
- 기술을 통해 새로운 가치를 창출
- 끊임없이 성장하는 개발자

unless there is a specific reason.

Prefer:

Problem

→ Approach

→ Implementation

→ Result

---

## 26. Metric Design

Verified metrics should be displayed visually.

Examples:

### Deepfake Detector

`AUC`

`Accuracy`

`F1`

### NuriSori

`Retrieval performance`

`Re-ranking improvement`

### Project

`Award`

Metrics should appear near the project explanation, not in a disconnected statistics section.

---

## 27. Evidence First

Whenever possible, support portfolio claims with:

- GitHub repository
- notebook output
- screenshots
- evaluation tables
- architecture diagrams
- awards
- certificates
- demo images

The site should communicate:

> This person actually built and tested these systems.

---

## 28. Source-of-Truth Policy

Never invent:

- performance metrics
- project responsibilities
- technologies
- awards
- certifications
- dataset sizes
- user counts
- model accuracy
- business impact

When information is missing:

1. inspect the GitHub repository
2. inspect README
3. inspect notebooks
4. inspect experiment logs
5. inspect project documentation

If still unavailable, omit the claim.

---

## 29. Repository Inspection Rule

Before creating detailed project descriptions, inspect the relevant repository whenever possible.

Important repositories:

### AI Teacher Agent

https://github.com/JoHyungTaek/ai-agent-project

### AI Book Manager

https://github.com/JoHyungTaek/ai-book-manager-repo

### Main GitHub

https://github.com/JoHyungTaek

NuriSori may exist in a team repository.

Use repository contents as the source of truth for implementation details.

---

## 30. Important Portfolio Message

A recruiter should leave the website with the following impression:

> HyungTaek Jo is an entry-level AI Engineer who has already experienced the full process of building AI-powered services: preparing data, applying models, evaluating performance, solving errors, developing APIs, and connecting AI functionality to applications.

This message should emerge naturally from the projects.

Do not simply write this sentence repeatedly.

---

## 31. Homepage Final Structure

Recommended final structure:

```text
Navbar

Hero
├── HyungTaek Jo
├── AI Engineer
├── Short positioning statement
├── GitHub
├── Blog
└── View Projects

About

Featured Projects
├── NuriSori
├── AI Teacher Agent
├── Deepfake Detector
└── AI Book Manager

Achievements
├── KT AIVLE Big Project 우수상
├── Dean's List
└── 우수 에이쁠 활동증서

Skills
├── AI / ML
├── LLM / Retrieval
├── Backend
├── Frontend
└── Tools

Experience
├── KT AIVLE School
└── 협진통신㈜

Certifications
├── 정보처리기사
├── SQLD
└── AICE Associate

Contact

Footer
```

---

## 32. Before Publishing

Before final deployment, verify:

- [ ] NuriSori final evaluation metrics
- [ ] NuriSori exact personal contribution
- [ ] Deepfake final AUC
- [ ] Deepfake final accuracy
- [ ] Deepfake final F1 score
- [ ] Deepfake final dataset size
- [ ] Deepfake final classification threshold
- [ ] AI Teacher Agent architecture
- [ ] AI Teacher Agent exact personal contribution
- [ ] GitHub repository links
- [ ] project screenshots
- [ ] award names
- [ ] certification dates

Do not leave fake placeholder metrics such as `XX%` on the production site.

If a metric is not verified, redesign the section without that metric.

---

## 33. Implementation Goal for Codex

When asked to build this portfolio:

1. Read this entire AGENTS.md first.
2. Inspect existing repository files.
3. Preserve existing working functionality.
4. Build a polished responsive portfolio.
5. Give highest visual priority to projects.
6. Use real project information.
7. Emphasize technical challenges and outcomes.
8. Include awards and certifications.
9. Avoid generic developer portfolio templates.
10. Do not invent information.
11. Keep the code maintainable.
12. Build reusable components.
13. Optimize for GitHub Pages deployment.
14. Make project data easy to update later.
15. Separate portfolio content from presentation components when practical.

The final result should feel like a real AI Engineer portfolio, not a generic template with the owner's name inserted.
