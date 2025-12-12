# Playwright-Automation
This repository contains an end-to-end test automation framework built using Microsoft Playwright. The project is designed to provide reliable, scalable, and maintainable UI automation for modern web applications

🚀 Features

✔️ Cross-browser testing (Chromium, Firefox, WebKit)

✔️ Page Object Model (POM) structure

✔️ Auto-generated HTML reports

✔️ Video, trace, and screenshot capture

✔️ Environment-based configurations

✔️ Easy integration with CI/CD (GitHub Actions)

✔️ Supports TypeScript/JavaScript (choose your setup)

📦 Installation

    1. Clone the Repository
       git clone https://github.com/<your-username>/<repo-name>.git
       cd <repo-name>

    2. Install Dependencies
        npm install
     
    3. Install Playwright Browsers
        npx playwright install

▶️ Running Tests

    1. Run all tests
        npx playwright test

    2. Run tests with UI mode
        npx playwright test --ui

    3. Run a specific test file
        npx playwright test tests/example.spec.ts

    4. Run headed mode (visible browser)
        npx playwright test --headed
