# 🎨 ExcaliDraw AI Version

An AI-powered version of Excalidraw that allows users to create, edit, and visualize diagrams using natural language prompts. The application combines the simplicity of hand-drawn diagrams with the power of Artificial Intelligence to automate diagram generation and enhance productivity.

## 🚀 Features

* ✨ AI-generated diagrams from text prompts
* 🎨 Interactive Excalidraw canvas
* 🔄 Real-time diagram editing
* 📤 Export diagrams as PNG, SVG, or JSON
* 🤖 AI-assisted flowchart creation
* 📱 Responsive user interface
* 🌙 Dark and Light mode support
* 💾 Auto-save functionality
* 🔍 Zoom and pan controls
* 🔗 Shareable diagram links

## 🛠️ Tech Stack

### Frontend

* React.js
* TypeScript
* Tailwind CSS
* Excalidraw

### Backend

* Node.js
* Express.js

### AI Integration

* OpenAI API / Gemini API / Custom LLM

### Database (Optional)

* MongoDB
* Firebase

## 📂 Project Structure

```bash
ExcaliDraw-AI-VERSION/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── hooks/
│   ├── utils/
│   └── App.tsx
│
├── server/
│   ├── routes/
│   ├── controllers/
│   └── services/
│
├── package.json
├── tsconfig.json
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/Pranshu51/ExcaliDraw-AI-VERSION.git
```

### Navigate to Project

```bash
cd ExcaliDraw-AI-VERSION
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

The application will run on:

```bash
http://localhost:5173
```

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```env
VITE_OPENAI_API_KEY=your_api_key
VITE_GEMINI_API_KEY=your_api_key
```

## 🤖 How It Works

1. User enters a text prompt.
2. AI interprets the prompt.
3. Structured diagram data is generated.
4. Excalidraw renders the diagram automatically.
5. Users can further edit and customize the generated diagram.

### Example Prompt

```text
Create a flowchart for an online shopping system.
```

### AI Generated Output

```text
Start
  ↓
Browse Products
  ↓
Add to Cart
  ↓
Payment
  ↓
Order Confirmation
  ↓
End
```

## 📸 Screenshots

Add screenshots here:

```markdown
![Home Page](screenshots/home.png)
![AI Diagram Generation](screenshots/ai-generation.png)
```

## 🔮 Future Enhancements

* Voice-to-diagram generation
* Multi-user collaboration
* AI diagram optimization
* UML diagram generation
* Database schema generation
* Architecture diagram generation
* Project documentation visualization

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Create a Pull Request

## 🐛 Issues

If you find a bug or have a feature request, please open an issue in the repository.

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Pranshu Tiwari**

* GitHub: https://github.com/Pranshu51

---

⭐ If you found this project useful, consider giving it a star on GitHub.
