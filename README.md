# DATA TO SPREADSHEET WORKFLOW AUTOMATION
"This workflow will retrieve the barangay, first_name, middle_name, last_name in your data file."


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/5272dfee-9f37-4952-90bd-9019755c8ed2" />


## Steps

### Step 1: Download the file of your data.(first you need to add another CREDENTIAL to connect it to your account)
<img width="1366" height="768" alt="Screenshot (105)" src="https://github.com/user-attachments/assets/c9610bf5-bc1b-49ce-88ac-53a764887cc2" />

### Step 2: Add Node(Extract from File) to Extract the File
<img width="1366" height="768" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/2346eb9e-d7fb-4186-b144-c64e3551ee66" />

### Step 3: Add Code Node to group the residents into their barangay where it belong
<img width="1366" height="768" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/1462104d-18aa-4bb4-87c9-09a93de8a9ef" />

### Step 4: Add Loop Node
<img width="1366" height="768" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/63ee8bb1-da5a-4cb0-b7ee-81f27fce239a" />

### Step 5: Add Code Node to Flatten the data(connect node in the loop branch
<img width="1366" height="768" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/a37d39bb-2115-4e67-9629-7077af359455" />

### Step 6: Add Spreadsheet/Google Sheet Node, then select 'Append or update rows in sheets'
<img width="1366" height="768" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/f0044e50-be18-484b-bdd4-b6efffec9c16" />

### Step 7: in loop branch add another Node which is Google Sheet and select 'Create Sheet'
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a71367a8-3c6d-4e08-b5a9-e93b788e8944" />

### Step 8: Connect the Google Sheet(Append & Update Rows) in the Loop Node to automatically create a sheetname of by barangay

## Notes
- Create Spreadsheet file in your WPS, name it and inside is barangay, first_name, last_name, middle_name
- Make sure your n8n server is running before importing  
- If the workflow uses external services (e.g., Google APIs), reconnect credentials after importing  
