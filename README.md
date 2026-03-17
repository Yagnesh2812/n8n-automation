🚀 n8n Automation 1 – Form to Google Sheets + Email Notification
📌 Overview

This project is an automated workflow built using n8n. It collects user information through a form, stores the data in Google Sheets, and sends a confirmation email to the user.

⚙️ Workflow Functionality

This automation performs the following steps:

Captures user input (Name & Email) via a form.

Stores the submitted data into a Google Sheet.

Sends a confirmation email to the user after submission.

🔄 Workflow Structure

Form Trigger → Collects user details

Google Sheets Node → Saves data (Name, Email, Time)

Gmail Node → Sends confirmation message

🛠️ Tools & Technologies

n8n (Workflow Automation)

Google Sheets API

Gmail API

📥 How to Use

Download the JSON workflow file.

Open n8n.

Click Import Workflow.

Upload the JSON file.

Configure:

Google Sheets credentials

Gmail credentials

Activate the workflow.

Use the form URL to test the automation.

📊 Data Stored

The following fields are stored in Google Sheets:

Name

Email

Submission Time

📧 Email Notification

After form submission, the user receives a welcome email confirming their registration for consultation.

💡 Use Cases

Lead collection forms

Consultation booking systems

Basic CRM data entry automation

Email response automation

🔐 Requirements

Google account (for Sheets & Gmail integration)

n8n instance (cloud or self-hosted)

📌 Future Improvements

Add validation for form inputs

Send personalized emails

Integrate with CRM tools

Add WhatsApp or SMS notifications

👨‍💻 Author

Yagnesh Gadhethariya
