# 🧠 TikZify: Your AI Assistant for LaTeX Diagrams

**TikZify** is an AI-powered assistant that generates professional-quality LaTeX diagrams from plain English prompts. Built on **IBM Watsonx.ai** and the **Granite-3.3-8B-Instruct** foundation model, TikZify helps researchers, students, and academic writers produce publication-ready TikZ code without needing to manually write LaTeX.

---

## 🧩 Problem Statement

Creating diagrams in LaTeX using TikZ is complex and time-consuming, especially for users unfamiliar with its syntax. This leads to inefficiencies in academic writing and can discourage non-experts from using LaTeX for technical documentation.

---

## 💡 Proposed Solution

**TikZify** bridges the gap by allowing users to describe diagrams in simple natural language. The AI agent then generates clean, compilable TikZ code in real time, supporting follow-up refinements and eliminating manual coding complexity.

---

## 🛠️ Technologies Used

- IBM Watsonx.ai Studio  
- IBM Granite-3.3-8B-Instruct (Foundation Model)  
- LaTeX and TikZ  
- ReAct Architecture  
- LangGraph (for orchestration)  
- Python (for integration & deployment)  
- Markdown / PDF Preview  
- GitHub Pages / Streamlit (for UI)

---

## ☁️ IBM Cloud Services Used

- IBM Watsonx.ai Studio  
- IBM Cloud Lite Account  
- IBM Granite Foundation Model  
- IBM IAM (Authentication & Access)  

---

## 👥 End Users

- Researchers  
- Graduate and PhD students  
- Professors and academic writers  
- Engineering and CS students  
- LaTeX beginners  
- Technical educators and content creators  
- Open-source documentarians  

---

## 🌟 Wow Factors

- Converts plain English into publication-ready TikZ code  
- Supports real-time refinement via conversational follow-up  
- Strictly domain-focused (ignores unrelated prompts)  
- Removes manual coding effort entirely  
- Runs fully on IBM Cloud Lite using Watsonx tools  
- Clean, demo-ready outputs for live presentations or academic use  

---

## 🔑 Key Features

- Natural language to TikZ code generation  
- Plain-English iterative diagram refinement  
- Clean, LaTeX-compatible output  
- Responds only to diagram-specific prompts  
- Built using IBM’s open-weight LLM  
- Easy integration into academic writing workflows  

---

## 🚀 How It Works

1. **User inputs a prompt**  
   e.g., “Draw a CNN flowchart with input → conv → relu → pool → output”

2. **AI agent processes the request**  
   Watsonx.ai + Granite model understands the intent

3. **TikZ code is generated**  
   Clean LaTeX code appears instantly

4. **User can refine the diagram**  
   e.g., “Add a Softmax layer after the pool layer”

5. **Copy code into any `.tex` file**  
   Compile using Overleaf, VS Code, TeXstudio, etc.

---

## 🖼️ Screenshots & Examples

| Prompt | Generated TikZ Code | Compiled Diagram |
|--------|---------------------|------------------|
| `Draw a simple 3-step flowchart` | `\begin{tikzpicture}...` | ![example](images/flowchart.png) |
| `Create a tree with root A and two branches` | ... | ![example](images/tree.png) |

---

## 💬 Sample Prompts to Try

- "Draw a flowchart: Load → Clean → Train → Evaluate"  
- "Create a triangle with three labeled nodes A, B, and C"  
- "Generate only TikZ code for a CNN block diagram"  
- "Make all blocks circular"  
- "Add a dropout layer after relu"  

---

## 📌 How to Run or Deploy

1. Log in to [IBM Cloud Lite](https://cloud.ibm.com)
2. Launch **Watsonx.ai Studio**
3. Create a new **AI Agent**
4. Use Granite-3.3-8B-Instruct as your foundation model
5. Set up your **system prompt** to restrict and format TikZ responses
6. Test in the **Preview Panel**
7. Deploy via:
   - Streamlit app
   - Web snippet
   - Custom web UI

---

## 🛣️ Future Scope

- Support for sketch-to-TikZ from hand-drawn images  
- Voice-to-diagram input with speech recognition  
- Live preview of TikZ output inside the UI  
- Expansion to PGFPlots and other LaTeX diagram packages  
- Reusable diagram templates and history  
- LaTeX document-aware editing  

---

## 🔗 Useful Links

- [IBM Watsonx.ai](https://www.ibm.com/products/watsonx-ai)  
- [TikZ Documentation](https://tikz.dev)  
- [Overleaf](https://www.overleaf.com)  
- [LaTeX Wikibook – TikZ](https://en.wikibooks.org/wiki/LaTeX/PGF/TikZ)  
- [Granite Models Overview](https://www.ibm.com/blogs/research/2023/10/granite-models/)

---

## 🙌 Acknowledgments

Built with 💙 during the IBM SkillsBuild & IBM Cloud Platform in Emerging Technologies (AI & Cloud) program by **Shreya Patel**.

---

