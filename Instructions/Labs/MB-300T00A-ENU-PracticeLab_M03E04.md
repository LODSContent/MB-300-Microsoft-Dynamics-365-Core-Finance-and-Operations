---
lab:
    title: 'Exercise 04: Use Excel workbook designer'
    module: 'Module 03: Manage Finance and Operations data'
---
## Exercise 4: Use Excel workbook designer

You need to use the Excel workbook designer page to create an Open in Excel experience for an entity.

### Instructions

1.  Switch to the **USMF** legal entity.

2.  In the **Fleet Management** module, go to **Setup \> Fleet Setup**.

3.  In the **Data setup** tab, select **Create**. 

4.  In the **Sample data created** dialog, select **Close**. 

5.  Close the page. 

6.  In the **Common** module, navigate to **Common \> Office integration \> Excel workbook designer**. 

7.  Select the **FleetCustomer** entity. You may use the filter to save time. 

8.  Add all fields in the list of available fields to the list of selected fields using the **Add all** button.

9.  Select **Create workbook**. You may safely ignore a SharePoint informational message. **Download** and **open** the workbook that is generated.

10. Go to **Downloads** folder and open the file. If the office activation appears, select **Close**.

11. If necessary, select **Enable Editing** to enable the Excel Data Connector App to load. Customer data is read from the OData service on the server and added to the table.

12. Select **Trust this add-in**. 

13. This workbook contains the Excel Data Connector App, a binding to the Fleet Management Customer entity, and a pointer to the server that the workbook was generated from. 

14. Select **Sign in** and use the alias you are using to connect to Dynamics 365 Finance.

15. Insert a blank row above the table and enter **Fleet Customers** as the title.

16. Rename the worksheet **FleetCustomers**.

17. Rearrange some of the fields in the table.

18. Select **Design** to open the design experience.

19. Next to the **Fleet Management Customers** data source, there are buttons for editing and deleting the data source. Select **Edit** to see the field list. 

20. Select fields and move them as you require. Set the order for the first three fields to **FirstName**, **LastName**, and **DriverLicense**. Select **Update**. Verify the field order is changed in the worksheet.

21. Select **Done**.

22. Select **Options**.

23. Expand **Data Connector** and select **Clear binding data** so that the workbook contains no bound data. Select **OK**. 

24. Save the workbook as `FleetCustomersBasic.xlsx`

25. In a browser tab, select the **Common** module and go to **Common \> Office integration \> Document templates**. 

26. Select **+ New**. 

27. Browse to the file that you just saved.

28. Select **OK**. The template is added as a line in the templates table.

29. In the **FleetCustomersBasic** row, clear the **Apply current record filter** checkbox, so that an unfiltered list of customers will be loaded after the template is opened.

30. Change the **Template display name** value to `Fleet Customers Basic`

31. Navigate to **Fleet Management \> Customers \> Customer**. 

32. Select **Open** in Microsoft Office. Note that **Fleet Customers Basic** is now an option in the **Open in Excel** section. Select that option. 

33. Open the workbook that is generated. 

34. Select **Enable editing** to enable the Excel Data Connector App to load. Customer data is read from the OData service on the server and added to the table binding that 
you created. 

