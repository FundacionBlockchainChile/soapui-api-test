# SoapUI API Test Project

This project contains automated API tests for the JSONPlaceholder Users endpoint using SoapUI.

## Requirements

- Java 8 or higher
- SoapUI 5.7.0 or higher (ReadyAPI)
- Maven

## Project Structure

```
.
├── README.md
├── pom.xml
└── src
    └── test
        └── resources
            └── JSONPlaceholder-Users-soapui-project.xml
```

## Running Tests

To run the tests locally:

```bash
mvn clean test
```

## GitHub Actions

The tests are automatically executed on push and pull requests using GitHub Actions. Check the `.github/workflows` directory for the workflow configuration. 