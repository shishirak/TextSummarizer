# **Text Summarizer using Hugging Face Transformers**

## **Overview**

This project is a simple **Text Summarizer Web App** built using **Flask** (backend) and **HTML, jQuery, and AJAX** (frontend). It utilizes **Hugging Face Transformers** to generate concise summaries of input text.

## **Features**

--> User-friendly interface to input text and get a summary  
--> Uses **Hugging Face Transformers** for high-quality summarization  
--> Displays a **loading indicator** while processing  
--> **Clear button** to reset the input and output fields  
--> **Error handling** for empty input

## **Tech Stack**

- **Backend:** Flask, Hugging Face Transformers
- **Frontend:** HTML, CSS, jQuery, AJAX
- **API Integration:** Flask routes for text processing

## **How It Works**

1. User enters a paragraph in the input box.
2. Clicks on the **Summarize** button.
3. AJAX sends the text to the Flask backend.
4. The backend processes the text using a **Hugging Face summarization model**.
5. The summarized text is displayed on the same page.

## **Setup and Installation**

### **1. Clone the Repository**

```sh
git clone https://github.com/shishirak/TextSummarizer.git
cd TextSummarizer
```

### **2. Create and Activate a Virtual Environment**

```sh
python -m venv venv
source venv/bin/activate   # For macOS/Linux
venv\Scripts\activate      # For Windows
```

### **3. Install Dependencies**

```sh
pip install -r requirements.txt
```

### **4. Run the Flask App**

```sh
python app.py
```
