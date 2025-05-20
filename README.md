# Langchain-QnA with Gemma Model

This repository demonstrates the use of the **Gemma Model (2B)** with **Langchain** and **Streamlit** to build a question-answering app. The application leverages Ollama for running the Gemma model locally and uses Langchain's pipeline to manage the prompt and the model.

---

## 🛠️ Project Structure

```
📦 Langchain-QnA-with-Gemma-Model
├── app.py              # Main application file
├── .env                # Environment variables
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
```

---

## 🚀 Features

* Streamlit-based user interface for inputting questions
* Integration of the Gemma model (2B) through Ollama
* Prompt template using Langchain for structured interactions
* Langsmith tracking enabled for prompt and output logging

---

## 📦 Dependencies

Ensure you have the following libraries installed:

* streamlit
* langchain-community
* langchain-core
* python-dotenv

All dependencies are listed in the `requirements.txt` file.

---

## 🔧 Installation and Setup

1. **Clone the repository:**

```bash
git clone https://github.com/Electrolight123/Langchain-QnA-with-Gemma-Model.git
cd Langchain-QnA-with-Gemma-Mode
```

2. **Create and activate a virtual environment:**

```bash
python -m venv env
source env/bin/activate  # On Unix/macOS
env\Scripts\activate    # On Windows
```

3. **Install the dependencies:**

```bash
pip install -r requirements.txt
```

4. **Install Ollama:**

Follow the official installation instructions from [Ollama](https://ollama.com).

After installation, run the following command to pull the Gemma 2B model:

```bash
ollama pull gemma:2b
```

5. **Setup the `.env` file:**

Create a `.env` file in the project root with the following content:

```
LANGCHAIN_API_KEY="YOUR_LANGCHAIN_API_KEY"
LANGCHAIN_PROJECT="GenAIAPPwithOPENAI"
HF_TOKEN="YOUR_HF_TOKEN"
```

Replace the placeholders with your actual keys.

6. **Run the application:**

```bash
streamlit run app.py
```

7. **Access the application:**

Open the link provided by Streamlit in your browser.

---

## ✅ Testing

* Enter a question in the text input box.
* The Gemma model (2B) will provide a response based on the Langchain pipeline.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🛠️ Contributions

Feel free to fork this repository, open issues, and submit pull requests.





