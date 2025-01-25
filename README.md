# 📰 AI Article Summarizer  

**Summarize articles from any URL using Google Gemini 1.5 Flash and Gradio.**  

## 🚀 Features  
✅ Fetches and extracts text from any article URL  
✅ Uses **Gemini 1.5 Flash** for high-quality AI-generated summaries  
✅ Simple and user-friendly **Gradio UI**  
✅ Supports **newspaper3k** and **BeautifulSoup** for web scraping  

---

## 🛠️ Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/ai-article-summarizer.git
   cd ai-article-summarizer
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your Google Gemini API key**  
   - Replace `"YOUR_API_KEY"` in `app.py` with your actual API key.

---

## 🎯 Usage  

Run the application using:  
```bash
python app.py
```

After running, a **Gradio link** will be generated. Open it in your browser and start summarizing articles!  

---

## 📝 Example  

1. Enter an **article URL**  
2. Click **Summarize**  
3. Get an AI-generated **summary**  

**Screenshot:**  
![alt text](image-1.png) 

---

## 📂 File Structure  
```
ai-article-summarizer/
│── gradio_app.py        # Main application script
│── requirements.txt     # Required dependencies
│── README.md            # Project documentation
```

---

## 🛠 Dependencies  
- `gradio`
- `newspaper3k`
- `google-generativeai`
- `beautifulsoup4`
- `requests`

Install all dependencies using:  
```bash
pip install -r requirements.txt
```

---

## 📌 Roadmap  
- [ ] Improve text extraction for different article formats  
- [ ] Add more AI models (like Llama, Mistral, or local models)  
- [ ] Implement caching for repeated summaries  

---

## 🤝 Contributing  
Feel free to fork this repository, submit issues, or make pull requests to improve the project.  

---

## 📜 License  
This project is licensed under the **MIT License**.  

---

## ✨ Author  
👨‍💻 **Your Name** – [GitHub Profile](https://github.com/yourusername)  

🚀 *If you like this project, give it a ⭐ on GitHub!*  
