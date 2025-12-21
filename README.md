# Automation

A concise, technical automation repository containing test suites and supporting tooling for validation of core product workflows.

Status
- Purpose: Automation QA — reliability-focused functional and API tests.
- Stack: Java · TestNG · Maven · REST-assured · Selenium/Appium (as applicable)
- CI: GitHub Actions running tests and publishing JUnit/Allure artifacts.

Quick start
1. Prerequisites
   - Java 11+ and Maven (or the repo's build tool)
2. Clone and run
   ```bash
   git clone https://github.com/PuneetQA/Automation.git
   cd Automation
   mvn -B clean test
   ```
3. Local report
   - Allure (if configured): mvn allure:serve
   - JUnit XML: target/surefire-reports/*.xml

What's inside
- src/test/java — Test suites and utility code
- pom.xml / build.gradle — Build & dependencies
- docs/ — Optional test output, screenshots, demo GIFs

CI / Reporting
- CI uploads JUnit XML and Allure results as artifacts. See the Actions tab for recent runs.
- Badge(s) in top-level README will reflect build status and test coverage (when available).

Contribution notes
- Branch naming: feat/feature-name, fix/bug-name, etc.
