---
lab:
    title: 'Exercise 01: Work with template in the Data Management Workspace'
    module: 'Module 03: Manage Finance and Operations data'
---
## Exercise 1: Work with template in the Data Management Workspace

The goal of the lab exercise is to apply the knowledge we have learned regarding the Data management workspace.

Instructions:

1. Go to **Workspaces** > **Data management**.

2. If the dialog box “The entity list is being refreshed. You may continue your work while this happens. The completion status of this operation can be found in the message center.” appeared, click **Close** and then Click **Enhanced view** button in the top left of the screen.

3. Select the **Templates** tile.

4. Refresh the page or press **Shift+F5**. (There is a refresh arrow near the top right of the Dynamics screen.) Note if there are any templates available.

5. Select **Load default templates**.

6. Select **Load all**. This may take a while.

7. In the list, find and select the desired template, such as **020 - GL Shared**.

8. View available entities for General ledger shared template.

9. In the list, find and select the desired record, such as **Main account categories** by using the filter

10. View available entities for **Main account categories** template.

11. Expand the **Template details** section. In the list, find and select the desired record, such as **Financial dimension sets and** Select **Discover dependencies**. It takes a few minutes, then shows all dependencies of the selected entity. This may take a while.

12. View entities that **Financial dimension sets** entity has dependency with.

13. Close the **Discover dependencies** page.

14. Close the **Templates** page.

15. Select **Data entities** tile. View the available **Finance and Operations apps** entities.

16. Select any of the entities of your choice, such as **Accountants** and select **Entity structure** button to see the data source. 

17. Here you can enable or disable running the business logic in your project. For instance, for data migration, you may have modified the settings of certain configurations to meet the customer requirements, however the legacy data would violate the new rule, so you may need to make the decision to turn off the rule for historical data.

18. Select the **Target fields** button. View and edit the target fields, such as enabling or disabling the table configuration key status.

19. Close the **Target fields** page.

20. Close the **Entity structure** page.

21. Select the **Entity model view** button. It allows you to have better visibility by grouping entities per category and subcategory of nodes representing the module, and the models of the entities.

22. In the tree, expand **All\AccountsPayable**. View available entities.

23. In the tree, select **All\AccountsPayable\Transaction**. View available entities.


24. In the tree, expand **All\GeneralLedger**. View available entities.

25. In the tree, select **All\GeneralLedger\Document**. View available entities.

26. Close the **Entity model view** page.

27. Select **Entity category view** button.


28. In the tree, expand **All\Configuration**. View available entities

29. In the tree, select **All\Configuration\SystemAdministration**. View available entities

30. In the tree, expand **All\Reference**. View available entities

31. In the tree, select **All\Reference\AccountsReceivable**. View available entities

32. Close the **Entity category view** page.

33. Close the **Data entities** page**.**

34. Select the **Staging cleanup** tile.

35. In the **Entity** field, enter or select a value such as **1099 fields**.

36. Select **OK**.

37. Select the **Data task automation** tile.

38. Select **Load default tasks** to open the **Load default tasks** dialog.

39. From the drop-down, enter or select a value such as **MS_Sample_Regression_DMFManifest**. Click **Select**.

40. Select **Load**. This dialog allows you to load multiple data task automation.

41. Select **Cancel**.

42. View available tasks.

43. Close the **Data task automation** page.

44. Select the **Configure data source** tile. Here you can view, edit, and create data types such as CSV, Excel, and Package.

45. Close all pages.
