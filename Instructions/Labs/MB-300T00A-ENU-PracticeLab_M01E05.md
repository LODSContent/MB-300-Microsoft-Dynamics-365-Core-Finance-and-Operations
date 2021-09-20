---
lab:
    title: 'Exercise 05: Prepare, enable, and use business document management'
    module: 'Module 01:  Describe Finance and Operations Apps, and extend apps by using Microsoft Power Platform technologies'
---
## Exercise 5: Prepare, enable, and use business document management

**Scenario**: you need to demonstrate the usage of Business document management (BDM) in **USMF**. Depending on the VM you are using the preview option of Business document management may not be working properly due to restrictions on the VM applied by the hosting company.

**Note:** you will not have the preview issue if you are working with your own environment.

In this exercise you will import the data from a free text invoice into an excel template by using the ER *data model* configuration which is provided as part of this lab in XML format.

**Important**: Click on the hyper link to download the data model and save it in the **Download** folder on your VM running an instance of **Dynamics 365 Finance**.

- **Sample ER customer invoicing solution**

	- [Customer invoicing model.version.2.xml](https://github.com/MicrosoftLearning/MB-300-Microsoft-Dynamics-365-Core-Finance-and-Operations/tree/master/Allfiles/Labs)

	- [Customer FTI report (GER).version.2.3.xml](https://github.com/MicrosoftLearning/MB-300-Microsoft-Dynamics-365-Core-Finance-and-Operations/tree/master/Allfiles/Labs)

The ER configuration will refer to the provider as the author of the configuration. In this example, you will create a configuration provider for sample company, **Litware, Inc.** These steps can be performed in any company as ER configuration providers are shared among all companies.

### Task 1: Create a provider

1. Go to the **navigation pane** in the upper left corner and select **Organization administration** and then select **Workspaces** > **Electronic reporting**.

2. Go to **Related links** > **Configuration providers**.

3. Select **+New**.

4. In the Name field, type **Litware, Inc.**

5. In the Internet address field, type [http://www.litwareinc.com/](http://www.litwareinc.com/)

6. Select **Save**.

7. **Close** the page.

### Task 2: Select as an active provider

1. Select the **Litware, Inc.** provider.

2. Click **…** drop down.

3. Select **Set active**.

### Task 3: Import ER solutions

Import the ER data model configuration of each ER solution in the tables above before you import the corresponding ER format configuration.

1. Select the **Organization administration** > **Work space** >**Electronic reporting** 

2.  Select **Reporting Configurations** tile.

3. Select the first node on the top of the page,

4. Select **Exchange** button.

5. Select **Load from XML file**.

6. Select **Browse** to load the required XML file.

7. Select **Customerinvoicingmodelversion2.xml**

8. Select **OK** to confirm configuration's import.

**Note : change UTF value if its throws any version error.**

9. This will create a new node “**Customer Invoicing model”**

10. Select the “**Customer Invoicing model”** node and Select **Exchange** button.

Note: change UTF value in xml to 16 and save.

11. Select **Load from XML file**.

12. Select **Browse** to load the required XML file.

13. Select **CustomerFTIreportGERversion23**

14. Select **OK** to confirm configuration's import.

15. This will create a new sub-node “**Customer FTI report (GER)”**

16. Select “**Customer FTI report (GER)” and** Select **Designer** button.

17. Expand **Report and** Expand **Invoice and r**eview the sub-nodes and the values of the **Format** tab on the right-hand side.

18. Select the **Mapping** tab and review the values.

19. Close the **Designer** form.

20. Close the **Reporting Configuration** form.

21. Click on the **Home** button.

### Task 4: Verify Business document management feature is enabled

To start Business document management, you need to open the **Feature management** workspace and enable the **Business document management** feature.

1. Select **Workspace management** and scroll down and select **Feature management** workspace.

2. Select **All** tab. In the quick filter type **Business,** then press enter**.**

3. Make sure the **Business document management** feature is enabled.

4. Click **Home**.

### Task 5: Configure access permissions

By default, when access to Business document management permissions is not enabled, every user with access to the Business document management workspace will see all of the ER solution templates that are available.

The Business document management workspace will show only those templates that reside in ER format configurations and that are marked by a **Business document type** tag.

1. Go to **Organization administration** > **Electronic reporting** > **Business document management** > **Manage access permissions** **to edit templates.**

2. Click **Access permission settings**

3. Set the **Apply configured access permission**, to **Yes**.

4. Click **Ok**.

5. Click **+Add and** Select **Accounts receivable manager and then** Click **Ok**.

6. Under the **Access permission per tags of configuration**, click **+New.**

	- Select **Functional area** in the **Tag type** field.

	- Select **invoicing** in the **Id** field.

	- Under the **Access permission per configuration** section, click **+Add.**

	- Select **Customer FTI report (GER)** in the **Name** field.

7. Click **Save**.

8. Close the form.

### Task 6: Business document management Workspace

1. Go to **Business document management** workspace. Click **New document** button.

2. Select **Invoicing** and then select **Create document** button**.**

3. In the Name field type “**My Free Text Excel Business Document**” and select **OK**.

**Note:** If you are using VM hosted by vendors rather than your environment you will receive an error message while previewing the excel document. Click **Ok**.

1. Select **Check for issues** button.

2. Select the **Open in Desktop App** button.

3. Select **Save** > **Save As**. Choose download folder and click **Save**.

4. Select **Open folder** button. Select the **Free Text Invoice Template** and double **Open**.

5. If the Office activation form appears, click **Close**.

6. View the format and Close the workbook.

7. Navigate to **Business document management** workspace.

**Note**: if you see ‌an error message that service is not available is due to not having a license of Office 365 online or have not logged on to the Office 365 services for editing the template. If you are using the VM hosted by a vendor you will see this message.

1. You can delete the document by selecting **Delete**.

2. You can publish your business document by selecting **Publish** button and Click **Publish** button and then click **Yes**.
