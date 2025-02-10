# PiPT_AI: AI-Powered Presentation Generator

## 🚀 Overview
PiPT_AI is a Streamlit-based application that generates professional PowerPoint presentations using Google's Gemini AI. It allows users to create well-structured and visually appealing slides based on a given topic, audience, and purpose.

## ✨ Features
- **AI-Powered Content Generation**: Generates slide content using the Gemini AI model.
- **Customizable Slide Styles**: Users can select font styles, font sizes, and color themes.
- **Dynamic Presentation Structure**: Generates structured slide outlines with engaging content.
- **Downloadable PowerPoint Files**: Generates and provides a `.pptx` file for easy downloading.
- **Interactive UI with Streamlit**: Simple and user-friendly web interface.

## 🛠️ Tech Stack
- **Python**: Core programming language.
- **Streamlit**: Frontend framework for the web application.
- **Google Generative AI (Gemini)**: AI model for generating content.
- **python-pptx**: Library to create PowerPoint presentations.

## 📦 Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/PiPT_AI.git
   cd PiPT_AI
   ```

2. **Create a virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up API Key**:
   - **Local Setup**: Create a `.streamlit/secrets.toml` file and add:
     ```toml
     GOOGLE_API_KEY = "your-google-api-key"
     ```
   - **Streamlit Cloud**: Go to **Settings → Secrets** and add:
     ```
     GOOGLE_API_KEY = your-google-api-key
     ```

## 🚀 Running the App
Run the Streamlit app using:
```bash
streamlit run app.py
```

## 🏗️ How It Works
1. Enter the **presentation topic**, number of slides, purpose, and audience.
2. Choose **font styles, sizes, and color themes** from the sidebar.
3. Click **"Generate Presentation"** and let AI create the slides.
4. Download the **.pptx file** and use it in PowerPoint.

## 🛠️ Troubleshooting
- **API Key Error**: Ensure your `GOOGLE_API_KEY` is set correctly in `secrets.toml` or Streamlit Cloud.
- **Dependency Issues**: Try reinstalling with `pip install -r requirements.txt`.
- **Invalid JSON Response**: Restart the app and try a simpler topic.



## 💡 Future Enhancements
- Add **image generation** for slides.
- Improve **AI-generated slide design**.
- Support **collaborative editing** of slides.

## 🤝 Contributing
Feel free to fork the repo and submit pull requests! 🚀

## 📬 Contact
For queries, reach out at [reachout.jatinhans@gmail.com](mailto:reachout.jatinhans@gmail.com).

