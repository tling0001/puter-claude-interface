# 🤖 Self-Hosted Claude AI Interface

A polished, self-hosted web interface for Anthropic's Claude AI. This project runs entirely within your browser, using **Puter.js** for secure and direct access to the Claude API. Please note that while the interface is self-hosted, users are responsible for any usage costs associated with their Puter.js or Claude API accounts.

---

### ✨ Live Demo


![Demo GIF of the Claude UI in action](demo.gif)

---

### 🚀 Key Features

*   ✅ **Seamless Claude API Interaction via Puter.js.**
*   🎨 **Polished UI:** A clean, modern interface inspired by the official Claude UI, with light and dark mode support.
*   📄 **Artifact Generation:** Automatically renders code blocks into beautiful, interactive "artifact" canvases with syntax highlighting, copy, download, and even an HTML preview feature.
*   💬 **Streaming Responses:** Watch Claude's responses appear in real-time, just like the official experience.
*   📂 **Local Chat History:** Remembers your recent conversations in your browser's local storage.
*   🔐 **Secure Authentication:** Handles Puter.js authentication directly in the browser with a clear, user-friendly flow.

---

### ❓ How It Works

This interface utilizes the official and legitimate **Puter.js** library for secure interaction with the Claude API. Upon first use, the application will prompt for a one-time authentication with your Puter account. This process securely connects the web app to your designated Claude API access, maintaining security and compliance.

---

### ▶️ Getting Started (How to Run)

Because browsers have security rules (CORS), you cannot simply open the `index.html` file directly. You must run it from a **local web server**. I've made this easy for you.

### ✅ Prerequisites

This project has minimal dependencies, making setup straightforward. You only need:

1.  **🐍 Python 3:**
    *   This is **only** required to run the simple local web server. The application itself is 100% JavaScript.
    *   **No `pip` packages are needed.** The `http.server` module is included with Python by default.
    *   Most macOS and Linux systems have Python pre-installed. For Windows, you can download it from [python.org](https://www.python.org/downloads/).

2.  **🌐 A Modern Web Browser:**
    *   Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari.

That's it! There are no other libraries or frameworks to install.

#### For Windows Users (Easiest Method):

1.  **Download:** Download this project as a ZIP file and extract it.
2.  **Run the Script:** Simply double-click the `run_server.bat` file.
3.  **Open:** A command prompt will appear, and your default web browser will automatically open to `http://localhost:8000`. That's it!

#### For Mac / Linux / Other Users:

1.  **Download:** Download this project as a ZIP file and extract it.
2.  **Open Terminal:** Open your terminal or command prompt and navigate into the project folder.
3.  **Run Server:** Run the following command:
    ```bash
    python -m http.server 8000
    ```
4.  **Open Browser:** Open your web browser and go to the address `http://localhost:8000`.

**First Use:** Upon sending your first message, a popup will appear requesting authentication with Puter. **Please allow this popup** to enable AI access.

---

### ❤️ Support The Project

If you find this tool useful, please consider making a small donation to support future development. Thank you!

<a href="https://www.paypal.com/paypalme/itkcartoons" target="_blank">
  <img src="https://img.shields.io/badge/Donate-PayPal-blue.svg?logo=paypal&style=for-the-badge" alt="Donate with PayPal">
</a>

---

### 🛠️ Tech Stack

*   **Core:** Vanilla JavaScript (ES6+), HTML5, CSS3
*   **API Integration:** Puter.js SDK (`@puter.com/v2`)
*   **Development:** No frameworks, just pure, efficient code.

---

### 📄 License

This project is licensed under the **MIT License**.
