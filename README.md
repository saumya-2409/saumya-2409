# Hi, I'm Saumya 👋

I build full-stack products and LLM-powered workflows. I like turning a slow, manual process into something that works, and I care about the unglamorous parts: validation, fallbacks, and error handling.

📍 Based in India · 🎓 B.Tech CSE, Graphic Era University (2026) · Qualified **GATE 2026** (CS & DA)

📫 Reach me:
✉️ [saumyagarg.2409@gmail.com](mailto:saumyagarg.2409@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/saumya-garg-1ab39224b/)

---

## What I'm doing now
- Training in full-stack (MERN) development and AI-assisted software development.
- Looking for a **Software Engineer / AI Engineer** role where I can ship full-stack features and LLM workflows with a product team.
- Re-building a MERN app by hand (no AI assistance) to sharpen my fundamentals. Repo coming soon.

## What I work with

| | |
|---|---|
| **Full-stack** | JavaScript, React, Next.js, Node.js, Express, MongoDB, SQL, REST APIs |
| **AI / LLM** | Python, RAG, embeddings (SBERT), prompt design with structured outputs, LLM agent workflows, evaluation (F1, NMI, ARI) |
| **Tools** | Git, Postman, Jira, Slack webhooks, Streamlit, Flask |
| **Also** | C/C++, scikit-learn, pandas, AI-assisted development (Claude, Copilot) |

---

## Projects

### 🔬 AI Academic Research Assistant
A research-paper discovery tool: type a topic, get papers grouped by theme.
- Pulls up to ~300 papers per search from 6 academic APIs in parallel, then de-duplicates them.
- Ranks and clusters with SBERT embeddings, UMAP and Ward clustering, with LLM-generated cluster labels.
- Built a **4-stage fallback** (LLM → KeyBERT → c-TF-IDF → frequency) so a failed model call never breaks the result.
- Evaluated against 6 baselines (Silhouette, NMI, ARI, F1, precision, recall), +8% over baseline.
- Exports to Excel/BibTeX. **Stack:** Python, SBERT, scikit-learn, LLaMA 3.1-8B, Streamlit, Groq API.
- 👉 [Repo](ADD-LINK) · [Demo](ADD-LINK-IF-ANY)

### 🧩 AI Chrome Extension ([chrome-extension-zeta](https://github.com/saumya-2409/chrome-extension-zeta))
Highlight text on any page, press Ctrl/Cmd+I, and get an AI answer in a popup. Flask backend, OpenAI API, response caching, and clean error handling in v2.0. It started as a prototype from my internship.

### 🧠 [Depression & Anxiety Detection in Students](https://github.com/saumya-2409/Depression-and-Anxiety-Detection-In-Students)
Classified student depression/anxiety severity from the DASS-21 questionnaire (Naive Bayes, Random Forest, KNN: **92% accuracy with KNN**, 88% with Random Forest). Winner, GEU BuildFest.

### 📄 [Automated Resume Builder](https://github.com/saumya-2409/Automated_Resume_Builder)
A responsive web app to fill in a form and download a clean resume as PDF. [Live demo](https://automated-resume-builder.vercel.app/)

### 🌱 Early-stage startup work: JityAI
Part-time contributor on the founding team of JityAI (incubated at JITO Foundation) from Jan to Aug 2026. I supported the lead engineer on agent-based LLM workflows, testing and debugging AI-generated code.

### 🏥 Mpox skin lesion classification (team research project)
During my research internship at GEU I worked with a team of three on the early version of an Mpox skin-lesion classifier, including the Streamlit/Flask prototype. The dataset and later versions are maintained by Priya Dhaila: [monkeypox-skin-lesion2.0](https://github.com/Priyadhaila01/monkeypox-skin-lesion2.0).

---

## Work I'm proud of

At **Cvent** (IT intern, Jan–Jul 2025) I built Python automation for vendor-risk intake that connects Jira and AuditBoard, cutting turnaround from hours to near real-time. I also added Slack notifications (about 90% lower ticket-to-action latency) and LLM-based analysis of security questionnaires.

---

## Let's talk

I'm happy to chat about full-stack, LLM workflows, or interesting problems. Email me, or say hi on LinkedIn.

*Fun fact: I bake code and cookies one commit at a time 🍪*

---
Thanks for stopping by! ✨
