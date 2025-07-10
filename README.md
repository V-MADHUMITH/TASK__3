TASK 3->CLOUD STORAGE SETUP 
COMPANY: CODTECH IT SOLUTION 
NAME: V. MADHUMITHA
INTERN ID: CITSOD393
DOMAIN: CLOUD COMPUTING 
DURATION: 4 WEEKS 
MENTOR: NEELA SANTOSH

-> Objective  
To build and demonstrate a simple multi-cloud application where the **frontend** is hosted on AWS (Amazon S3) and the backend is deployed on **Azure Functions / Azure App Service**, showcasing cross-cloud communication.

---

-> Architecture Overview

Frontend and backend services are distributed across two cloud providers:

- AWS S3: Hosts the static frontend website (HTML, CSS, JS)
- Azure: Hosts the backend logic using Azure Function or Azure App Service



->Technologies Used

| Service          | Cloud Provider | Purpose                         |
|------------------|----------------|----------------------------------|
| Amazon S3        | AWS            | Frontend hosting (static website) |
| Azure Functions  | Azure          | Backend logic via HTTP trigger   |
| JavaScript       | Frontend       | Form handling and API call       |
| Node.js / Python | Backend        | Azure Function code              |


 *Implementation Steps

* Frontend (AWS S3)
- Created an S3 bucket and enabled static website hosting.
- Uploaded `index.html`, `main.js`, and `style.css`.
- Configured the bucket for public read access.
- Added CORS rules to allow requests to Azure backend.

* Backend (Azure Function)
- Created an Azure Function App with an HTTP Trigger.
- Wrote logic to handle POST requests and respond with a success message.
- Enabled CORS to allow requests from AWS S3.
- Deployed and tested using Azure Portal.



* Testing:

- Accessed the frontend using the S3 static website URL.
- Submitted the form and received a real-time response from the Azure backend.
- Verified Azure Function logs to ensure data was received correctly.

* architecture:
  
<img width="104" height="540" alt="Image" src="https://github.com/user-attachments/assets/1291b6ab-da37-49e5-8115-744b93ed0f79" />
