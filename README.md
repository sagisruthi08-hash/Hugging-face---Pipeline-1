🤗 Hugging Face Pipelines for NLP Tasks
📌 Project Overview
This project demonstrates the use of Hugging Face Transformers pipelines to perform four Natural Language Processing (NLP) tasks using pretrained AI models.

The application is developed using Python in Visual Studio Code (VS Code). It provides a simple, menu-driven interface that allows users to perform text summarization, language translation, sentiment analysis, and question answering.

🎯 Objectives
To understand and implement Hugging Face Transformers pipelines.
To perform text summarization using pretrained models.
To translate English text into French.
To analyze the sentiment of text.
To answer questions based on a given context.
To explore practical applications of Natural Language Processing.
✨ Features
1. Text Summarization
Automatically generates a shorter version of a long text while preserving its main ideas.

Pipeline: summarization

2. Language Translation
Translates English text into French using a pretrained translation model.

Pipeline: translation_en_to_fr

3. Sentiment Analysis
Identifies whether a given text expresses positive or negative sentiment and provides a confidence score.

Pipeline: sentiment-analysis

4. Question Answering
Extracts answers to questions from a user-provided context.

Pipeline: question-answering

🛠️ Technologies Used
Programming Language: Python
Development Environment: Visual Studio Code
AI Platform: Hugging Face
NLP Library: Transformers
Deep Learning Framework: PyTorch
Additional Library: SentencePiece
📂 Project Structure
HuggingFace-Pipelines/
│
├── main.py
├── README.md
└── requirements.txt
⚙️ Installation and Setup
Step 1: Clone the Repository
git clone <your-github-repository-url>
Navigate to the project directory:

cd HuggingFace-Pipelines
Alternatively, open your existing project folder directly in VS Code.

Step 2: Create a Virtual Environment
python -m venv venv
Activate the environment in Windows PowerShell:

.\venv\Scripts\Activate.ps1
If PowerShell blocks activation, you can use Command Prompt:

venv\Scripts\activate.bat
Step 3: Install Dependencies
Install the required libraries:

python -m pip install transformers torch sentencepiece
Step 4: Run the Application
Execute the Python program:

python main.py
🧠 Pretrained Models Used
Task	Model
Text Summarization	sshleifer/distilbart-cnn-12-6
English-to-French Translation	Helsinki-NLP/opus-mt-en-fr
Sentiment Analysis	distilbert/distilbert-base-uncased-finetuned-sst-2-english
Question Answering	distilbert/distilbert-base-cased-distilled-squad
These pretrained models are downloaded from Hugging Face when they are first needed and are not already cached locally.

💻 Example Usage
When the application starts, the following menu is displayed:

====================================
   HUGGING FACE NLP PIPELINES
====================================
1. Text Summarization
2. Translation (English to French)
3. Sentiment Analysis
4. Question Answering
5. Exit
Select an option to execute the corresponding NLP task.

Example: Sentiment Analysis
Input:

I love learning Artificial Intelligence.
Expected Result:

Sentiment: POSITIVE
Confidence Score: Model-dependent
The actual confidence score depends on the model's prediction.

📋 Requirements
Python 3.9 or a compatible Python version supported by the installed dependencies.
Visual Studio Code.
Internet access for downloading pretrained models.
Sufficient memory and storage to install PyTorch and load the models.
🌍 Applications
Automatic summarization of documents and articles.
Language translation.
Customer feedback and review analysis.
Question-answering systems.
Educational applications.
Text processing and information extraction.
🚀 Future Enhancements
Add a graphical user interface using Streamlit.
Allow users to enter their own text.
Support translation between additional languages.
Accept documents for summarization.
Add more sentiment categories and emotion detection.
Deploy the application as a web-based NLP tool.
📚 Learning Outcomes
Through this project, I learned how to:

Use Hugging Face Transformers pipelines.
Load and run pretrained NLP models.
Perform common NLP tasks using Python.
Understand model outputs and confidence scores.
Integrate multiple AI tasks into a single application.
👩‍💻 Author
Sruthi S

BSc Computer Science with Artificial Intelligence

📄 License
This project is intended for educational and learning purposes. Refer to the individual pretrained models' licenses for their usage and redistribution conditions.




**1. Create `requirements.txt`**

Add these lines to a file named `requirements.txt`:

```text
transformers
torch
sentencepiece
2. Don't upload your virtual environment.

Add this to your .gitignore file:

venv/
__pycache__/
*.pyc
Your final project structure should be:

HuggingFace-Pipelines/
│
├── main.py
├── README.md
├── requirements.txt
└── .gitignore
