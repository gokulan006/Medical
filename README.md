# MedSnap: AI-Powered Medical Research Platform

## 📌 Overview
MedSnap is an AI-powered tool designed for **medical students, researchers, and professionals** to streamline their workflow. It leverages state-of-the-art NLP models to assist in **skimming medical abstracts, summarizing research papers, and providing the latest medical news with AI-powered insights**.

## 🚀 Features
1. **Medical Abstract Skimmer** 📚
   - Automatically organizes medical abstracts into structured sections such as **Objective, Methods, Results, Conclusions, and Background**.
   - Fine-tuned using **DistilBERT** on the **PubMed 20k RCT dataset**.

2. **Medical Text Summarization** 🏥
   - Summarizes **medical research papers, notes, and abstracts**.
   - Uses **BART/T5 transformers** trained on scientific literature.
   - Provides three summary modes:
     - **Abstract Summary** (Concise overview of the abstract)
     - **Notes Summary** (Detailed summary suitable for quick reference)
     - **Full Paper Summary** (Comprehensive summary covering all key insights)

3. **Medical News Aggregator & Summarizer** 📰
   - Fetches **real-time medical news**.
   - Provides AI-generated **summaries, meta descriptions, and SEO titles** to enhance readability and searchability.
   - Ensures medical professionals stay updated with the latest advancements.

## 🛠️ Technology Stack
- **Hugging Face Transformers** (for NLP-based summarization & text processing)
- **Gradio** (for interactive web-based UI)
- **PyTorch** (for deep learning model inference)
- **BeautifulSoup & Requests** (for web scraping and fetching news articles)
- **Hugging Face Spaces** (for model deployment)

## 📂 Project Structure
```
MedSnap/
│── app.py                # Main Gradio application
│── summarizer.py         # Summarization model pipeline
│── news_scraper.py       # Medical news scraper
│── requirements.txt      # Dependencies
│── README.md             # Project documentation
│── notebooks/
│   ├── SkimLit.ipynb     # Medical abstract skimmer notebook
│   ├── Med_Summary.ipynb # Research paper & notes summarizer
│   ├── Med_News.ipynb    # Medical news summarizer
```

## 📌 How to Use
### 🔹 Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MedSnap.git
   cd MedSnap
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Gradio app:
   ```bash
   python app.py
   ```

### 🔹 Hugging Face Spaces
You can also access **MedSnap** on Hugging Face Spaces [here](https://huggingface.co/spaces/your-space-url).

## 📌 Example Usage
### **Medical Abstract Skimmer**
Input:
```
Background: Artificial Intelligence (AI) is revolutionizing medical diagnosis.
Methods: We conducted a study with 500 participants using AI-assisted diagnostics.
Results: AI improved accuracy by 30%.
Conclusions: AI can enhance diagnostic reliability.
```
Output:
```
Objective: Explore AI's impact on diagnosis.
Methods: 500 participants, AI-assisted diagnostics.
Results: 30% accuracy improvement.
Conclusions: AI enhances reliability.
```

### **Medical Research Paper Summarization**
Input:
```
Deep learning has been widely adopted in radiology. A study on AI-based tumor detection found that...
```
Output:
```
Summary: AI-driven deep learning models show promising results in tumor detection, improving diagnostic accuracy.
```

### **Medical News Summarization**
Input:
```
A breakthrough in cancer research shows that...
```
Output:
```
Title: "Breakthrough in Cancer Research: New Treatment Discovered"
Meta Description: "Scientists have discovered a groundbreaking treatment for cancer..."
Summary: "Recent research reveals an innovative approach to cancer treatment..."
```

## 📝 Future Enhancements
- ✨ Expand dataset for improved summarization accuracy.
- 📊 Integrate visualization for research insights.
- 🌎 Support multiple languages for global accessibility.

## 🤝 Contributing
Feel free to contribute by submitting issues or pull requests!

## 📜 License
Apache 2.0 License - Free to use and modify.

---
### 🔗 Connect with Us
💻 GitHub: [gokulan006](https://github.com/gokulan006)

