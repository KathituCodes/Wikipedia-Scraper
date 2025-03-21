# Wikipedia-Scraper

## 🚀 Overview
Have you ever needed to extract structured content from Wikipedia without manually copying and pasting? This Python script automates the process, pulling article titles, text (with proper section mapping), and internal Wikipedia links all wrapped neatly into a single function. Just pass a Wikipedia URL, and boom! You get structured data ready for analysis, NLP, or whatever wizardry you're up to.

## 🎯 Objective
The goal is simple: take any Wikipedia page and extract its HTML content, title, article text (organized by headings), and internal links all in a clean and efficient way. This makes it easy to process Wikipedia data for various applications, from research to machine learning.

## 🛠️ How It Works
1. **Fetch & Parse HTML** – Loads and parses the Wikipedia page’s HTML content.
2. **Extract Title** – Grabs the official title of the Wikipedia article.
3. **Extract Text & Headings** – Retrieves article text, mapping paragraphs to their respective headings.
4. **Collect Internal Links** – Gathers all links pointing to other Wikipedia pages.
5. **One Function to Rule Them All** – A single function ties it all together, making extraction as simple as calling one function with a Wikipedia URL.
6. **Testing** – Run the script on any Wikipedia page to verify functionality.

## 📌 Usage
### Installation
First, make sure you have `requests` and `BeautifulSoup` installed:
```bash
pip install requests beautifulsoup4
```

### Running the Script
Simply import the function and pass in a Wikipedia URL:
```python
from wikipedia_scraper import extract_wikipedia_data

data = extract_wikipedia_data("https://en.wikipedia.org/wiki/Web_scraping")
print(data)
```

## 🎯 Why Use This?
- **Automates Wikipedia data extraction** – No more manual copy-pasting.
- **Structured output** – Get cleanly formatted text and links.
- **Ready for NLP & Data Science** – Ideal for text analysis, machine learning, or research.

## 📌 Future Improvements
- Support for additional metadata (e.g., references, images).
- Option to filter content by section.
- Multi-threading for faster scraping.

---
Give it a spin, and let me know if you have any ideas to make it even better! 🚀

