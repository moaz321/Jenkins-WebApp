# Jenkins Plugins 
Make sure you have Jenkins installed. You also need the Git and GitHub plugins:
Go to Jenkins Dashboard
Click Manage Jenkins → Manage Plugins
Search for "Git plugin" and "GitHub plugin"
Install them & restart Jenkins
# Create a New Jenkins Project
Go to Jenkins Dashboard
Click "New Item"
Enter a project name & select "Freestyle project"
Click OK
# Clone the repo in your Git account
Click fork and paste the https link
# Build the Project
Click on Settings where your html page is residing
configure the GitHub Webhook. Make sure to type "master" under branch specification
# After configurations
Head to jenkins dashboard click the play button on right side.
