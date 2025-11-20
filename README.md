# ServRest
API Test creation with Newman & Postman


## API TEST - CI/CD

This repository was created for an API Test Bootcamp


## Technologies:
- Postman web version

- Newman 6.2.1

- Newman - reporter - html

- Node v24.11.1

## Documentation:
[Swagger](https://serverest.dev )

## Testing Environment Setup Guide:

This guide will help you set up the necessary environment to run the API tests for this project.

Prerequisites

1. Install Node.js
   · Download and install Node.js on your computer. This will also install npm (Node Package Manager), which is required for the next steps.
   · 📥 Download Link: https://nodejs.org/en/download
2. Install Newman (Global Installation)
   · Newman is a command-line collection runner for Postman. Install it globally on your system using npm.
   · Run the following command in your terminal or command prompt:
   bash
   npm install -g newman


 ## How to Run Tests

You can execute the tests in two ways: via the Postman application or directly from the command line using Newman.

1. Using Postman (Web or Desktop App)

· Import the Collection and Environment files into your Postman workspace.
· You can then run the tests manually within the Postman app or set up automated runs.

2. Using the Command Line (Recommended for Automation)

This is the preferred method for automated testing and CI/CD pipelines.

1. Open your preferred terminal or command prompt.
2. Navigate to the directory containing your collection and environment files.
3. Run the following command:

bash
newman run ServeRestAPI.postman_collection.json -e ServeRestAPI_env.postman_environment.json --env-var "BaseURL=https://serverest.dev" -r cli,html

 
   
4. (Optional) Install the HTML Reporter for Newman
   · For generating detailed and visually appealing HTML reports, you can install the newman-reporter-html package.
   · Run the following command in your terminal or command prompt:
   bash
   npm install -g newman-reporter-html


## Contact:
email: travassos1985@gmail.com
Linkedin: www.linkedin.com/in/patricia-travassos-oliveira



   
