# Brazilian-E-Commerce-Public-Dataset-by-Olist
# Brazilian-E-Commerce-Public-Dataset-by-Olist
🛍️ Brazilian E-Commerce Analytics Dashboard
<p align="center"> <img src="Images/Olist_ecommerce_analytics_banner_1280x720_true_quality.gif" width="90%"> </p>

An end-to-end data analytics project built using the Olist Brazilian E-Commerce Public Dataset. The project transforms raw e-commerce data into an interactive Power BI dashboard, covering the complete analytics workflow — from data cleaning with Python to data modeling, DAX measures, and dashboard design.

The dashboard provides insights into:
📈 Revenue performance
🛒 Product performance
👥 Customer behavior
🚚 Delivery performance
⭐ Customer satisfaction
📌 Table of Contents
About the Project
Dataset
Tools & Technologies
Project Workflow
Repository Structure
Downloads
Dashboard Pages
Key Insights
Design System
How to Use
Author
📖 About the Project

This project analyzes approximately 100,000 e-commerce orders placed on the Olist marketplace between 2016 and 2018 across multiple Brazilian states. The main objective is to transform raw relational e-commerce data into a structured and interactive analytics solution that supports data-driven decision-making.

The project follows a complete data analytics workflow:

Cleaning and preprocessing raw data using Python and Pandas
Preparing clean CSV files for analysis
Building a relational data model in Power BI
Creating business KPIs and calculations using DAX
Designing an interactive and visually consistent dashboard
🗂️ Dataset

Source: Olist Brazilian E-Commerce Public Dataset The dataset contains approximately 100K anonymized orders from the Olist marketplace and covers the period between 2016 and 2018.

🛠️ Tools & Technologies
Python (Data cleaning and preprocessing)
Pandas (Data manipulation and transformation)
Jupyter Notebook (Data cleaning workflow)
Power BI Desktop (Data modeling, DAX measures, and dashboard development)
DAX (Business calculations and KPIs)
Figma (Dashboard background design and color palette planning)
🔄 Project Workflow

1️⃣ Data Cleaning & Preprocessing The raw Olist dataset was cleaned and prepared using Python and Pandas. The Python notebook used for this process is available in the Data_Cleaning/ folder, and the processed data was exported as CSV files.

2️⃣ Data Modeling A relational data model was created in Power BI to connect the main entities (Orders, Customers, Products, etc.).

3️⃣ DAX Measures & KPIs Custom DAX measures were created for metrics such as Total Revenue, Total Orders, Average Delivery Days, and On-Time Delivery Rate.

4️⃣ Dashboard Design The dashboard features a custom 1280x720 background created in Figma, a unified color palette, and custom icons to ensure a consistent user experience.

📁 Repository Structure
text
project/
│
├── 📂 Data_Cleaning/              # Python notebooks for data preparation
│   └── cleaning 1.ipynb           # Data cleaning and preprocessing script
│
├── 📂 data/                       # Download from Google Drive (Link below)
│   ├── project.pbix               # Power BI Dashboard file
│   └── cleaned_*.csv              # Cleaned CSV files used in the model
│
├── Icons/                         # All custom icons used in the dashboard
│
├── Images/                        # Screenshots and banners
│   ├── Olist_ecommerce_analytics_banner_1280x720_true_quality.gif
│   ├── Screenshot 2026-09-04 220413.png
│   ├── Screenshot 2026-09-04 220434.png
│   ├── Screenshot 2026-09-07 134256.png
│   └── Screenshot 2026-09-07 141410.png
│
├── Theme/                         # Dashboard design assets
│   ├── Untitled.png               # Background designed using Figma
│   └── color_palette.png          # Color palette used across the dashboard
│
└── README.md
📥 Downloads

Due to file size limitations, the cleaned datasets and the Power BI dashboard file are bundled together and hosted on Google Drive.

📊 Download the Project Files (Data & Dashboard)

After downloading: Simply extract the folder and open project.pbix using Power BI Desktop. Since the dashboard and the CSV files are in the same folder, Power BI will successfully access the data without any path errors.

📊 Dashboard Pages
🏠 Landing Page

The dashboard starts with a custom Landing Page designed to provide a clear entry point for users.

<p align="center"> <img src="Images/WhatsApp Image 2026-09-08 at 2.10.37 PM.jpeg" width="90%"> </p>
1️⃣ Overview

A high-level view of overall business performance including Total Revenue by Month and Top Product Categories.

<p align="center"> <img src="Images/WhatsApp Image 2026-09-08 at 2.10.37 PM (1).jpeg" width="90%"> </p>
2️⃣ Customer Analysis

An analysis of customer distribution and revenue contribution across Brazilian states.

<p align="center"> <img src="Images/WhatsApp Image 2026-09-08 at 2.10.36 PM.jpeg" width="90%"> </p>
3️⃣ Product Performance

A detailed analysis of product categories, sales volume, and average prices.

<p align="center"> <img src="Images/WhatsApp Image 2026-09-08 at 2.10.35 PM.jpeg" width="90%"> </p>
4️⃣ Delivery & Satisfaction

An analysis of delivery performance and its relationship with customer review scores.

<p align="center"> <img src="Images/Screenshot 2026-09-07 141410.png" width="90%"> </p>
💡 Key Insights

📊 Revenue Is Concentrated A relatively small number of product categories generate a significant share of total revenue.

🌍 Geography Impacts Delivery Customers in remote northern states experience delivery times that are more than twice the national average.

💳 Credit Cards Dominate Credit cards generate more than 78% of total revenue.

⭐ Delivery Impacts Satisfaction Longer delivery periods are generally associated with lower customer satisfaction scores.

🎨 Design System

The dashboard follows a consistent visual design system. The design assets are stored inside the Theme/ folder.

<p align="center"> <img src="Theme/Untitled.png" width="60%"> </p>
▶️ How to Use
Clone the Repository: git clone <repository-url>
Download Files: Download the project files from the Downloads section.
Open Dashboard: Open project.pbix (located inside the downloaded folder) using Power BI Desktop.
👤 Author

Built as a portfolio data analytics project using the public Olist Brazilian E-Commerce Public Dataset.

Connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-ahmed-5a769741a?utm_source=share_via&utm_content=profile&utm_medium=member_android) o
