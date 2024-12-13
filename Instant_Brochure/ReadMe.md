# **Brochure Builder Project**

## **Overview**
This project is a simple automation tool I created during my free time to generate professional brochures for businesses. It takes a company's name and website, scrapes relevant content, and uses AI to generate a draft for a brochure. This project is a hands-on exploration of how web scraping and AI can be combined to automate content creation.

---

## **How It Works**
1. **Input**: Provide a company name and its website URL.
2. **Web Scraping**: The project uses BeautifulSoup to extract content from the company's website, like key details about their services, products, or mission statement.
3. **AI Generation**: OpenAI's GPT model processes the extracted data and generates structured, professional text suitable for brochures.
4. **Output**: A markdown draft of the brochure that can be further designed or edited.

---

## **Tools and Technologies**
### **Libraries**
- `requests` and `json`: For handling API interactions.
- `BeautifulSoup`: For web scraping and parsing HTML content.
- `dotenv`: For securely storing API keys.
- `IPython.display`: For displaying results in the notebook.

### **API**
- **OpenAI API**: Used for generating brochure text. It provides human-like text generation capabilities.

---


