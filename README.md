# 🧬 Symptomap AI

**Symptomap AI** is an interactive, educational tool designed to make learning about human anatomy intuitive and engaging. This application combines a procedurally generated 3D human model with a powerful AI to provide detailed information on demand. Users can explore the model, click on body parts to learn more, and ask specific questions via an integrated AI chat.

**🚀 Live Demo:** [Link to your deployed website]

---

## ✨ Key Features

* **🧍 Interactive 3D Anatomy Model:** A fully interactive human model built from scratch using Three.js.
* **🤖 Dynamic AI Explanations:** Click on any body part or use the chat to get instant, detailed information from Google's Gemini API.
* **🎨 Customizable View:** Switch between male and female models and select from various skin tones to personalize the experience.
* **🗺️ Anatomy Explorer:** A comprehensive list of all body parts, allowing users to quickly navigate and select specific anatomy.
* **🌟 Glow on Hover Effect:** A selective bloom effect provides a beautiful glow on the specific body part the user is hovering over, enhancing visual feedback.
* **✨ Dynamic Particle Background:** A glittering, multi-colored particle system creates an engaging and visually appealing background.
* **📱 Fully Responsive Design:** The layout adapts smoothly to different screen sizes, from mobile devices to large desktop monitors.

---

## 🛠️ Technologies Used

* **Frontend:** HTML5, CSS3, JavaScript (ES6 Modules)
* **3D Graphics:** [Three.js](https://threejs.org/)
* **AI Integration:** [Google Gemini API](https://ai.google.dev/)
* **Post-Processing:** Custom shaders for a selective bloom effect.

---

## 🚀 Setup and Installation

This project is a single-file web application and does not require a complex build process. To run it locally, you can use a simple local server.

1.  **Clone the repository (or download the files):**
    ```bash
    git clone [your-repository-url]
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd symptomap-ai
    ```

3.  **Start a local server.**
    If you have Python installed, you can run:
    ```bash
    # For Python 3
    python -m http.server
    ```
    Or, if you have Node.js, you can use a package like `live-server`:
    ```bash
    npx live-server
    ```

4.  **Open your browser** and navigate to `http://localhost:8000` (or the address provided by your local server).

**🔑 Note on API Key:** To use the AI features, you will need a Google Gemini API key. The code expects this key to be available. For local development, you can paste your key into the `apiKey` constant within the `<script type="module">` tag. For deployment, it is strongly recommended to use a more secure method, such as environment variables or a backend proxy.

---

## ☁️ Deployment

This static site can be deployed to any modern web hosting service that supports static files, such as GitHub Pages, Netlify, or Vercel.

### Deploying with GitHub Pages

1.  Push your code to a GitHub repository.
2.  In your repository's **Settings**, navigate to the **Pages** section.
3.  Under **Build and deployment**, select **Deploy from a branch**.
4.  Choose the `main` branch and the `/ (root)` folder, then click **Save**.
5.  Your site will be deployed to `https://<your-username>.github.io/<your-repository-name>/`.

**⚠️ Security Warning:** Deploying to GitHub Pages will expose your API key if it is hardcoded in the HTML file. For a secure deployment, it is highly recommended to use a service like Netlify or Vercel that supports environment variables and serverless functions to protect your API key.
