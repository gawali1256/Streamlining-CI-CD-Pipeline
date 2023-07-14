# CI-CD-Web
Effortless HTML Deployment: Streamlining CI/CD Pipeline with GitHub, Jenkins, and Apache Web Server ,on AWS

A CI/CD (Continuous Integration/Continuous Deployment) pipeline using GitHub, Jenkins, and a web server involves automating the process of building and deploying software changes to a production environment. Here's a high-level description of such a pipeline

Tools
(git, Github , Jenkins, Apache web server, AWS)

Steps:
Set up a GitHub repository:
👉 Create a new repository on GitHub or use an existing one.
Initialize the repository with an HTML file or add the HTML file to the repository.
👉 Add or modify the HTML code:
Use a text editor or integrated development environment (IDE) to add or modify the HTML code in the cloned repository.
👉 Commit and push changes:
Once you're done editing the HTML code, commit the changes using the following commands:
git add . git commit -m "Add/modify HTML code" git push origin master
Install and configure Jenkins:
👉 Download and install Jenkins on your local machine or a server.
Follow the installation instructions provided by Jenkins for your operating system.
Once installed, access the Jenkins web interface.
Set up a Jenkins project:
👉 Create a new Jenkins project by selecting "New Item" from the Jenkins dashboard.
Enter a name for the project and choose the "Freestyle project" option.
Click "OK" to create the project.
Configure the Jenkins project:
Select Git as the version control system and enter the URL of your GitHub repository.
Optionally, specify the branch you want Jenkins to build.
👉 Set up a build step:
In the project configuration, go to the "Build" section.
Add a build step of type "Execute shell" or "Execute Windows batch command" depending on your operating system.
In the build step, enter the commands to deploy the HTML code to your local server. For example, if you're using a web server like Apache HTTP Server.
👉 Save the project configuration and trigger a build:
Save the Jenkins project configuration.
From the Jenkins dashboard, select the project and click "Build Now" to trigger a build.
Jenkins will link the GitHub repository, execute the build steps, and deploy the HTML code to your local server.
👉 Verify the deployment:
Access your local server using a web browser and verify that the HTML code is deployed correctly.
