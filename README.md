# Postman API Testing

## 📌 Overview  
This project uses **Postman** for automating API tests with **BDD (Cucumber)**. It supports operations like **GET, POST, PUT, PATCH, DELETE** with tools like **Newman** for running collections in the command line. It also includes **Mocking API responses** using Postman Interceptor.

## 🛠 Installation  

1. **Clone the repository**  
   ```sh
   git clone https://github.com/MaksuraM/PostmanAPITesting.git
   cd PostmanAPITesting
2. **Install dependencies**  
   
sh
   npm install -g newman

## 🚀 Running Tests  
### Run the Collection
Run Postman tests using Newman:  
sh
   newman run AutomateTC.postman_collection.json

### Run the Collection with HTML Report
Generate an HTML report after running the tests:
sh
  newman run AutomateTC.postman_collection.json -r html

The report will be saved in a folder named newman.

## 📂 Project Structure
bash
    PostmanAPITesting/
│── AutomateTC.postman_collection.json    # Postman collection file with all API tests
│── README.md                             # This file
│── newman/                               # Folder to store Newman run reports (optional)

##📌 Dependencies
Ensure Newman is installed globally for running collections from the command line.

To install Newman, run:
sh
 npm install -g newman

## npm install -g newman
sql
   
This structure should match the layout of your Postman API Testing repository and guide users through setup, running tests, and viewing reports. You can copy and paste this into your `README.md` file and push it to your GitHub repository!
