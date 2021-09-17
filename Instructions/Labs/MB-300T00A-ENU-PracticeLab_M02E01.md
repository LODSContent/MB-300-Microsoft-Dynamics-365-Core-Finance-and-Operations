---
lab:
    title: 'Exercise 01: Creating users and Assigning security roles'
    module: 'Module 02:  Configure administrative features and workflows'
---
## Exercise 1: Creating users and Assigning security roles

Scenario - In this exercise, we will create two new users and assign security roles to them. One will be manually entered, and one will be imported from the Azure Active directory.

The HR department of **USMF** has requested access to Finance and Operations apps for a newly hired employee as an **Accounts payable clerk**. As a system administrator, you need to create a new user ID for the employee in Finance and Operations, assign USMF as their default company, and associate the **Accounts payable clerk**. The active directory user account has already been created as part of the onboarding process.

You also need to import a new employee into Finance and Operations apps and assign the default company to **USMF** and associate **Accounts receivable clerk**.
## Instructions

1. Go to **System administration > Manage Users > Users**. Note that this navigation is almost always done from the modules selection on the left side.

2. Select **+New and then data as mentioned below**

	- In the **User ID** field, enter **DynUser3**.

	- In the **User name** field, enter **Dynamics 365 User 1**.

	- In the **Email** field, enter [DynUser3@contosoax7.onmicrosoft.com](mailto:DynUser3@contosoax7.onmicrosoft.com).

	- In the **Company** field, select **USMF**.

3. Select **Assign roles**.

	- In the list, find and select **Account payable clerk**.

	- Select **OK**.

4. Select **Save**.

5. Close the page.

