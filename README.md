# 🌤️ Real-Estate-Web-Scraping-Automation-Bot-
“An intelligent UiPath bot that scrapes, cleans, and converts real estate data into ready-to-analyze Excel reports.”
# 📌 Project Overview -
This project involves building an RPA bot using UiPath to scrape real estate data from websites like Zillow based on a city name entered by the user. The automation opens the website in an incognito browser, searches for properties in the selected city, and extracts detailed listing information such as property price, number of bedrooms, number of bathrooms, total square feet, and full address.

The bot uses UiPath’s Web Scraping Wizard to extract structured data across multiple pages using pagination. After scraping, the data is stored in a DataTable where it is cleaned and transformed. The bot removes unnecessary text (like $, sq ft), converts values into proper numeric format, and calculates additional insights such as price per square feet. New Data Table columns are created for processed data, ensuring well-organized output.

Finally, the cleaned and processed dataset is exported into an Excel file using Excel activities for easy analysis and reporting. The automation includes simple exception handling, stable selector usage, and a clean workflow structure, giving hands-on experience in real-world web automation and data extraction scenarios.

This project strengthens skills in user input handling, browser automation, structured data scraping, Data Table operations, data transformation, and Excel integration.

# 🚀 Key Features -

* 🔍 City-Based Property Search
Allows users to enter any city name and automatically fetch property listings from Zillow based on that input.

* 🌡️ Automated Browser Navigation
Opens the website in an incognito browser and performs all search and navigation steps without manual intervention.

* 🎯 Multi-Page Web Scraping
Uses UiPath’s Web Scraping Wizard with pagination to extract property data from multiple result pages.

* 🧠 Structured Data Extraction
Captures important listing details such as price, bedrooms, bathrooms, square feet, and full address in a structured format.

* 📄 Data Cleaning and Transformation
Automatically removes unwanted text like currency symbols and “sq ft,” converts values into numeric format, and prepares clean data for analysis.

* 🛡️ Price per Square Foot Calculation
Calculates additional insights such as price per square foot to help evaluate property value.

* ⚡ Excel Export and Reporting
Exports the final processed data into an Excel file for easy review, filtering, and reporting.

# 🛠️ Technologies & Tools Used -

•	UiPath Studio

•	UiPath Web Scraping Wizard

•	Data Scraping Activities

•	Browser Automation (Incognito Mode)

•	Selectors (Basic Understanding & Validation)

•	Data Table Operations (Add Column, For Each Row, Assign)

•	Excel Activities (Write Range, Append Range)

•	Try Catch (Basic Exception Handling)
