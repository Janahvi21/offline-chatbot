# 🌐 Llama-Based AI Bot


**Llama-Based AI Bot** is a 🛠️ web-based application that enables 👤 users to interact with Llama models seamlessly, designed with a focus on 🎨 user experience and 🎩 functionality.

---

## 🏆 Features

- **Main Application**: 
  - The core 🔧 functionality resides in `app.py`, which handles the 🔐 application logic using Flask and LangChain Ollama.

- **🔖 Templates**:
  - Located in the `templates` folder, these 🔒 HTML files define the 🕸️ user interface.

- **🗃️ Static Assets**:
  - 🖌️ CSS, 🔦 JavaScript, and 🖼️ images are stored in the `static` folder to ensure a clean separation of 🎨 design and 🔧 functionality.

---

## 🔄 Technologies Used

- **Backend**: 🐍 Python (🏊 Flask)
- **AI Model**: Llama 3.2 via LangChain Ollama
- **Frontend**: 🔖 HTML, 🖌️ CSS, 🔦 JavaScript

---

## 🔧 Setup Instructions

1. 🔀 Clone the repository:
   ```bash
   git clone https://github.com/parassawal/llama-based-ai-bot.git
   ```

2. Navigate to the 🏰 project directory:
   ```bash
   cd llama-based-ai-bot
   ```

3. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # On Windows
   ```

4. Install required 🔎 dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Ensure Ollama is running with Llama 3.2 model:
   ```bash
   ollama pull llama3.2
   ollama serve
   ```

6. Run the 🔐 application:
   ```bash
   python app.py
   ```

7. Access the 🔐 application in your 🔍 browser at:
   ```
   http://localhost:5000
   ```

---

## 🔃 File Structure

```
llama-based-ai-bot/
|
|-- app.py              # Main 🔧 application logic
|-- requirements.txt    # Python dependencies
|-- static/             # Static 🖌️ assets (CSS, JS, 🖼️ images)
|-- templates/          # HTML 🔖 templates
|-- .venv/              # Virtual environment (created during setup)
```

---

