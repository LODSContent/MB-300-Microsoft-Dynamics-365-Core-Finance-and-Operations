---
lab:
    title: 'Exercise 04: Use Excel workbook designer'
    module: 'Module 03: Manage Finance and Operations data'
---
## Exercise 4: Use Excel workbook designer

You need to use the Excel workbook designer page to create an Open in Excel experience for an entity.

### Instructions

1.  Switch to the **USMF** legal entity.
2.  Go to **Fleet Management \> Setup \> Fleet Setup**
3.  In the **Data setup** tab, click **Create.**
4.  In the Sample data created dialog box, click **Close**.
5.  Close the page.
6.  Navigate to **Common \> Common \> Office integration \> Excel workbook designer**.
7.  Select the **FleetCustomer** entity. You may use the filter to save time.
8.  Add all fields in the list of available fields to the list of selected fields.
9.  Select **Create workbook**. You may safely ignore a SharePoint informational message. **Download** and **open** the workbook that is generated.
10. Go to Downloads folder and launch the file. If the office activation appears click close.
11. If necessary, select **Enable editing** to enable the Excel Data Connector App to load. Customer data is read from the OData service on the server and added to the table.
12. Click **Trust this add-in**.
13. This workbook contains the Excel Data Connector App, a binding to the Fleet Management Customer entity, and a pointer to the server that the workbook was generated from. Click sign in and use the alias you are using to connect to Dynamics 365 Finance.
1.  Insert a blank row above the table and enter **Fleet Customers** as the title.
2.  Rename the worksheet **FleetCustomers**.
3.  Rearrange some of the fields in the table.
4.  Select **Design** to open the design experience.
5.  Next to the FleetCustomer data source, there are buttons for editing and deleting the data source. Select **Edit** to see the field list.
6.  Select fields and move them as you require. Set the order for the first three fields to **FirstName**, **LastName**, and **DriverLicense**. Select **Update**. Note that the field order is changed.
7.  Select **Done**.
8.  Select the **Settings**.
9.  Select **Clear binding data** under **Data Connector** so that the workbook contains no bound data. Select **OK**.
10. Save the workbook as FleetCustomersBasic.xlsx.
11. In an internet browser, navigate to **Common \> Common \> Office integration \> Document templates**.
12. Select **New**.
13. Browse to the file that you just saved.
14. Select **OK**. The template is added as a line in the templates table.
15. In the **FleetCustomersBasic** row, clear the apply current record filter check box, so that an unfiltered list of customers will be loaded after the template is opened.
16. Change the **Template display name** value to Fleet Customers Basic.
17. Navigate to **Fleet Management \> Customers \> Customer**.
18. Select **Open** in Microsoft Office. Note that Fleet Customers Basic is now an option in the Open in Excel section. Select that option.
19. Open the workbook that is generated.
20. Select **Enable editing** to enable the Excel Data Connector App to load. Customer data is read from the OData service on the server and added to the table binding that you created.
