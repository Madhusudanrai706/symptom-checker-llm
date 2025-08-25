# Symptom Checker (React + Hugging Face LLM)

A demo web app where users enter symptoms in a React frontend.  
A Node/Express backend forwards the request to a Hugging Face LLM model, which returns possible diagnoses and recommended next steps.

⚠️ **Disclaimer**: This project is for **educational/demo purposes only**.  
It is **not medical advice** and must not be used for clinical decision-making.



symptom-checker-llm/
├── frontend/              # React app (your symptom checker UI)
│   ├── src/
│   │   └── App.tsx        # Code I provided in canvas
│   ├── package.json
│   └── ...
├── backend/               # Node/Express Hugging Face API
│   ├── server.js
│   ├── package.json
│   └── .env.example
├── README.md
└── LICENSE


---

## Features
- 🖥️ React frontend (Tailwind + shadcn/ui + framer-motion)
- 🤖 Hugging Face LLM backend via Inference API
- ✅ Strict JSON schema enforced with [zod](https://zod.dev)
- ⚡ Confidence bars, red-flag alerts, recommended next steps

---

