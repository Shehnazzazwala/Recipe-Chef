# Recipe-Chef
this is the kaggle notebook of the ai recipe chef- web interface was made in gradio as well as it has the new updated ui where the history stays forever of generated recipes , they are stored in google cloud spreadsheets.


# 👨‍🍳 AI Master Chef: Fine-Tuned Recipe Generator
A specialized LLM application that generates structured, professional recipes using a fine-tuned Qwen-2.5-3B model.

### 🌟 Project Highlights
* **Model:** Fine-tuned **Qwen-2.5-3B** using **QLoRA (4-bit)** for high-efficiency GPU performance.
* **Evaluation:** Achieved a **70% ROUGE-L score**, matching professional culinary structures.
* **Architecture:** Implemented a two-step generation logic (Title -> Recipe) with a custom "Surgical Slicer" to prevent prompt leaking and hallucinations.
* **Interface:** Built a wide-layout Gradio UI featuring a Chef's Sidebar, Dietary Restrictions, and Session History.

### 🛠️ Technical Stack
* **Language:** Python
* **Libraries:** Transformers, PEFT, BitsAndBytes, Accelerate, Gradio
* **Dataset:** Professional Culinary Instruction Dataset

### 📊 Performance
The model was evaluated against unseen ingredients, demonstrating 70% accuracy in instructional sequencing and vocabulary overlap.
