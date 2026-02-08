# Article Translator with Azure OpenAI

This project is an **article and text translator** using **Azure OpenAI Service** with **LangChain**, developed in Python and executed in **Google Colab**.

The notebook allows you to:
- Extract text from articles (e.g., web pages)
- Translate the content into another language
- Return the result in **Markdown**

---

## 🚀 Technologies used

- Python  
- Google Colab  
- Azure OpenAI Service  
- LangChain  
- BeautifulSoup  
- Requests

---

## ▶️ How to run

- Open the `article_translator.ipynb` notebook in Google Colab.  
- Configure your Azure OpenAI credentials.  
- Run the cells in order.  
- Provide the text or URL to be translated and wait for the result.

---

## 🧠 Usage example

Example of a function available in the notebook:
```python
translate_article(
    "Let's see if the deployment was succeeded.",
    "português"
)
```

Expected output:
```python
Vamos ver se o deployment foi bem-sucedido.
```


