# TikZify: AI-Powered LaTeX Diagram Generator

**TikZify** is an AI-powered assistant that converts plain English descriptions into professional-quality LaTeX diagrams using TikZ. Designed for academic and technical users, it eliminates the need to manually write TikZ code by generating publication-ready output through conversational prompts.

---

## 🚀 Features

- Generate LaTeX diagrams with natural language prompts  
- Built on IBM Watsonx.ai using Granite-3.3-8B-Instruct model  
- Real-time refinement using plain-English follow-up instructions  
- Outputs clean, compilable TikZ code for LaTeX documents  
- Domain-restricted agent – responds only to diagram-specific queries  
- Lightweight deployment on IBM Cloud Lite (free tier)

---

## 🧠 How It Works

1. **Input:** User provides a diagram description  
   _Example: “Draw a flowchart for CNN architecture”_
2. **Processing:** IBM Watsonx.ai + Granite model interprets the prompt  
3. **Output:** TikZify returns valid LaTeX TikZ code  
4. **Refinement:** User can add steps like “Add a Softmax layer after ReLU”

---

## 📋 Example Prompts

```Draw a flowchart: Load → Clean → Train → Evaluate```
```Create a tree diagram with root 'Start' branching to A and B```
```Make all nodes circular```
```Add a label to the second block```

---

## 🔧 Tech Stack

- IBM Watsonx.ai Studio  
- IBM Granite-3.3-8B-Instruct (LLM)  
- LaTeX + TikZ  
- LangGraph (agent orchestration)  
- Python (deployment & testing)  
- IBM Cloud Lite

---

## 👥 Target Users

- Researchers and academic writers  
- Graduate and PhD students  
- Professors and technical educators  
- LaTeX beginners  
- Open-source technical contributors  

---

## 🛣️ Future Roadmap

- Live preview of TikZ output within web interface  
- Support for PGFPlots and data-driven charts  
- Voice-to-TikZ generation  
- Diagram template gallery  
- Overleaf integration  

---

## 🧪 Getting Started

_TikZify is currently deployed inside IBM Watsonx.ai Studio._

To build or customize:

1. Log in to [IBM Cloud Lite](https://cloud.ibm.com)  
2. Launch Watsonx.ai Studio  
3. Create a new AI agent using **Granite-3.3-8B-Instruct**  
4. Configure system prompt to limit the domain to TikZ diagram generation  
5. Test in preview panel with sample prompts  
6. Deploy using Streamlit, web widget, or a custom UI  

---

## 📷 Screenshots

_(Insert images of input prompt, TikZ output code, and rendered PDF diagrams here)_

---

## 🙋 About the Author

Created by **Shreya Patel**  
AI & Cloud Intern — IBM SkillsBuild & Edunet Foundation  
For academic use and research enhancement in LaTeX authoring
