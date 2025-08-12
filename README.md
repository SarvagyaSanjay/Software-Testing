# 🛠 End-to-End QA Automation for E-Commerce Web Applications

![Automation Testing](https://img.shields.io/badge/QA-Automation-blue)
![Selenium](https://img.shields.io/badge/Selenium-Python-green)
![PyTest](https://img.shields.io/badge/TestRunner-PyTest-yellow)

---

## 📌 Project Summary
This project presents a **comprehensive Quality Assurance (QA) strategy** for **three demo e-commerce web applications**.  
The goal was to **ensure reliability, functionality, and robustness** of critical user journeys through a **hybrid testing approach**.  

- ✅ Manual testing for baseline verification.  
- 🤖 Python-based **automation framework** using **Selenium** & **PyTest** for regression testing.  
- 🔍 Tested 15+ critical user flows including authentication, session management, cart operations, and checkout.  

---

## 🎯 Objectives
- 🧪 Perform thorough **manual testing** to identify bugs and understand workflows.
- 📜 Design **positive (happy path)** & **negative (edge case)** test scenarios.
- 💻 Develop a **maintainable automation framework** using Python + Selenium.
- ⚡ Automate regression suite for **Login, Registration, Add to Cart, Checkout**.
- 🔐 Validate form handling, data integrity, and session management.

---

## 💻 Tech Stack & Tools
| Category | Tools |
|----------|-------|
| **Automation Language** | Python 3.9 |
| **Framework** | Selenium WebDriver |
| **Test Runner** | PyTest |
| **Browser Management** | WebDriver Manager |
| **Version Control** | Git & GitHub |
| **Test Case Management** | Google Sheets / Zephyr Scale |
| **Applications Tested** | saucedemo.com, demoblaze.com + 1 more |

---

## 📂 Project Architecture
graph TD
    A[QA_Automation_Project] --> B[pages/]
    A --> C[tests/]
    A --> D[utils/]
    A --> E[requirements.txt]

    B --> B1[login_page.py]
    B --> B2[home_page.py]
    B --> B3[cart_page.py]

    C --> C1[test_login.py]
    C --> C2[test_cart_workflow.py]

    D --> D1[config.py]
    D --> D2[helpers.py]
    ## 🔄 Workflow Diagram

---

    
```mermaid
flowchart TD
    A([Manual Testing Phase]) --> B[Design Test Cases]
    B --> C[Execute Tests Manually]
    C --> D[Identify Bugs & Document Findings]
    D --> E[Build Automation Framework]
    E --> F[Implement Page Object Model (POM)]
    F --> G[Automate Critical User Flows]
    G --> H[Run Automated Regression Suite]
    H --> I[Generate Test Reports]
    I --> J[Integrate with CI/CD Pipeline]



