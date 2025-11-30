![banner](https://i.ibb.co/k27s42VP/Captura-desde-2025-07-30-21-35-35.png)

## 🎯 What does 2dehands Scraper do

2dehands Scraper helps you extract product listings and marketplace data from **2dehands.be**, Belgium's leading online marketplace for buying and selling second-hand items.

<p align="center">
  <a href="https://apify.com/lexis-solutions/2dehands-be-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px;" />
  </a>
</p>


You can extract detailed product information including prices, SKUs, seller information, descriptions, and other key details from the website. 2dehands Scraper supports REST API which gives you access to the extracted dataset, enables you to download it in various formats and use it in other applications.

## 📊 What data can I extract from 2dehands with a web scraper

With this web scraping tool, you can extract the following data from 2dehands:

<table>
<tr>
<td>🏷️ Product title</td>
<td>💰 Price</td>
</tr>
<tr>
<td>🔢 SKU number</td>
<td>👤 Seller information</td>
</tr>
<tr>
<td>📝 Product description</td>
<td>🏷️ Categories</td>
</tr>
<tr>
<td>🔗 Product URL</td>
<td>📊 Product details</td>
</tr>
<tr>
<td>🖼️ Product images</td>
<td>📍 Location information</td>
</tr>
</table>

## 🚀 Why scrape 2dehands.be

2dehands.be is Belgium's most popular online marketplace for second-hand items, with millions of listings across various categories. Scraping 2dehands.be can help you:

- Track pricing trends for second-hand items
- Monitor product availability and market demand
- Research competitor pricing strategies
- Analyze seller behavior and marketplace dynamics
- Make informed purchasing decisions
- Monitor new listings and popular categories
- Understand regional market differences in Belgium

## 🛠️ How to use 2dehands Scraper

2dehands Scraper is designed for easy and fast start even if you've never extracted data from websites before. Here's how you can extract data from 2dehands:

1. Create a free Apify account using your email
2. Open 2dehands Scraper on the Apify platform
3. Click on the **Try for free** button
4. Enter your search parameters or start URLs
5. Click on the **Start** button and wait for the data to be extracted
6. Download your data in JSON, XML, CSV, Excel, or HTML

## ⚙️ Input

The actor accepts the following input parameters:

- `startUrls` (array) - Array of URLs to start scraping from
- `maxItems` (integer) - Maximum number of products to scrape (default: 10)

Example:

```json
{
  "startUrls": [
    {
      "url": "https://www.2dehands.be/q/samsung"
    }
  ],
  "maxItems": 10
}
```

## 📤 Output

The scraped data will be saved as a dataset. Each item will represent a product listing. You can download your data in various formats: JSON, JSONL, HTML table, CSV, Excel spreadsheet, or NDJSON.

Example of the output format:

```json
{
  "url": "https://www.2dehands.be/v/elektronische-apparatuur/wasmachines/a152578136-samsung-ww11dg5b25ae-11-kg",
  "title": "Samsung WW11DG5B25AE  11 kg",
  "sku": "152578136",
  "price": "€ 480,00",
  "sellerInfo": {
    "name": "bart",
    "identity": "Zakelijke verkoper"
  },
  "description": "Samsung washing machine in excellent condition...",
  "categories": ["Elektronische apparatuur"]
}
```

## ⚠️ Notes and Limitations

- The actor relies on the structure of the 2dehands website. If the website structure changes, the actor may need to be updated
- Ensure you comply with the terms of service of 2dehands.be when using this actor
- For large-scale scraping, use Apify's proxy services to avoid IP blocking
- The scraper uses Camoufox for enhanced browser fingerprinting to avoid detection
- Respect rate limits to avoid overwhelming the website

## 🔗 Need to scrape other marketplaces

Check out our other marketplace scrapers:

- [Alibaba Scraper](https://apify.com/lexis-solutions/alibaba-scraper)
- [Otto Scraper](https://apify.com/lexis-solutions/otto-de-scraper)

## 🛠️ Want something custom-built

This 2dehands Scraper doesn't exactly do what you need? You can always build your own! Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!
