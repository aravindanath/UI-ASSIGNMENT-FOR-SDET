# 🧪 UI Automation Assignment – SDET (Frontend)

## 📌 Overview
This assignment is designed to assess your **problem-solving skills, test automation expertise, and object-oriented design abilities**. The goal is to create a robust **UI automation framework** for the website [Midtrans Demo](https://demo.midtrans.com/), implementing automated end-to-end test flows for credit card transactions.

---

## 🎯 Objectives

You are required to:

- Build a **UI automation framework** from scratch (Web or Mobile).
- Implement tests using **Selenium/Appium** with your choice of language stack (**Java/Python/JS/TS**).
- Deliver **clean, maintainable, and modular code**.
- Showcase **test reporting and cross-browser compatibility**.

---

## ✅ Requirements

### Must-Have Scenarios
1. **Successful Payment Flow:**  
   Automate end-to-end checkout for purchasing a **“Pillow”** using **Credit Card** with a **successful payment result**.

2. **Failed Payment Flow:**  
   Automate end-to-end checkout for purchasing a **“Pillow”** using **Credit Card** with a **failed payment result**.

3. **Reporting:**  
   Integrate a **reporting framework** of your choice to display test execution results.

4. **Cross-Browser Testing:**  
   Ensure tests run on **Chrome** and **Firefox**.

---

## 🔑 Test Data

| Payment Type              | Card Number          | Expiry Date | CVV | Bank OTP |
|--------------------------|----------------------|-------------|-----|----------|
| Success Credit Card      | 4811 1111 1111 1114  | 02/20       | 123 | 112233   |
| Failed Credit Card       | 4911 1111 1111 1113  | 02/20       | 123 | 112233   |

---

## 🛠 Tech Stack Recommendations

- **Automation Tool:** Selenium / Appium  
- **Framework:** TestNG / JUnit / Cucumber (Java) or PyTest / Playwright (Python/JS)  
- **Build Tool:** Maven / Gradle (Java) or equivalent  
- **Reporting:** Allure / Extent Reports or similar  

---

## 📂 Submission Guidelines

1. **Project Folder:**  
   - Name the folder with **your name**.  
   - Include:
     - Source code and test scripts  
     - Framework files  
     - Test reports  
     - `README.md` with instructions and assumptions

2. **Version Control:**  
   - Maintain a **local Git repository** with **frequent, clear commits** showing solution evolution.  
   - Share the final project as a **zipped folder** or via a **Google Drive link** (ensure public access).

---

## ⚠️ Rules of the Game

- You have **2 full days** to complete the task.
- **Do NOT publish** the solution on public GitHub/GitLab repositories or forums.
- Code must be **original**—plagiarism may lead to rejection.
- Avoid excessive use of `Thread.sleep()`; use **proper waits** instead.
- Write **meaningful assertions** to validate test results.
- Use **intuitive class and function names** with comments explaining the **WHY**, not the **WHAT/HOW**.

---

## 💡 Bonus Tips

- Keep tests **atomic and fast**.
- Follow **clean coding practices** for maintainability.
- Use **design patterns** like Page Object Model (POM) where appropriate.
- Remember Martin Fowler's advice:  
  *“Any fool can write code that a computer can understand. Good programmers write code that humans can understand.”*

---

## ✅ Deliverables Checklist

- [ ] End-to-end test for **successful payment**  
- [ ] End-to-end test for **failed payment**  
- [ ] Reporting framework implemented  
- [ ] Cross-browser execution validated  
- [ ] Proper folder structure and documentation  
- [ ] Zipped project folder with `README.md` included  
