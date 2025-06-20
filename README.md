# 🧠 Email Classifier with LLaMA2 via Ollama
🙋‍♂️ About Me
This project was built as part of my AI learning journey and demonstrates local LLM usage with real-world applications. It's an AI email classifier, using Llama to organise and categorise your email inbox.

Connect with me on [LinkedIn](https://uk.linkedin.com/in/aomufti) 🚀

This project uses a local LLaMA2 model via [Ollama](https://ollama.com/) to classify email messages into categories: **Priority**, **Updates**, or **Promotions**.

---

## 📁 Files

| File | Description |
|------|-------------|
| `email_classifier_llama2.ipynb` | Main Jupyter notebook for training + testing |
| `email_categories_data.csv`     | Sample email dataset |
| `requirements.txt`              | Python dependencies |
| `README.md`                     | Project description and setup |

---

## 🛠 Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/your-username/email-classifier-llama2.git
cd email-classifier-llama2
### 2. Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
### 3. Install dependencies 
pip install -r requirements.txt
### 4. Install and run Ollama
ollama pull llama2
### 5. Running the Notebook
Launch Jupyter Notebook or VS Code.
Open email_classifier_llama2.ipynb
Run the cells top to bottom.
###Example output: 
Email: "Your payment failed. Please update immediately."
Prediction: Priority
