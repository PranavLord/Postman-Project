# Postman CRUD Project

This project demonstrates how to automate CRUD (Create, Read, Update, Delete) operations using Postman on a free public library API.

## About the Project
In this project, we automate CRUD operations on a free library API using Postman. The project includes the creation of two environments:
- **QA (Quality Assurance) Environment**
- **UAT (User Acceptance Testing) Environment**

These environments help test the API in different stages, ensuring smooth transitions between development and production. Postman was used as the primary tool to manage and execute these operations.

## Technologies Used
- **Postman**: API testing and automation tool
- **Free Library API**: A public API for managing and interacting with library data
- **QA Environment**: A testing environment for quality assurance
- **UAT Environment**: A testing environment for user acceptance testing

## Objectives:
- Automate CRUD operations on the Free Library API using Postman.
- Set up different environments (QA and UAT) for testing.
- Ensure the API functions as expected in both environments.
- Provide sample Postman collections for easy execution of CRUD operations.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/PranavLord/Postman-Project.git

2. Navigate to the project directory:

cd Postman-Project

3. Import the Postman collection into the Postman app
    Open Postman.
    In the left sidebar, click on the gear icon next to "Collections".
    Click on "Import", select the postman_collection.json file, and import it.

4. Set up the QA and UAT environments
   In Postman, go to the "Environments" section.
    Import the QA_environment.json and UAT_environment.json files for configuring the environments.

5. Run the collection
   Once the environment is set up, execute the requests in the collection to perform CRUD operations on the Free Library API.
