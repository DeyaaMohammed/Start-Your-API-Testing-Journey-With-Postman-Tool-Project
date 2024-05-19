# Start Your API Testing Journey With Postman Tool - API Testing using Postman
This repository contains resources related to the "Start Your API Testing Journey With Postman Tool" guided project. Here, you'll find the Postman collections and environments created.

- [Introduction](#introduction)
- [Learning Milestones](#learning-milestones)
- [Technologies Used](technologies-used)
- [Add-ons](#add-ons)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributions](#contributions)
- [Disclaimer](#disclaimer)

## Introduction
The "[Start Your API Testing Journey With Postman Tool](https://www.coursera.org/projects/start-your-api-testing-journey-with-postman-tool)" allowed me to practice writing scripts to test APIs using Postman, how to test CRUD (Create, Read, Update, and Delete) operations with HTTP methods like GET, POST, PUT and DELETE, understanding JSON request and response, and adding assertions to the API response.

## Learning Milestones
- Sending a GET request
- Understanding the JSON response and adding filters to the GET request
- Adding user-defined variables
- Sending a POST request
- Sending a PUT and DELETE requests
- Adding assertions to the JSON response
- Generating reports using Newman

## Technologies Used
- [API Playground](https://github.com/BestBuy/api-playground)
- [Postman](https://www.postman.com/)
- [NodeJS](https://nodejs.org/en)
- [newman](https://www.npmjs.com/package/newman)
- [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)

## Add-ons
In addition to the functionalities covered in the guided project, I've made the following custom additions to the collections:
- Added multiple assertions to evaluate the integrity of the JSON response and enhance the test results.
- Extracted the product ID embedded within the JSON response, which serves as input for the subsequent test cases.
- Created environment variables for flexible test configuration.
- Generated an HTML report using Newman for a more user-friendly and visually appealing way to showcase the test results.

## Directory Structure
- `newman/`: The directory where HTML Reports are located.
  - `HTML_Report.html`:  This HTML file provides a detailed overview of the test execution results.
- `BestBuyAppAPI.postman_collection.json`: This file contains a collection of API requests, organized and grouped for testing the JSON Server API. It is used to perform various API tests.
- `LocalhostInstance.postman_environment.json`: This file stores the environment-specific variables and configurations used for the local testing environment. This is the environment selected to test the API using Newman.

## Getting Started
1. Install Postman: [https://www.postman.com/downloads/](https://www.postman.com/downloads/)
2. Install API Playground: [https://github.com/BestBuy/api-playground](https://github.com/BestBuy/api-playground)
3. Import Collections:
    - Download the entire repository or specific files.
    - In Postman, open `"File"` -> `"Import"` -> `"Select Files"` and choose the downloaded files.
4. Configure Environments:
    - Choose the appropriate environment file for your testing environment (e.g., "LocalhostInstance.postman_environment.json").
    - Go to `"File"` -> `"Import"` -> `"Select Files"` and select the chosen file.
5. Run Tests:
    - Within the collection, you can run individual requests or the entire collection.


## Usage
You can go ahead and explore my collections and environments. Feel free to use these collections as reference, study materials, or review materials to enhance your understanding of Postman.

## Contributions
Contributions to this repository are welcome. If you have alternative code implementations, suggestions for improvements please consider submitting a pull request. If you encounter any issues with my implementation or have additional insights to share, please open an issue.

## Disclaimer
> This is not the official implementation.
