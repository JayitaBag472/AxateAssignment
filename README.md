# AxateAssignment
AxateAssignment

## Install

```bash
npm install
```

- Install VS Extensions - Cucumber (Gherkin) Full Support
- Install VS Extensions - Feature Syntax Highlight and Snippets (Cucumber/Gherkin)
- Perform below steps to Add Step Definitions Path to link feature File with Step definitions
  1. Go to VS Code Settings
  2. Search for "Step de" and Refer the snapshot ![Alt text](static/images/image.png)
  3. Remove all the existing code and Add below code snippet inside both User and Workbook settings inside Cucumber Autocomplete settings.json
     ```bash
     {
      "cucumberautocomplete.syncfeatures": true,
      "cucumberautocomplete.steps": [
      "features/step-definitions/*.js",
      ]
     }
     ```

## Test Implementation Info

- BDD Feature files for E2E Journey for Chatbot needs to be written in ./features/feature-files/axate_website/user-registration.feature


## Run Tests

- Execute test

```bash
npm run test       < To run Whole Suite >
npm run test-web   < To run Web specific tests >
npm run test-api   < To run Api specific tests >
```

# Reports

- BDD Test Execution reports can be found in reports/bdd-results/html-reports/index.html
