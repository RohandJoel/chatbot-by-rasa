This project demonstrates the development of a Generative AI-based chatbot using Python, Rasa, and HuggingFace Transformers. The chatbot is capable of handling user queries in a context-aware manner using a combination of rule-based and generative AI models. It aims to improve customer engagement by providing natural, dynamic, and intelligent conversations without relying on hard-coded scripts.

---

 🎯 Objectives

- Build a chatbot that understands user intents and entities using Rasa NLU.
- Integrate a Generative AI model (e.g., GPT-2) to handle open-ended or unknown queries.
- Deploy the chatbot through a basic HTML-based web interface.
- Enable feedback and learning mechanisms for future scalability and improvement.

---

 🛠️ Technologies Used

- Python – Programming language
- Rasa – NLP and chatbot framework
- HuggingFace Transformers – For pre-trained generative models like GPT-2
- HTML – For web interface
- VS Code – Development environment
- Additional Libraries – TensorFlow, spaCy, scikit-learn (optional)

---

 ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/genai-chatbot.git
   cd genai-chatbot
````

2. Install Rasa and dependencies:

   ```bash
   pip install rasa
   ```

3. Initialize the chatbot project:

   ```bash
   rasa init
   ```

4. Train the chatbot model:

   ```bash
   rasa train
   ```

5. Run custom actions (if any):

   ```bash
   rasa run actions
   ```

6. Run the chatbot:

   ```bash
   rasa run -m models --enable-api --cors ""
   ```

7. Launch the web interface:

    Open the provided `index.html` file in a browser.

---
 ✅ Features

 Intent recognition and entity extraction
 Dynamic response generation using GPT-2
 Modular architecture for easy extension
 Simple web interface for interaction

---

 🚀 Future Enhancements

 Multilingual support
 User-specific personalization
 Integration with analytics tools
 Deployment on cloud platforms

---

 📚 References

 [Rasa Documentation](https://rasa.com/docs/)
 [HuggingFace Transformers](https://huggingface.co/docs/transformers/index)
 [OpenAI GPT Models](https://platform.openai.com/docs)
 [HTML Basics](https://developer.mozilla.org/en-US/docs/Web/HTML)

