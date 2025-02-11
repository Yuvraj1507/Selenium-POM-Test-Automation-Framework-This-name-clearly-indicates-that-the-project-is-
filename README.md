# Selenium POM Test Automation Framework

## 📌 Project Overview

This project is a Test Automation Framework built using Selenium with Java, 
following the Page Object Model (POM) design pattern. It leverages TestNG for
test execution, Maven for dependency management, and integrates log4j for logging
and Extent Reports for detailed test reporting.

## 🚀 Key Features

* Page Object Model (POM) to enhance test maintainability and reusability.

* Automated UI Testing for web applications using Selenium WebDriver.

* Test Execution with TestNG (Parallel execution, Assertions, Annotations, Reporting).

* Logging Mechanism using log4j.

* Detailed HTML Reports with Extent Reports.

* Configuration Management with config.properties.

* Maven Build System for managing dependencies and running test cases.

* Screenshot Capture on Test Failures.

## 🛠️ Tech Stack & Tools

* Programming Language: Java

* Automation Framework: Selenium WebDriver

* Test Framework: TestNG

* Build & Dependency Management: Maven

* Logging: log4j

* Reporting: Extent Reports

* Version Control: Git & GitHub


# 📂 Project Structure

# Selenium-POM-Test-Automation-Framework/

├── src/main/java/com/crm/qa/
│   ├── base/TestBase.java          # Initializes WebDriver & Configurations
│   ├── config/config.properties    # Stores environment-specific settings
│   ├── pages/                      # Page classes (POM Design Pattern)
│   ├── util/TestUtil.java          # Utility functions (Waits, Screenshots, etc.)
├── src/test/java/com/crm/qa/
│   ├── testcases/LoginPageTest.java  # Test Cases
│   ├── testcases/HomePageTest.java   # Test Cases
├── pom.xml                          # Maven Dependency Management
├── test-output/                      # Test Reports
├── screenshots/                      # Captured failure screenshots
└── README.md

# 📖 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/Selenium-POM-Test-Automation-Framework.git
cd Selenium-POM-Test-Automation-Framework

2️⃣ Install Dependencies

* Ensure you have Java, Maven, and TestNG installed. Then, run:

mvn clean install

3️⃣ Run Test Cases

* Execute the test suite using:
  
mvn test

# ✅ Test Execution & Reporting

After test execution, logs can be found in app.log.

Extent Reports are generated inside the test-output/ folder.

Screenshots of failed tests are saved in the screenshots/ folder.

# 🔥 Future Enhancements

✅ Implement Data-Driven Testing using Excel/CSV.

✅ Integrate with Jenkins CI/CD.

✅ Add Docker support for running tests in containers.

# 🤝 Contributing

Feel free to fork this repository, raise issues, and 
submit pull requests to improve the framework.

# 📝 License

This project is licensed under the MIT License.

