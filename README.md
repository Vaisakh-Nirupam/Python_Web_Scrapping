# 📚 Website Spell Checker & Crawler

A Python-based web crawler and spell checker that **crawls all accessible pages** of a website, **extracts visible text content**, and **identifies spelling mistakes** with suggestions for corrections.  
This project demonstrates automated web data extraction combined with simple spell checking to help improve content quality on websites.

---

## ⚡ Key Features

- 🌐 **Website Crawling:**  
  Traverses all paginated product listing pages and extracts individual product URLs starting from the homepage.

- 🔍 **Visible Text Extraction:**  
  Parses HTML to extract meaningful text content such as product titles, descriptions, and product info — excluding scripts and styles.

- 🧹 **Clean and Modular:**  
  Clean text processing with filtering to avoid punctuation and non-alphabetic tokens during spell check.

- 📝 **Spell Checking:**  
  Uses the `spellchecker` library to detect misspelled words and provide up to 5 suggestions for each misspelling.

- 💾 **Data Export:**  
  Saves all extracted links, product details, and spelling reports as CSV files for easy review and further processing.

---

## 🌟 What Makes It Special?

By combining web crawling with spell checking, this solution helps website owners and content teams identify and fix spelling errors across all pages, improving user experience and professionalism while allowing export of all data and reports as CSV files.

**Foundation for NLP Applications**  
The extracted, cleaned, and validated product data can be used as the basis for building advanced NLP-powered applications, like a book recommendation system.

---

## 🛠️ Tech Stack

| Tool           | Purpose                              |
| -------------- | ------------------------------------ |
| Python         | Core programming language            |
| Requests       | HTTP requests and page fetching      |
| BeautifulSoup4 | HTML parsing and content extraction  |
| urllib.parse   | URL management                       |
| spellchecker   | Spell checking and suggestion engine |
| Pandas         | Data handling and CSV export         |

---

## 🚀 How It Works

1. **Start Crawling:**  
   Begins at the homepage URL and traverses through all product listing pages using pagination links.

2. **Extract URLs:**  
   Collects URLs of all individual product pages.

3. **Parse Content:**  
   Visits each product page and extracts key visible content: title, description, product details, and image URLs.

4. **Spell Check:**  
   Cleans extracted text and identifies misspelled words with suggested corrections.

5. **Reporting:**  
   Compiles and exports comprehensive CSV reports of links, products, and spelling issues.

---

## 📈 Future Plans

Leverage this clean, structured dataset to build a **Book Recommendation NLP app** that can provide personalized suggestions based on content and metadata scraped from the website.

---

## 👨‍💻 Author

**Vaisakh Nirupam**  
🔗 [LinkedIn](https://www.linkedin.com/in/vaisakh-nirupam)

---
