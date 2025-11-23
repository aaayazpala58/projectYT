# 🚀 projectYT

A full-stack project with a **React frontend** and **backend**, supporting drag-and-drop UI components, workflow/pipeline building, and interactive node systems.  
This project is organized into **frontend** and **backend** folders, making it easy to develop each part independently.

---

## 📁 Project Structure

projectYT/
│
├── backend/
│ ├── main.py
│ ├── requirements.txt
│ └── (other backend files…)
│
└── frontend/
├── src/
│ ├── nodes/
│ │ ├── inputNode.js
│ │ ├── outputNode.js
│ │ ├── textNode.js
│ │ ├── llmNode.js
│ │ └── BaseNode.js
│ ├── ui.js
│ ├── App.js
│ ├── store.js
│ └── ...other files
├── package.json
└── public/

---

## ⚙️ Tech Stack

### **Frontend**
- React.js
- ReactFlow (drag/drop workflow)
- Zustand (state management)
- JavaScript (ES6+)
- HTML / CSS

### **Backend**
- Python (FastAPI / Flask or whichever you're using)
- REST APIs
- JSON handling

---

## 🔧 Installation & Setup

### **Clone the Repository**
```bash
git clone https://github.com/aaayazpala58/projectYT.git
cd projectYT
cd frontend
npm install
npm start
http://localhost:3000
cd backend
pip install -r requirements.txt
python main.py
http://127.0.0.1:8000
⭐ Features

✔️ Drag & drop nodes

✔️ ReactFlow-based workflow builder

✔️ Node linking & edge creation

✔️ Zustand-based global state

✔️ Custom node types (Input, Output, Text, LLM)

✔️ Backend API integration

✔️ Clean and modular code
🧪 How to Use

Open the frontend in your browser.

Drag nodes (Input, Output, Text, etc.) onto the canvas.

Connect nodes using edges.

Click Submit Pipeline to get pipeline structure.

Backend receives the structure and processes it.

🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to change.
