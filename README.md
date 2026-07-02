# 📝 Text Summarization using PEGASUS

A Natural Language Processing (NLP) project that performs **Abstractive Text Summarization** using the **PEGASUS** transformer model from Hugging Face. The model is fine-tuned on the **SAMSum** dataset to generate concise summaries of conversations.

---

## 🚀 Project Overview

This project demonstrates how to:

- Load and preprocess the SAMSum dialogue summarization dataset
- Fine-tune the PEGASUS model for abstractive summarization
- Generate summaries for unseen conversations
- Evaluate the model using ROUGE metrics

---

## 📂 Dataset

- **Dataset:** SAMSum
- **Task:** Dialogue Summarization
- **Source:** Hugging Face Datasets

Each sample contains:

- **Dialogue:** A conversation between two or more people
- **Summary:** A short summary of the conversation

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Evaluate
- NLTK
- Pandas
- Matplotlib

---

## 📦 Model

- **Model Name:** `google/pegasus-cnn_dailymail`

PEGASUS is a transformer model designed specifically for text summarization tasks.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Text-Summarization-using-PEGASUS.git
cd Text-Summarization-using-PEGASUS
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the Jupyter Notebook or Google Colab notebook and execute the cells sequentially.

---

## 📊 Evaluation

The model is evaluated using:

- ROUGE-1
- ROUGE-2
- ROUGE-L
- ROUGE-Lsum

---

## 💡 Example

### Input Dialogue

```
John: Hi Sarah!
Sarah: Hi John.
John: Are you coming to the meeting?
Sarah: Yes, I'll be there at 10 AM.
```

### Generated Summary

```
Sarah confirms that she will attend the meeting at 10 AM.
```

---

## 📁 Project Structure

```
Text-Summarization-using-PEGASUS/
│
├── Text_Summarization.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## 🔮 Future Improvements

- Deploy using FastAPI
- Create a Streamlit web application
- Fine-tune on custom datasets
- Compare PEGASUS with T5 and BART
- Deploy on AWS

---

## 👨‍💻 Author

**Lohith Vattam**

- GitHub: https://github.com/LOHITHVATTAM1628
- LinkedIn: https://linkedin.com/in/lohith-vattam-827343326

---

## ⭐ If you found this project useful

Please consider giving this repository a ⭐ on GitHub!
