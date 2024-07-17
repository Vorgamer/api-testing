# API Testing Repository

This repository contains a collection of API tests and environment variables for testing using Postman.

## Contents

- `API Testing.postman_collection.json`: The collection of API tests.
- `API Testing.postman_environment.json`: The environment variables for the tests.

## Overview

This repository uses the Open API from [GoRest](https://gorest.co.in/). The tests are designed to interact with the endpoints provided by GoRest.

## Prerequisites

- Postman installed on your system. You can download it from [Postman's official website](https://www.postman.com/downloads/).

## Instructions

### Importing the Collection and Environment Variables

1. **Download the Repository:**
   Clone or download the repository to your local machine.

2. **Open Postman:**
   Launch the Postman application.

3. **Import the Collection:**
   - Click on the `Import` button in the top-left corner of Postman.
   - Select the `Upload Files` tab.
   - Browse to the location of the `API Testing.postman_collection.json` file and select it.
   - Click `Open` to import the collection.

4. **Import the Environment Variables:**
   - Click on the `Import` button in the top-left corner of Postman.
   - Select the `Upload Files` tab.
   - Browse to the location of the `API Testing.postman_environment.json` file and select it.
   - Click `Open` to import the environment variables.

### Setting Up the Bearer Token

To execute the requests in the collection, you need to set up the Bearer Token. Follow these steps:

1. **Obtain a Bearer Token:**
   - Visit [GoRest Access Tokens](https://gorest.co.in/my-account/access-tokens).
   - Log in using Google, GitHub, or Microsoft.
   - Generate a new access token or use an existing one.

2. **Set the Bearer Token in Postman:**
   - In Postman, click on the `Environment Quick Look` (the eye icon in the top-right corner).
   - Find the `API Testing` environment.
   - Click the `Edit` button (the pencil icon).
   - Add a new variable named `bearerToken` if it doesn't exist.
   - Set the value of `bearerToken` to the token you obtained from GoRest.
   - Click `Update` to save the changes.

### Running the Tests

1. **Select the Environment:**
   - In Postman, click on the `Environment Quick Look` (the eye icon in the top-right corner).
   - Select the `API Testing` environment from the dropdown list.

2. **Run the Collection:**
   - Go to the `Collections` tab in Postman.
   - Find the `API Testing` collection.
   - Click the `Run` button to open the Collection Runner.
   - Click `Start Run` to execute the tests.

## Conclusion

You have successfully imported the API test collection and environment variables, set up the Bearer Token, and run the tests using Postman. If you encounter any issues or have any questions, please refer to the Postman documentation or reach out for support.

Happy Testing!
