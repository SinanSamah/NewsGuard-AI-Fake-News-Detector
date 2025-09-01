# NewsGuard AI: Fake News Detection, Recommendation, and Summarization System

This is the source code for NewsGuard AI, an end-to-end system designed to classify news articles as 'real' or 'fake' using a Bidirectional CuDNNLSTM model. The project also provides users with verified alternative sources and AI-powered summaries for credible articles.

[![Project Demo on YouTube](https://img.youtube.com/vi/XAa1Y5wHieQ/0.jpg)](https://www.youtube.com/watch?v=XAa1Y5wHieQ)
*<p align="center">Click the image above to watch the full 10-minute video demonstration.</p>*

---

## Features
* **Deep Learning Classification:** A Bidirectional CuDNNLSTM model with an Attention Mechanism classifies news with **93.01% accuracy**.
* **AI Transparency:** Integrates **LIME (Local Interpretable Model-agnostic Explanations)** to show users which words influenced the model's prediction.
* **Source Verification:** For articles classified as "Real", the system uses the **NewsAPI** to find and recommend related articles from credible sources.
* **AI-Powered Summaries:** Uses a **Hugging Face BART model** to generate concise summaries of recommended articles.
* **Interactive UI:** The entire application is deployed in a user-friendly web interface built with **Streamlit**.

---

## Technologies Used
* **AI/ML:** Python, TensorFlow, Keras, Scikit-learn, Deep Learning, Bidirectional LSTM
* **NLP:** Hugging Face Transformers, LIME, spaCy, NLTK
* **Deployment & Tools:** Git, GitHub, Streamlit, API Integration, Google Colab

---

## How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/SinanSamah/NewsGuard-AI-Fake-News-Detector.git](https://github.com/SinanSamah/NewsGuard-AI-Fake-News-Detector.git)
    cd NewsGuard-AI-Fake-News-Detector
    ```
2.  **Set up a virtual environment and install dependencies:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r "Source Code/Streamlit_Code/requirements.txt"
    ```
3.  **Set up your secrets:**
    Create a file at `Source Code/Streamlit_Code/.streamlit/secrets.toml` and add your NewsAPI key:
    ```toml
    NEWS_API_KEY = "YOUR_API_KEY_HERE"
    ```
4.  **Run the Streamlit application:**
    ```bash
    streamlit run "Source Code/Streamlit_Code/main_app.py"
    ```

---
