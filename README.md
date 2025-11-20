# E-Commerce Web Application QA

End-to-end **quality assurance project** for an e-commerce style web application, covering:
- Manual test design & execution
- UI regression testing
- Automation of critical paths using **Cypress**
- Basic API checks using **Postman**

This project is one of the core portfolio items referenced in my **CV** and **QA portfolio website**.

---

## 🎯 Objectives

- Design realistic test scenarios for core e-commerce flows:
  - Login / Logout
  - Product browsing & filters
  - Cart management
  - Checkout flow
- Convert critical test cases into **Cypress automation**.
- Document bugs clearly (steps, expected vs actual, severity).

---

## 🧰 Tech Stack

- **Cypress** (UI automation)
- **JavaScript** (Mocha/Chai style tests)
- **Postman** (basic API checks)
- **Git & GitHub**

---

## 📂 Structure (example)

```text
ecommerce-webapp-qa/
├─ cypress/
│  ├─ e2e/
│  │  ├─ login.cy.js
│  │  ├─ product-list.cy.js
│  │  ├─ cart.cy.js
│  │  └─ checkout.cy.js
│  ├─ fixtures/
│  ├─ support/
│  │  ├─ commands.js
│  │  └─ e2e.js
├─ docs/
│  ├─ test-cases.xlsx
│  └─ bug-report-samples.md
├─ cypress.config.js
├─ package.json
└─ README.md
✅ Test Coverage
Authentication (valid & invalid credentials)

Product listing, search, sorting, filters

Cart add/remove/update

Checkout with field validations

Basic negative tests (empty cart, invalid form data)

🚀 Running the Tests
1. Clone & Install
bash
Copy code
git clone https://github.com/Micharemu/ecommerce-webapp-qa.git
cd ecommerce-webapp-qa
npm install
2. Run Cypress
bash
Copy code
# Open Cypress UI
npm run cypress:open

# OR headless run
npm run cypress:run
(Adjust to match your package.json scripts.)

