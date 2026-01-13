# Playwright Non-BDD Test Automation Framework
## 1. Overview
This repository contains a Playwright test automation framework implemented using TypeScript. 
The framework is designed with focus on:
- High maintainability and scalability

- Fast feedback and efficient debugging

- Clear ownership by engineering/SDET teams

- Easy migration from Cypress-based frameworks

The framework intentionally avoids Gherkin/Cucumber and instead relies on descriptive test cases, Page Object Model (POM), Facade pattern, and explicit workflows.

## 1. Key Design Principles

- Non-BDD by design: No feature files or step definitions

- Playwright-native: Uses Playwright Test Runner directly

- Explicit over implicit: No hidden command chaining

- Separation of concerns:

 - Tests describe behavior

 - Pages describe UI interactions

 - Facades describe business workflows

- Custom data attributes for locators (data-testid)

## 1. Prerequisites
Ensure the following are installed on your machine
 
### System Requirements
- Node.js v18+
- npm v9+ (or yarn if preferred)
- Git
- Jave (required for Allure reports)

Verify installation
 ```
node --version
npm --version
java -version
 ```

 ## 1. Tech Stack
 - Language: TypeScript
 - Test Runner: Playwright Test
 - Design Patterns:
   - Page Object Model (POM)
   - Facade Pattern
   - Singleton (where explictly needed)
 - Reporting: Allure
 - IDE: Visual Studio recommended


## 1. Cloning the Repository

### Clone Repo:
```
git clone <repository-url>
cd playwright-framework
```

### Install Dependencies:
```
npm install
```

### Install Playwright Browsers
```
npx playwright install

```

## 1. Running Tests




## 1. Reporting (Allure)


## 1. What this Framework Is Not
- Not a BDD framework
- Not business-authored documentation
- Not Cypress-style implicit execution

## 1. Support & Contribution

- Follow existing patterns strictly
- Discuss architectural changes before implementation
- Keep test readability a priority


## 1. Final Note
This framework prioritise clarity, speed an dlong term maintaninability. It is designed for SDETs who own their automation and value signal over ceremony.

For question or improvement, raise a PR or start design discussion. 