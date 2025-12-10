# Banking Web Automation Suite 🏦

## 📌 Project Overview
This project is a robust test automation framework designed for a Banking Web Application. It uses **Selenium WebDriver** with the **Page Object Model (POM)** design pattern to ensure script maintainability. It automates critical financial workflows including secure login, fund transfers, and statement generation.

## 🛠 Tech Stack
* **Language:** Python
* **Automation Tool:** Selenium WebDriver
* **Design Pattern:** Page Object Model (POM)
* **Data Source:** Excel (Data-Driven Testing) for multiple account scenarios.

## 🧪 Test Scenarios Automate
| Module | Test Case Description | Logic Used |
| :--- | :--- | :--- |
| **Login** | Validate secure login with valid/invalid credentials. | Alert Handling & Encryption checks. |
| **Fund Transfer** | Automate money transfer between accounts. | Form validation & Transaction ID verification. |
| **Account Summary** | Verify balance updates after transactions. | Dynamic Table handling (WebTables). |
| **New Customer** | Add new customer details and validate DB reflection. | Form inputs & Validation messages. |

## 🚀 Key Highlights
* **Page Object Model (POM):** Separated page locators from test logic, reducing code duplication by 60%.
* **Data-Driven Testing:** Integrated with Excel to run the same test with 50+ different user datasets.
* **Reporting:** Generates HTML reports with screenshots for failed test cases.

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/jayanthruthala/Banking-Web-Automation.git](https://github.com/jayanthruthala/Banking-Web-Automation.git)

2. Install dependancies:
   ```
   pip install selenium openpyxl

3. Run the Test Suite:
   ```
   python test_runner.py
   
