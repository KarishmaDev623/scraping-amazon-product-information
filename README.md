📦 Scraping Amazon Product Information using Beautiful Soup
This project demonstrates how to scrape product data from Amazon using Python's requests and BeautifulSoup libraries. The data includes product title, rating, and price for search results of a specific keyword.

🧰 Technologies Used
Python 3.x

BeautifulSoup4

Requests

Jupyter Notebook

📑 Features
Automates search queries for Amazon products

Parses and extracts:

Product Name

Product Rating

Product Price

Outputs results in a structured format

⚙️ How It Works
Sends an HTTP request to Amazon search results using a keyword.

Parses the HTML content with BeautifulSoup.

Extracts product data using HTML tags and class names.

Displays or processes the data as needed.

🚀 Getting Started
🔧 Installation
bash
Copy
Edit
pip install beautifulsoup4
pip install requests
▶️ Running the Code
Open the .ipynb notebook file.

Modify the search_query variable (e.g., "bags", "laptop").

Run all cells to fetch and display results.

🔐 Note on Headers
Amazon may block automated scraping. Use headers with a user-agent string to mimic a browser:

python
Copy
Edit
headers = {
    'User-Agent': 'Mozilla/5.0 (Windows NT 10.0; Win64; x64)'
}
📌 Limitations
Amazon frequently updates its HTML structure — scraping code may break.

Requests from bots may be blocked — rotate IPs or use proxies for large-scale scraping.

📁 Example Output
plaintext
Copy
Edit
Product: F Gear Luxur Brown Laptop Backpack
Rating: 4.3 out of 5 stars
Price: ₹1,399
📄 License
This project is for educational purposes only. Scraping Amazon may violate its Terms of Service.
