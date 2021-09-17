---
lab:
    title: 'Exercise 04: Create purchase requisition workflow'
    module: 'Module 02:  Configure administrative features and workflows'
---
## Exercise 4: Create purchase requisition workflow

**Scenario**

The Finance and Operations module that you're working in determines the types of workflow that you can create. In this lab, you will create a purchase requisition workflow. Before a purchase requisition can be submitted for review, you need to configure the workflow.

 

### Task 1: Create and set up workflows

1. In the company **USMF**, go to **Procurement and sourcing** > **Setup** > **Procurement and sourcing workflows**.

2. On the list page that appears, on the Action Pane, select **New**.On the **Create workflow** page, select the **Purchase requisition line review**.


3. For the first time, the browser will show a dialog box to open the **Microsoft.Dynamics.AX.Framework.WorkflowEditorHost** page.

**Note**

If you are not prompted to run the **Microsoft.Dynamics.AX.Framework.WorkflowEditorHost** and to log in, then restart the Internet browser in the lab environment, log in again, and perform steps 1 to 4 again.

4. Select **Run** to run the framework.


5. In the **Do you want to run this application?** dialog box, select **Run**. It takes a few minutes for the workflow editor to be downloaded. When it has finished the download, it automatically opens the **Sign in** dialog box.

6. Enter your credentials and password (found in the **Resources** tab on the lab side bar, in the **Azure portal** section)


7. The workflow editor appears (this can take a couple of minutes and may open behind the browser window).

### Task 2: Drag workflow elements onto the canvas

The **Workflow elements** area of the workflow editor contains the elements that you can add to your workflow.

1. To add elements to the workflow, drag **Review purchase requisition lines** and **Approve purchase requisition lines** onto the canvas.


2. Connect **Start** to **Review purchase requisition lines**. To connect one workflow element to another, hold the pointer over an element until connection points appear (small boxes around the edges of the elements). Select a connection point and drag it to another element. Be sure to connect all the elements.

3. Connect **Review purchase requisition lines** to **Approve purchase requisition lines**.

4. Connect **Approve purchase requisition lines** to **End**.

### Task 3: Configure workflow properties

1. In the workflow editor canvas, select **Review purchase requisition lines** and, from the Action Pane, select **Properties** to open the **Properties** page.

2. Enter below values and then Select **Assignment** on the left section

- Enter a value in the **Name** field or accept the default.

- Enter a value in the **Work item subject** field, for example **Work item test**. Alternatively, you can also include a place holder and concatenate the text with the place holder.

- Enter a value in the **Work item instructions** field, for example "**Review this purchase requisition**".

3. In the **Assignment type** tab select **User**.

4. Select the **User** tab, and select a user, for example **ALICIA**, and add it to the **Selected users** section by using the arrow and then select **Close**. 

**Note:** The workflow editor may hide behind the browser window, if so – then just select it from the Windows task bar to open it.

5. On the pane at the bottom of the page, you will have four errors or warnings. 

6. Select each one.

- The first will be a warning, noted by the icon on the left of an exclamation point. Select the icon to open the screen that needs to be changed. In this case, you do not have to enter anything, as you will see the warning is now gone from the bottom pane.

- Select the next error, **Selected assignment type “None” is not supported**.

-  On the screen that opens, select **User**. 

- On the **User** tab, select **Admin** or any other user, and move it over to the **Selected** users. The error will then disappear and you can close the screen from the first step.


- The next message is **You must enter a message text for language en-us**. Select the message and then enter in the **Work item subject**, **Vendor invoice approval**.

	- In the **Work item instructions** (the last error message) enter **Please approve**. This will remove all error messages and your workflow is now complete.


7. Select **Save and close** in the workflow editor. Specify version notes, for example **New workflow** and then select **OK**.


8. Select **Activate the new version**.

9. Select **OK**. It might take a few minutes for the workflow editor to finish its activation process, and then it will close automatically.

10. Select **Close**.

11. Refresh the **Procurement and sourcing workflows** page in Finance and Operations if you don't see your new workflow.
