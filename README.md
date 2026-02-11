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

📂 Project Workflow -

* The user enters a city name, and the bot launches Zillow in an incognito browser.

* The bot searches for property listings in the selected city.

* UiPath Web Scraping Wizard extracts structured listing data across multiple pages.

* The extracted data is stored in a DataTable for processing.

* Data is cleaned by removing symbols like $ and sq ft and converting text into numbers.

* Final processed data is exported into an Excel file for analysis.
  
💡 Use Cases -

* Helps real estate agents analyze property prices across different cities.

* Assists investors in comparing price per square foot.

* Enables market trend analysis for housing demand.

* Reduces manual effort in collecting real estate data.

* Supports business intelligence teams with structured property data.

* Useful for academic or market research.
  
📘 What This Project Demonstrates -

* Ability to build real-world UiPath automation workflows.

* Strong knowledge of web scraping and pagination handling.

* Experience in DataTable manipulation and data cleaning.

* Implementation of user input handling.

* Excel automation and report generation skills.

* Use of reliable selectors and basic exception handling.
  
📈 Future Enhancements -

* Add support for multiple real estate websites.

* Implement automatic scheduling of data extraction.

* Include advanced analytics like price trends and graphs.

* Add database storage instead of Excel.

* Create a dashboard for real-time data visualization.

* Enable email reporting with attached Excel files.

# 🧑‍💻 Author -
Abhijit Kulkarni RPA Developer | UiPath | Power Automate | Automation Enthusiast
