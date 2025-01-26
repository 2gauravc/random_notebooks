# Introduction

This git repository is a collection if various random project notebooks. These notebooks may come from: 

- LinkedIn experiments done by others 
- Sources like AWS (e.g. AWS courses)
- My own experiments 



# Recommended Method to use the Notebooks

## Via AWS Sagemaker 

**Step 1: Set Up Your AWS Account**

Ensure you have an AWS account. If you don’t, you can create one at the [AWS website](https://aws.amazon.com/).

**Step 2: Access SageMaker**

1. Log in to your AWS Management Console.
2. Navigate to the **SageMaker** service.

**Step 3: Create a SageMaker Studio Domain**

Amazon SageMaker Studio is the integrated development environment (IDE) for SageMaker. A domain is a dedicated SageMaker environment that multiple users can access.

1. In the SageMaker console, choose **SageMaker Studio** on the left panel.
2. Click on **SageMaker Studio Control Panel**.
3. Press **Get started** if it’s your first time, or **Launch app** -> **Studio** to create a new domain.
4. Fill in the required details for the setup, such as authentication method (AWS Single Sign-On, IAM), VPC (if specific network configurations are needed), and permissions.
5. Click **Submit** to create your domain.

**Step 4: Add Users (optional)**

1. In the **SageMaker Studio Control Panel**, under the domain settings, you can add users.
2. Assign user roles and provide them access to the studio.

**Step 5: Launch Studio**

Once the domain is set up and users are added, you can launch Studio:

1. Open the **SageMaker Studio Control Panel**.
2. Find your user name, and click on the **Open Studio** link next to it.

**Step 6: Create Projects and Spaces**

Within SageMaker Studio, you can organize your work into projects and spaces:

1. On the Studio interface, use the **File** menu to create new files, notebooks, or upload data.
2. Use the **Projects** pane to start new ML projects or import existing ones.
3. **Spaces** are generally used within projects to organize resources and share among team members.

**Step 7: Set Up and Use Notebooks**

1. In SageMaker Studio, this Git repository directly to your workspace

2. To do this, go to the **Git** menu in the top navigation of SageMaker Studio.

3. Select **Clone a Repository**.

