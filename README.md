Genesys Groupie Application
Genesys Groupie is a desktop application built using Python and Tkinter that allows you to authenticate with Genesys Cloud, fetch groups and their members, and export this information to CSV files. This application is especially useful for managing and exporting group and member data from your Genesys Cloud environment.

Features
Authenticate with Genesys Cloud using OAuth.
Fetch and display groups and their members.
Export all groups and their members to a CSV file.
Export a selected group and its members to a CSV file.

Authentication with Genesys Cloud
To use the Genesys Groupie application, you need to authenticate with Genesys Cloud. Follow these steps to get the necessary OAuth credentials:

Create an OAuth Client:

Log in to your Genesys Cloud organization.
Go to Admin > Integrations > OAuth.
Click on Add Client.
Fill in the details and set the following:
Client Name: Name of your client (e.g., Genesys Groupie).
Description: Description of the client.
Grant Types: Select Client Credentials.
Client Secret: Note down the generated client secret.
Scope: Add groups and groups:readonly.
Get Client ID and Secret:

After creating the client, you will get a Client ID and Client Secret. Note these down as they will be used for authentication in the application.
Using the Application
Open Genesys Groupie:
Run the application executable (genesys_groupie.exe) or the Python script (genesys_groupie.py).

Authenticate:

Enter your Client ID and Client Secret in the provided fields.
Enter your Environment (e.g., mypurecloud.com.au).
Click on Authenticate.
Fetch Groups:

After authentication, the application will fetch and display the list of groups in your Genesys Cloud organization.
View Group Members:

Select a group from the list to view its members.
Export Data to CSV:

Use the Export All Groups to CSV button to export all groups and their members.
Use the Export Current Group to CSV button to export the selected group and its members.
Troubleshooting
If the application fails to authenticate, ensure that your client ID, client secret, and environment are correct.
Check the genesys_groupie.log file for detailed error messages and logs.
