# DATA TO SPREADSHEET WORKFLOW AUTOMATION
"This workflow will retrieve the barangay, first_name, middle_name, last_name in your data file."

Follow these steps to download and import the workflow into your n8n setup.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/5272dfee-9f37-4952-90bd-9019755c8ed2" />


## 🧾 Steps

### Step 1: Download the ZIP File
Download the provided ZIP file that contains the workflow JSON file.

### Step 2: Extract the ZIP File
Extract the contents of the ZIP file to any location on your computer.

### Step 3: Open n8n
Go to your local n8n instance:
http://localhost:5678

Log in to your account.

### Step 4: Import the Workflow
- In the top-right corner, click the **three dots (...)** menu  
- Select **"Import from file"**

### Step 5: Select the JSON File
- Navigate to the folder where you extracted the ZIP file  
- Select the `.json` workflow file  
- Click **Open / OK**


## Notes
- Create Spreadsheet file in your WPS name it and inside is first_name, last_name, middle_name
- Make sure your n8n server is running before importing  
- If the workflow uses external services (e.g., Google APIs), reconnect credentials after importing  
