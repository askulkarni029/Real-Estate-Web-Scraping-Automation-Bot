# 🌤️ Real-Estate-Web-Scraping-Automation-Bot-
“An intelligent UiPath bot that scrapes, cleans, and converts real estate data into ready-to-analyze Excel reports.”
📌 Project Overview -
This project involves building an RPA bot using UiPath to scrape real estate data from websites like Zillow based on a city name entered by the user. The automation opens the website in an incognito browser, searches for properties in the selected city, and extracts detailed listing information such as property price, number of bedrooms, number of bathrooms, total square feet, and full address.

The bot uses UiPath’s Web Scraping Wizard to extract structured data across multiple pages using pagination. After scraping, the data is stored in a DataTable where it is cleaned and transformed. The bot removes unnecessary text (like $, sq ft), converts values into proper numeric format, and calculates additional insights such as price per square feet. New Data Table columns are created for processed data, ensuring well-organized output.

Finally, the cleaned and processed dataset is exported into an Excel file using Excel activities for easy analysis and reporting. The automation includes simple exception handling, stable selector usage, and a clean workflow structure, giving hands-on experience in real-world web automation and data extraction scenarios.

This project strengthens skills in user input handling, browser automation, structured data scraping, Data Table operations, data transformation, and Excel integration.
