# 🧬 Symptomap AI

Symptomap AI is an interactive, educational tool designed to make learning about human anatomy intuitive and engaging. This application combines a procedurally generated 3D human model with a powerful AI to provide detailed information on demand. Users can explore the model, click on body parts to learn more, and ask specific questions via an integrated AI chat.

## 🚀 Live Demo

[https://pavangunnam19.github.io/Symptomap-AI/](https://pavangunnam19.github.io/Symptomap-AI/)

---

## ✨ Key Features

- 🧍 **Interactive 3D Anatomy Model**  
  A fully interactive human model built from scratch using Three.js.

- 🤖 **Dynamic AI Explanations**  
  Click on any body part or use the chat to get instant, detailed information from Google's Gemini API.

- 🎨 **Customizable View**  
  Switch between male and female models and select from various skin tones to personalize the experience.

- 🗺️ **Anatomy Explorer**  
  A comprehensive list of all body parts, allowing users to quickly navigate and select specific anatomy.

- 🌟 **Glow on Hover Effect**  
  A selective bloom effect provides a beautiful glow on the specific body part the user is hovering over, enhancing visual feedback.

- ✨ **Dynamic Particle Background**  
  A glittering, multi-colored particle system creates an engaging and visually appealing background.

- 📱 **Fully Responsive Design**  
  The layout adapts smoothly to different screen sizes, from mobile devices to large desktop monitors.

---

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6 Modules)  
- **3D Graphics**: [Three.js](https://threejs.org/)  
- **AI Integration**: [Google Gemini API](https://ai.google.dev/)  
- **Post-Processing**: Custom shaders for a selective bloom effect

---

## 🚀 Setup and Installation

This project runs as a single `index.html` file. To set it up locally, follow these steps:

### 1. Get the Code

Clone the repository to your local machine:

```bash
git clone https://github.com/pavangunnam19/Symptomap-AI.git
````

### 2. Get Your API Key

The AI features require a Google Gemini API key.
You can generate a free API key at [Google AI Studio](https://aistudio.google.com/app/apikey).

### 3. Add the API Key to the Code

* Open the `index.html` file in a code editor.
* Find the `getAIExplanation` function inside the `<script type="module">` tag.
* Locate the following line and paste your API key:

```js
const apiKey = "PASTE_YOUR_API_KEY_HERE";
```

### 4. Run the Project

Start a local server in the project directory. If you have Python installed, you can run:

```bash
# For Python 3
python -m http.server
```

Then, open your browser and go to:
[http://localhost:8000](http://localhost:8000)

---

## ☁️ Deployment

This static site can be deployed to any modern web hosting service like **GitHub Pages**, **Netlify**, or **Vercel**.

---

## ⚠️ IMPORTANT SECURITY WARNING

The current setup is designed for simplicity and **requires the API key to be placed directly in the `index.html` file**.

> **DO NOT** make your repository public or deploy this project with your API key included if you are concerned about security.

If your API key is exposed, others can use it, which could lead to unexpected charges.

For a secure, production-ready deployment, you should implement a **backend** or **serverless function** to protect your API key. The current method is only recommended for **personal projects or temporary demos**.
