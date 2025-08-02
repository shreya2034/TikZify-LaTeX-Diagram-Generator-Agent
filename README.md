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

_TikZify is currently deployed inside IBM Watsonx.ai Studio._

---

## 📋 Example Prompts

- ```Draw a flowchart: Load → Clean → Train → Evaluate```
- ```Create a tree diagram with root 'Start' branching to A and B```
- ```Make all nodes circular```
- ```Add a label to the second block```

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

## 📷 Screenshots

### 🔹 Setting up..
![Setup image](setup.png)

### 🔹 Agent Configurations & Instructions...
![Agent Instructions](configuration-instructions.png)

### 🔹 Quick Start Questions...
![quick_start_questions](suggested-prompts.png)

### 🔹 Tools used & Testing...
![Tool Used & Testing](tools-used.png)

### 🔹 Deployment & Preview...
![Preview](agent-start.png)
![Deployment](deployment-and-preview.png)

### 🔹 Prompts & Response
![Response](prompt-response.png)
![Off topic prompt response](off-topic-prompt.png)

### 🔹 API References after Deployment...
![api _references](api-endpoints.png)

### 🔹 Resources List...
![resourses_list.jpg](resource-list.png)

---

## 🙋 About the Author

Created by **Shreya Patel** during internship in SkillsBuild & IBM Cloud Platform in Emerging Technologies (AI & Cloud) 
For academic use and research enhancement in LaTeX authoring
