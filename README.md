# Implementing-Terraform-on-Microsoft-Azure
 version v0.12.28 y  azure-cli v 2.9.0

### Visual Studio Code

You are going to want to use Visual Studio Code or a similar code editor. Personally I like VS Code because it's free and cross-platform, and it has source control built-in. But hey, that's just me. You do you.

### Azure Subscription(s)

This is a course all about using Terraform on Microsoft Azure. It is safe to assume you'll need at least one Azure subscription and the **Owner** or **Co-administrator** role on that subscription. The exercises use two subscriptions - one for networking and another for security - to demonstrate multiple instances of the AzureRM provider.

You don't have to use two separate subscriptions, instead you could use the same subscription for all the exercises. I haven't tested that, and some of the automatic role creation might fail. It's probably just as easy to create an extra subscription and delete it when you are done the course.

### Azure Active Directory Rights

The course includes use of the AzureAD provider, and it assumes that you have permissions to create Service Principals within the Azure AD tenant associated with your Azure subscriptions. Assuming you created subscriptions and an Azure AD tenant for this course, then you shouldn't have any problems.

### Azure DevOps Subscription

The course also makes use of Azure DevOps Repos and Pipelines. The basic Azure DevOps plan is free for up to five users. You will also need to add the [Terraform Build & Release Tasks](https://marketplace.visualstudio.com/items?itemName=charleszipp.azure-pipelines-tasks-terraform) extension from the Visual Studio Marketplace.

