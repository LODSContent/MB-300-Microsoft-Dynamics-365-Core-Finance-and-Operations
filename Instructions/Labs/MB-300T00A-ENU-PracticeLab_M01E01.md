---
lab:
    title: 'Exercise 01: Work with operational workspace'
    module: 'Module 01: Describe Finance and Operations Apps, and extend apps by using Microsoft Power Platform technologies'
---
## Exercise 1: Work with an operational workspace

**Scenario**: In **USMF** you are acting as a sales representative to sell item **A0001** to your customers. You need to check the available on-hand quantity of the items, find out if there is any default sales price for the item, or trade agreement price per customer.

If the item quantity is not enough, you need to create a purchase order for the customer to fulfill the demand.

1.  Login to your Virtual Machine with credentials provided.

2.  Navigate to the Dynamics home page on the browser, and the default Dashboard by selecting the **Finance and Operations** button on the top left or selecting the **Home** button on the left menu.

3.  Select the **Sales order processing and inquiry** workspace.

4.  Select **New** and then select **Sales order** from the drop-down.

5.  In the **Customer account** field, enter or select customer `US-004` Cave Wholesales and select **OK**.

6.  In the **Item number** field, enter or select item `A0001`

7.  In the **Warehouse** field, enter or select `11`. The **Site** is automatically populated.

8.  Select the **Inventory** menu in the **Sales order lines** section and then select **On-hand inventory**. Note that there is not enough quantity of this item in this warehouse and select **Close**.

9.  In the **Site** field, enter or select site `2` and in the **Warehouse** field, enter or select warehouse `21`

10. In the **Lead time date change, recalculate ship and receipt dates?** dialog, select **Yes**.

11. Select the **Inventory** menu in the **Sales order lines** section and then select **On-hand inventory**. Note that there is not enough quantity of this item in this warehouse. 

12. Select **Close**. 

13. From the **Sales order** tab in Action pane, select **Purchase order**. 

14. In the **Vendor account** field, enter or select `US-108` **City Power & Light**. 

15. Select the **Include** checkbox and then select **Validate**. Select **OK** after the validation is successful. 

16. Select the **General** tab from the Action pane, select **Purchase order**. 

17. Select the **Inventory** menu in the **Purchase order lines** section and then select **On-hand**. 

18. Verify the quantity of 1.00 for **A0001** in the **Ordered Reserved** field and select **Close**. 

19. Select **Close**. 

20. **Close** the Sales order page. 

21. In the **Sales order processing and inquiry** workspace and select the **Unconfirmed** tab. 

22. Find the sales order you have just created in this exercise. Note this sales order status is **Unconfirmed**. Select the line in the grid you have just created in this exercise and select the **Confirm** button. 

23. Select the **OK** button on **Confirm sales order** window. 

24. In the **You are about to post the document without printing it. Select OK to continue.** dialog, select **OK**. 

25. Select the **Confirmed** tile in the **Sales order processing and inquiry** workspace. 

26. Find the sales order you have just created in this exercise. Select the sales order number link to open the details page. 

27. Close the sales order page. 

28. Navigate back to the default Dashboard. 

