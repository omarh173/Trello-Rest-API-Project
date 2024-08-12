# Trello API Testing Project

## 🔎 Test Scope

This project tests various aspects of the Trello API based on the API documentation. The tests cover the following areas:

### Board
- **Create a Board**
- **Get a Board**
- **Update a Board**

### List
- **Create a List on a Board**
- **Get Lists on Board**
- **Update a List**
- **Archive All Cards in a List**

### Card
- **Create a New Card**
- **Get a Card on a Board**
- **Update a Card**

### Checklist
- **Create Checklist on a Board**
- **Get Checklists on a Board**
- **Create Checkitem on Checklist**

### Delete
- **Delete a Checklist on a Card**
- **Delete a Card**
- **Delete a Board**

## 🚀 Getting Started

### 📌 Steps to Run Collection and Tests

1. **Postman Installation**
2. **Creating a Trello Account**
3. **Trello Authentication**
4. **Importing a File into Postman**
5. **Creating Environment Variables in Postman**
6. **Running the Collection and Testing**

### 💻 Postman Installation

1. Go to the [Postman website](https://www.postman.com/downloads/) and click the download button for your operating system.
2. Download the installation file, then run the installer and follow the on-screen instructions.
3. Postman is now ready to use.

### 📅 Creating a Trello Account

1. Go to the [Trello website](https://trello.com) and click the "Get Trello for free" button.
2. Follow the instructions to create a Trello account.
3. Your Trello account is now ready.

### 🔑 Trello Authentication

1. Log in to your Trello account.
2. Navigate to the [Trello API key generation page](https://trello.com/app-key).
3. Click "Go to the Power-Up Admin Portal," then click "Create New Key" and fill in the required details.
4. Copy and save your API key displayed on the page.
5. Click on the Token link under the key you just generated.
6. Allow the application to access your Trello account.
7. Copy and save your token displayed on the page.

### 📂 Importing a File into Postman

1. Download the Postman collection file.
2. Open Postman and click the "Import" button in the top left corner.
3. Drag and drop the downloaded file into the "Import" window.
4. The collection will appear in Postman, ready for use.

### 🌍 Creating Environment Variables in Postman

1. Click the "Environment" dropdown in the top left corner of Postman.
2. Click "New" to create a new environment and select the "Environment" icon.
3. Name your environment.
4. Create variables: "key", "token", and "baseURL". Set the value of "baseURL" to `https://api.trello.com`, and enter your key and token values for the "key" and "token" variables.
5. Click "Save" to save the environment.
6. Select the newly created environment from the "Environment" dropdown.

### 🏃 Running the Collection and Testing

1. Click the "Collections" icon in Postman.
2. Select the "Trello REST API" collection from the list.
3. Click the three dots icon next to the collection name and choose "Run Collection".
4. Click the "Run Trello REST API" button.
