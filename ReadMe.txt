* Must use Computer Certificates management tool to install the certificate in the correct place. You can search for 'Manage Certificates' from your desktop to find it. 

- Double click the folder called 'Trusted People'
- open the 'Action' menu at top of the window
- hover over 'All tasks'
- click 'Import'
- follow the wizard to import the certificate

* Troubleshooting help:
- https://learn.microsoft.com/en-us/windows/msix/app-installer/troubleshoot-appinstaller-issues

* This is necessary because it's a packaged windows store app but I'm using a self signed/developers certificate. An actual signing certificate from a trusted certificate authority is simple to get but costs money. They are automatically added to the trusted developers section of the certificate manager without need for the user installing it. 

* You may need to install the included dependencies if you are missing them. (Microsoft Visual C Libraries and Microsoft Windows App Runtime)

* These steps only need to be done once. From now on you can just use the Retro360 MSIX file to update the program. 
