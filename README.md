# Story-Spoiler-API-Automation-Testing
This repository contains automated API tests for the Story Spoiler platform. The goal of this project is to automate the testing of various API endpoints related to user authentication and story spoiler management.

## Project Overview
The Story Spoiler platform allows users to log in, create, update, search, and delete story spoilers. This project automates the validation of these functionalities using an API testing framework.

## APIs Covered:
- Login and Authentication: Allows users to authenticate via a username and password.
- Create Story Spoiler: Enables users to create new story spoilers.
- Search Story Spoilers: Fetches spoilers based on search criteria.
- Edit Story Spoiler: Updates an existing spoiler.
- Delete Story Spoiler: Deletes a story spoiler.
  
## Automated API Endpoints
The following API endpoints are covered in the automated tests:

POST /api/User/Authentication: Authenticates a user.
POST /api/Story/Create: Creates a new story spoiler.
GET /api/Story/Search: Searches for a specific spoiler.
PUT /api/Story/{id}: Updates an existing spoiler.
DELETE /api/Story/{id}: Deletes a spoiler.

## Tools & Technologies
Postman/Newman: Used for creating and running API tests.
JavaScript/TypeScript: Programming language used for automation scripts.
GitHub: Version control and repository management.
CI Tool (if applicable): Continuous integration for running automated tests.

## How to Use
1. Clone the repository:

git clone https://github.com/yourusername/StorySpoiler-API-Testing.git

2. Run the automated tests:

newman run StorySpoilerAPI.postman_collection.json

3. View the results in the terminal or CI pipeline.

## Test Cases

1. Login and Authentication: Validates successful user login.
2. Create Story Spoiler: Automates the creation of a new spoiler.
3. Search Story Spoiler: Searches for the created spoiler.
4. Edit Story Spoiler: Verifies the ability to update the spoiler.
5. Delete Story Spoiler: Ensures the spoiler is deleted successfully.
