🏆 Competitive Price Scraper








A custom-built Selenium web automation tool created to track and analyze competitor pricing in real-time.

This project was built before the era of ChatGPT and LLM-assisted coding, entirely from scratch. It automated logins, scraped data across multiple e-commerce platforms, structured the results, and exported clean datasets for analytics and reporting.

🚀 Highlights

Automated end-to-end competitor monitoring (login → scrape → export).

Collected live pricing, availability, and product metadata.

Deployed to an AWS EC2 instance for continuous, cloud-based execution.

Used a lightweight Windows .bat file scheduler to trigger runs automatically.

Configurable for multiple platforms and product categories.

🏅 Recognition

This scraper wasn’t just another side project — it earned me a direct award from CEO Claire Gills at Bell Mobility for its innovation and measurable impact on the company’s pricing strategy.

⚙️ Workflow Overview
+---------------------+
|   Windows .bat Job  |
|   (Scheduler)       |
+----------+----------+
           |
           v
+---------------------+
|   AWS EC2 Instance  |
|   (24/7 Runtime)    |
+----------+----------+
           |
           v
+---------------------+
|   Selenium Scraper  |
|   (Login + Crawl)   |
+----------+----------+
           |
           v
+---------------------+
|   Data Export       |
|   (CSV/Excel)       |
+----------+----------+
           |
           v
+---------------------+
|   Analytics & BI    |
|   (Price Strategy)  |
+---------------------+

⚠️ Ownership & Code Access

The full implementation is proprietary to Bell Mobility and cannot be shared publicly.
This repository contains only sample snippets and simplified demonstrations that illustrate the techniques used (e.g., Selenium automation patterns, scheduling, and export flows).
