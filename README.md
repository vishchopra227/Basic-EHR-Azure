# 🏥 Electronic Health Record (EHR) Web Application

A simple, lightweight **Electronic Health Record (EHR)** web application developed using HTML, CSS, and JavaScript and deployed using **Microsoft Azure Static Web Apps**.

This project demonstrates how a basic healthcare record management system can be designed, developed, and deployed using modern web technologies and cloud hosting.

## 🌐 Live Demo

**[Visit the EHR Web Application](https://mango-glacier-0704e7800.3.azurestaticapps.net/)**

## 📌 Project Overview

The Electronic Health Record (EHR) application provides a basic interface for entering, storing, viewing, and searching patient information.

It is developed as an educational demonstration to understand frontend web development, browser-based data storage, and cloud application deployment using Microsoft Azure.

## ✨ Features

- **Patient Registration:** Add patient information through a simple entry form.
- **Patient ID Management:** Enter unique patient identifiers using letters, numbers, and hyphens.
- **Patient Details:** Record patient name, age, and clinical notes.
- **Patient Records:** View saved patient information in a structured table.
- **Search Functionality:** Search and filter records using patient ID or name.
- **Browser Storage:** Store records locally using the browser's Local Storage.
- **Cloud Deployment:** Access the application online through Microsoft Azure Static Web Apps.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the web application |
| CSS3 | Styling and user interface design |
| JavaScript | Application logic and interactivity |
| Local Storage | Browser-based patient record storage |
| GitHub | Source code management |
| Microsoft Azure | Cloud hosting and deployment |
| PowerShell | Command-line deployment and configuration |

## ⚙️ How It Works

1. Open the EHR application using the live deployment link.
2. Enter the Patient ID, Patient Name, Age, and Clinical Notes.
3. Click the **Add Patient Record** button.
4. The patient information is stored in the browser's Local Storage.
5. The saved patient records are displayed in the Patient Records section.
6. Use the search field to find a particular patient by ID or name.

## ☁️ Deployment on Microsoft Azure

The application is hosted using **Microsoft Azure Static Web Apps**.

The deployment workflow involves:

1. Developing the EHR webpage using HTML, CSS, and JavaScript.
2. Creating a GitHub repository and uploading the source code.
3. Creating an Azure Static Web App resource.
4. Configuring the application and deployment settings.
5. Installing and configuring the Azure Static Web Apps CLI.
6. Deploying the application using PowerShell.
7. Testing the deployed application through a web browser.

## 🚀 Run Locally

To run this project on your local machine:

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project directory:

   ```bash
   cd YOUR_PROJECT_FOLDER
   ```

3. Open the `index.html` file in your web browser.

No backend server is required for this basic demonstration.

## 📂 Project Structure

A typical static web application structure:

```text
EHR-Web-Application/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

*Note: Adjust the filenames above if your actual repository uses a different structure.*

## 🔒 Data Storage and Privacy

This project uses browser Local Storage for storing patient records.

- Records remain stored in the browser where they were entered.
- Data is not stored in
