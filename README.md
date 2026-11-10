# Hi, I'm Patrick Aguiar 👋

**QA Engineer** focused on test automation and on finding risks before they reach users.
Open to **remote QA roles (LATAM)** · Fluent English · Based in Brazil.

## What I do

- **Test design:** equivalence partitioning, boundary value analysis, decision tables and exploratory testing (charters, SBTM)
- **API testing:** Postman and automated suites in JavaScript (Mocha, Supertest, Chai), guided by the VADER heuristic
- **Web E2E automation:** Cypress with custom commands, fixtures, API-based test data and HTML reports
- **Performance testing:** k6 with NFRs as thresholds (p95/p99), load, stress and spike profiles
- **Accessibility and responsiveness:** axe-core (WCAG), mobile and tablet viewports
- **Agile teams:** refinement, Jira, Gherkin scenarios, clear bug reports with severity and priority, Git and pull requests

## Portfolio: end-to-end quality of one product

Three projects testing the same e-commerce ([ServeRest](https://github.com/ServeRest/ServeRest)) at different layers,
all running in CI with GitHub Actions:

| Project | Layer | Stack | Highlights |
|---|---|---|---|
| [serverest-api-tests](https://github.com/patrick-aguiar-qa/serverest-api-tests) | REST API | Mocha · Supertest · Chai | 53 tests · auth/authorization, data validation, boundary values · 3 bugs reported |
| [serverest-web-cypress](https://github.com/patrick-aguiar-qa/serverest-web-cypress) | Web UI | Cypress · axe-core | 35 tests · sessions, calculations, accessibility, responsiveness · 9 bugs reported |
| [serverest-k6-performance](https://github.com/patrick-aguiar-qa/serverest-k6-performance) | Performance | k6 | Smoke, load, stress and spike · found the spike where p99 breaks the 1 s target |

**88 automated tests** and **12 documented bugs** — including security issues (passwords exposed in a JWT,
in API responses and in the admin UI), a broken mobile menu and a customer reaching the admin area.

## Tools

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Cypress](https://img.shields.io/badge/Cypress-69D3A7?logo=cypress&logoColor=black)
![k6](https://img.shields.io/badge/k6-7D64FF?logo=k6&logoColor=white)
![Mocha](https://img.shields.io/badge/Mocha-8D6748?logo=mocha&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

## How I approach testing

1. Understand the rule and ask the PO about anything ambiguous before testing.
2. List the risks: what can go wrong for the user and for the business.
3. Design the checks with formal techniques, then explore what the requirements do not say.
4. Automate what repeats, so every change gets fast feedback in the pipeline.
5. Report what I find with evidence, impact and a clear recommendation.
