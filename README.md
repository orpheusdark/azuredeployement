![image](https://github.com/krishvsoni/whatToDo/assets/67964054/48caafe9-758e-42ba-af6f-5318f265b62c)

# Deploying a Static App on Azure with GitHub

In this guide, we'll walk through the steps to deploy a static web application on Azure using GitHub.

## Prerequisites

Before you begin, make sure you have the following:

- An Azure account
- A GitHub account
- Your static web application code hosted on GitHub

## Steps

### 1. Create an Azure Web App

1. Log in to the [Azure Portal](https://portal.azure.com/).
2. Click on "Create a resource" and search for "Web App".
3. Fill in the required details like App name, Subscription, Resource Group, and App Service Plan.
4. Click on "Review + create" and then "Create" to create the Web App.

### 2. Set Up Deployment Source

1. Once the Web App is created, navigate to it in the Azure Portal.
2. In the left-hand menu, under "Deployment", click on "Deployment Center".
3. Select GitHub as the source, and then click on "Continue".
4. Follow the prompts to authorize Azure to access your GitHub account and select the repository that contains your static web application code.
5. Configure the branch to deploy from and the build provider (if necessary).
6. Click on "Finish".

### 3. Configure Deployment Settings

1. In the "Deployment Center", under "Settings", configure any additional deployment settings as needed.
2. Review the deployment options and make any necessary changes.
3. Save the settings.

### 4. Trigger Deployment

1. Once the deployment source and settings are configured, Azure will automatically deploy the static web application whenever changes are pushed to the selected branch on GitHub.
2. You can also manually trigger a deployment from the Azure Portal if needed.

### 5. Verify Deployment

1. After the deployment is completed, navigate to the URL of your Azure Web App to verify that the static web application is successfully deployed.

## Conclusion

By following these steps, you can easily deploy your static web application on Azure using GitHub as the source repository. This setup allows for continuous deployment, ensuring that your application is always up-to-date with the latest changes pushed to your GitHub repository.
