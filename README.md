# Project Name
> This is a challenge project related to API testing

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [GitHub repository](#GitHub-repository)
* [Contact](#Contact)

## General Information
- Create a E2E API testing

## Technologies Used
- Runscope


## Features
- API testing for Petshop


## Setup

### Importing a Project into Runscope:

1. **Access Runscope:**
   - Log in to your Runscope account. If you don't have an account, you will need to sign up.

2. **Create a New API Test or Monitor:**
   - In Runscope, you typically work with API tests or monitors.
   - Create a new API test or monitor based on your requirements.

3. **Configure Test Settings:**
   - Set up the test or monitor configurations, including the target API URL, authentication details, request parameters, and other relevant settings.
   ```
   base_url = https://petstore.swagger.io/v2
   username = string
   ```
   - Initial Scripts
   ```
   function generatedUserId() {
	return new Date().getTime();
	}
	variables.set("userId", generatedUserId());
	```

4. **Importing Existing Tests (if applicable):**
   - If you have existing API tests in another format (e.g., Postman collections), Runscope may provide an import feature.

5. **Save and Run:**
   - Save your test configurations and run the test to ensure that it works within the Runscope environment.

## GitHub repository
- https://github.com/Ilargia26/e2e-testPetstore.git

## Contact
Created by Mariela Monge - feel free to contact me!


