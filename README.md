# 🔐 Login Test Automation | Java + Selenium

### Welcome to my QA Automation Lab! 👩🏽‍💻✨

**Great software doesn't happen by accident. It gets tested.**

Welcome to my Login Test Automation project! I'm a Software Quality Engineer passionate about building reliable applications, catching defects before users encounter them, and making software testing smarter through automation.

This project showcases my approach to designing, organizing, and executing automated UI tests using **Java, Selenium WebDriver, TestNG, and Maven**.

The mission? Simple: **Test smarter. Catch bugs earlier. Deliver with confidence.** 🚀

---

## 🛠️ My Automation Toolkit

| Technology | Purpose |
|---|---|
| ☕ Java | Automation programming language |
| 🌐 Selenium WebDriver | Browser interaction and UI automation |
| 🧪 TestNG | Test organization and execution |
| 📦 Maven | Dependency management and build configuration |
| 🏗️ Page Object Model | Separation of page elements and test logic |
| 📊 ExtentReports | Test execution reporting |
| 📁 CSV | External test data management |
| 💻 VS Code | Development environment |

## 🎯 What's Being Tested?

This project focuses on automating the login functionality of a practice web application.

The framework is designed to demonstrate how UI tests can be organized with reusable components, external test data, and reporting utilities.

Rather than placing every automation step into one large test script, the project separates responsibilities across multiple classes.

**Because maintainable automation is just as important as making a test pass.**

## 🏗️ Behind the Automation

The project includes several components that support a structured automation approach:

- **LoginTest.java:** Login test execution
- **LoginActions.java:** Reusable login actions
- **LoginObjects.java:** Login page objects
- **BaseTest.java:** Shared test setup and functionality
- **DriverFactory.java:** Browser driver management
- **TestDataReader.java:** External test data handling
- **WaitUtils.java:** Synchronization utilities
- **ExtentManager.java:** Reporting support
- **Logger.java:** Logging utilities

## 📂 Project Structure

```text
login-test-automation/
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── actions/
│   │   │   ├── base/
│   │   │   ├── driver/
│   │   │   ├── pages/
│   │   │   ├── reports/
│   │   │   └── utils/
│   │   └── resources/
│   │       ├── config.properties
│   │       └── loginData.csv
│   └── test/
│       └── java/
│           └── tests/
│               ├── LoginTest.java
│               └── testng.xml
└── README.md
```

## ▶️ Running the Automation

**Prerequisites**

- Java JDK
- Maven
- Compatible web browser
- Browser driver configuration supported by the project

**Getting Started**

1. Clone this repository.
2. Open the project in VS Code or another Java-compatible IDE.
3. Install the Maven dependencies.
4. Review `config.properties` for environment configuration.
5. Run the tests using the project's configured TestNG execution setup.

Test results can be reviewed using the reporting functionality included in the framework.

## 💡 What This Project Demonstrates

Beyond automating a login page, this project reflects important quality engineering practices:

- Building reusable test automation components
- Organizing UI automation using the Page Object Model
- Separating test data from test logic
- Managing dependencies with Maven
- Structuring test execution with TestNG
- Supporting troubleshooting through logging and reporting

## 👩🏽‍💻 Meet the Engineer Behind the Tests

**Morgan Davis | Software Quality Engineer**

Howdy! I'm a quality-focused technology professional with nearly six years of experience in software testing and quality engineering.

My professional background includes manual and automated testing, Agile collaboration, defect management, test planning, and supporting software releases.

I enjoy the intersection of technical problem-solving and user experience, where thoughtful testing helps transform complex software into dependable products.

This repository is part of my growing automation portfolio, where I demonstrate my technical skills, strengthen my framework development practices, and continue exploring modern quality engineering techniques.

**Thanks for stopping by! Feel free to explore the code.** 🚀

---

### ✨ My QA Philosophy

*Quality isn't just about finding what's broken. It's about building confidence in what works.*
