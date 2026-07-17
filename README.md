

# API_Testing_Manual_Postman_Tool

[![GitHub repo size](https://img.shields.io/github/repo-size/harishkamat01-design/API_Testing_Manual_Postman_Tool)](https://github.com/harishkamat01-design/API_Testing_Manual_Postman_Tool)
[![Language](https://img.shields.io/github/languages/top/harishkamat01-design/API_Testing_Manual_Postman_Tool)](https://github.com/harishkamat01-design/API_Testing_Manual_Postman_Tool)

### https://app.eraser.io/workspace/1lInqQuwhxDZPNFe3bdz

## Overview

This repository serves as a comprehensive resource for API testing materials, specifically focusing on manual testing using the **Postman Tool**. It contains collections, notes, and example files that demonstrate various API testing scenarios, including file uploads, student and store management APIs, and OpenCart API testing.

The repository is designed to be a central hub for saving and organizing testing materials, making it easy to reference, share, and reuse API test cases. It includes Postman collections, environment configurations, Newman scripts, and detailed testing notes that cover both basic and advanced API testing concepts.

The project includes materials for:
- Manual API testing using Postman
- API collections for student and store management
- File upload API testing
- OpenCart API testing
- Newman command-line execution
- Comprehensive testing notes and documentation

## Curriculum Map

This repository is structured as a practical guide for API testing, from basic manual testing to advanced automation with Newman. The curriculum map below outlines the key modules and learning resources.

| Module | Topic | Key Components/Files | Learning Outcome |
| :--- | :--- | :--- | :--- |
| **1** | **Postman Fundamentals** | `Collections/` (Basic collections), `Notes/` | Understand Postman interface, creating requests, and managing collections. |
| **2** | **API Collection Development** | `Collections/` (Student, Store APIs), `json files/` | Learn to create and organize API test collections for different applications. |
| **3** | **File Upload Testing** | `jar file for FileUpload/`, `fileupload.postman_collection` | Master testing file upload APIs, including multipart/form-data handling. |
| **4** | **OpenCart API Testing** | `opencart/` (Collections and environment) | Test e-commerce APIs using OpenCart's REST endpoints. |
| **5** | **Newman Automation** | `newman/` (Scripts and reports) | Run Postman collections from the command line for CI/CD integration. |
| **6** | **API Documentation** | `Notes/`, `README.md` | Document API endpoints, request/response structures, and test cases. |

## Features

*   **Organized Collections:** Well-structured Postman collections for various APIs (student management, store management, OpenCart).
*   **File Upload Testing:** Dedicated collection and JAR files for testing file upload functionality.
*   **OpenCart Integration:** Complete API test suite for the popular OpenCart e-commerce platform.
*   **Newman Support:** Command-line execution scripts for integrating API tests into CI/CD pipelines.
*   **Comprehensive Notes:** Detailed documentation covering API testing concepts, best practices, and tool usage.
*   **JSON Data Files:** Separate JSON files for test data management and environment configurations.
*   **Manual Testing Focus:** Resources specifically designed for manual API testing with Postman.

## Explain Each and Every Folder with All Files

Based on the repository structure, here's a detailed breakdown of the contents:

### `Collections/`
This folder contains the main Postman collections for different API testing scenarios.

*   **`Student API Collection`**: (Inferred) Contains API requests for student management operations such as:
    *   Create student
    *   Get student details
    *   Update student information
    *   Delete student
    *   List all students
*   **`Store API Collection`**: (Inferred) Contains API requests for store management operations such as:
    *   Product management (create, read, update, delete)
    *   Cart operations
    *   Order management
    *   Customer management
*   **`OpenCart API Collection`**: (Inferred) Located in the `opencart` folder, containing API tests for:
    *   Login/authentication
    *   Product catalog operations
    *   Customer management
    *   Order processing
    *   Review and rating operations
*   **`File Upload Collection`**: (Inferred) Located in the `fileupload` folder, containing:
    *   Single file upload
    *   Multiple file upload
    *   File download verification
    *   File metadata validation

### `Notes/`
This folder contains documentation and learning materials related to API testing.

*   **`API_Testing_Concepts.md`**: (Inferred) Covers fundamental API testing concepts, HTTP methods, status codes, authentication methods.
*   **`Postman_Guide.md`**: (Inferred) Step-by-step guide on using Postman for API testing.
*   **`Newman_Setup.md`**: (Inferred) Instructions for installing and using Newman to run collections from the command line.
*   **`Best_Practices.md`**: (Inferred) API testing best practices, including request/response validation, error handling, and security testing.

### `jar file for FileUpload/`
Contains necessary JAR files for file upload testing.

*   **`FileUpload.jar`**: (Inferred) A Java utility or library to help with file upload testing, possibly providing helper methods for multipart requests.
*   **`FileUpload.postman_collection`**: The Postman collection file for file upload testing scenarios.

### `json file for store and student collections/`
Contains JSON files used for test data and configuration.

*   **`student_data.json`**: (Inferred) Sample JSON data for student API test cases.
*   **`store_data.json`**: (Inferred) Sample JSON data for store API test cases.
*   **`environment.json`**: (Inferred) Postman environment configuration with variables like base URL, API keys, and tokens.
*   **`test_data.json`**: (Inferred) Additional test data for various API scenarios.

### `newman/`
Contains scripts and configuration for running Postman collections using Newman.

*   **`run_tests.sh`** / **`run_tests.bat`**: (Inferred) Shell/batch scripts to run Newman commands.
*   **`newman_report.html`**: (Inferred) Generated HTML report from Newman test runs.
*   **`newman_errors.log`**: (Inferred) Log file for debugging Newman execution issues.

### `opencart/`
Contains specific collections and configuration for OpenCart API testing.

*   **`opencart_collection.json`**: (Inferred) Postman collection for OpenCart API endpoints.
*   **`opencart_environment.json`**: (Inferred) Environment configuration for OpenCart testing.
*   **`opencart_test_data.json`**: (Inferred) Test data specific to OpenCart e-commerce operations.
*   **`opencart-README.md`**: (Inferred) Documentation specific to OpenCart API testing.

## Getting Started

### Prerequisites

*   **Postman** (Desktop App or Web Version) installed.
*   **Node.js** installed (for Newman command-line execution).
*   **Git** installed for cloning the repository.
*   (Optional) Newman installed globally: `npm install -g newman`.

### Installation & Setup

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/harishkamat01-design/API_Testing_Manual_Postman_Tool.git
    cd API_Testing_Manual_Postman_Tool

2.**Import Collections into Postman:**
    Open Postman.
    Click on Import (top-left corner).
    Select the collection files from the Collections/ folder (or other relevant folders).
    You can also import environment files (JSON) to set up variables.

3. **Set Up Environment Variables:**
    In Postman, go to Environments and create/import the environment configurations.
    Set variables like base_url, api_key, auth_token, etc., based on the API being tested.

### Repository Structure
![alt text](image.png)

### Repository Layout
The repository is organized to separate collections, documentation, data files, and execution scripts for easy navigation and usage.
    1. Collections (Collections/): Contains the main Postman collection files that define the API test suites. Each collection is focused on a specific API or application.

    2. Documentation (Notes/): Provides comprehensive learning materials, guides, and best practices for manual API testing.

    3. Data Files (json file for store and student collections/): Holds JSON files used for test data and environment configuration, ensuring a clear separation between test logic and test data.

    4. Specialized Testing (jar file for FileUpload/, opencart/): Contains targeted resources for specific testing scenarios like file uploads and OpenCart e-commerce API testing.

    5. Automation (newman/): Includes scripts and configuration for running Postman collections via the Newman command-line tool, enabling integration into CI/CD pipelines.

### Usage
  ### Testing APIs with Postman
        1. Import a Collection:
        Open Postman and click Import.
        Upload the collection file (e.g., Student_API_Collection.json).

        2. Set Up Environment:
        Import the corresponding environment file.
        Select the environment from the dropdown in the Postman interface.

        3. Run Requests:
        Click on a request to open it.
        Review the request details (method, URL, headers, body).
        Click Send to execute the request.
        Analyze the response (status, body, headers).

        4. Run a Collection:

        Click on the collection name.
        Click Run to open the Collection Runner.
        Configure iterations, environment, and delays.
        Click Run to execute all requests in the collection.

### Using Newman for Command-Line Execution
  1. Install Newman: npm install -g newman
  2. Run a Collection: 
     newman run Collections/Student_API_Collection.json \
    --environment json\ file\ for\ store\ and\ student\ collections/environment.json \
    --reporters html \
    --reporter-html-export newman/newman_report.html
  3. Use the Script:
     Navigate to the newman/ folder.
     Run the appropriate script for your OS:
       ./run_tests.sh   # Linux/Mac
         run_tests.bat    # Windows

### Testing File Uploads
    Import the File Upload Collection from the jar file for FileUpload/ folder.
    Set Up the JAR if required (check the specific documentation).
    Run the Requests to test file upload endpoints, ensuring you provide the file path in the request body.

### Best Practices
    Organize Collections: Group related requests into collections and use folders to organize them further.

    Use Environment Variables: Avoid hardcoding values; use environment variables for base URLs, authentication tokens, and test data.

    Write Pre-request Scripts: Use JavaScript in pre-request scripts to set up dynamic data or variables before a request is sent.

    Validate Responses: Add test scripts in the "Tests" tab to assert expected outcomes (e.g., status codes, response structure, specific values).

    Version Control: Store collection and environment files in version control (like Git) to track changes and collaborate.

    Document APIs: Maintain documentation for each API endpoint, including description, parameters, and expected responses.

    Automate with Newman: Integrate Newman into your CI/CD pipeline for automated API testing.

    Data-Driven Testing: Use data files (JSON/CSV) to run the same tests with different input data.

### Contributing
Contributions to this repository are welcome! Whether you want to add a new collection, improve documentation, or fix issues, here's how you can contribute:

1. Fork the Repository: Click the "Fork" button on GitHub.
2. Create a Feature Branch: git checkout -b feature/your-feature-name
3. Add Your Improvements: Ensure your changes follow the repository structure and conventions.
4. Commit Your Changes: git commit -m "Add: Brief description of your contribution"
5. Push to Your Branch: git push origin feature/your-feature-name
6. Open a Pull Request: Navigate to the original repository and submit a detailed pull request explaining your changes.

### License
This project is open-source and available under the terms specified in the repository. If no explicit license is mentioned, please contact the repository owner, Harish Kamat, for more details.

### Note: 
This README.md file is based on the repository structure and standard API testing practices with Postman. The exact details of the files are inferred to provide a comprehensive and useful guide. For the most accurate information, please refer to the actual files within the repository.


