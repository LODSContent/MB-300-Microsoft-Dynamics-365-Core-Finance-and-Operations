---
lab:
    title: 'Exercise 08: Create a Batch Job'
    module: 'Module 02:  Configure administrative features and workflows'
--- 
## Exercise 8:  Create a Batch Job

As an administrator you need to create a batch job, which is a group of tasks that are submitted to an Application Object Server (AOS) instance for automatic processing.

### Task 1: Create the batch job

1. Go to **System administration** > **Inquiries** > **Batch jobs**.

2. Select **+New**.

- In the **Job description** field, enter “My Batch Job”.

- In the **Scheduled start date/time** field, enter today’s date.

3. Select **Save**.

### Task 2: Create a recurrence

1. In the **Action** pane, select **Batch job** > **Recurrence** in the legacy form, or **Recurrence** in the enhanced form.

- Use these options to enter a range and pattern for the recurrence as you desire, for example select daily by choosing a pattern of **Days** and an interval of **1**.

2. Select **OK**.

### Task 3: Add alerts

1. In the **Action** pane, select **Batch job** > **Alerts** in the legacy form, or **Alerts** in the enhanced form.

- Indicate if you want alert messages sent when the batch job ends, has an error, or is canceled. Specify if you want the alerts to be displayed as pop-up messages.

2. Select **OK**.

### Task 4: Copy a batch job

1. Select **System administration** > **Inquiries** > **Batch jobs**.

2. Select the job that you want to copy, and in the **Action** pane, select **Batch Job** > **Copy batch job** in the legacy form, or **Copy batch job** in the enhanced form.

3. Enter or add any changes. If you set **View tasks** to Yes, when you select **OK** you will go directly to the **Batch tasks** page for the copied job.

- The copied batch job will be created with a **Withhold** status, so you will need to enable it. The **Run by** user can also be set to give this user the privilege to run the job without being a system administrator.

### Task 5: Enable the batch job

1. On the **Batch job** page, in the **Action** pane, select **Batch job** > **Change status in the legacy form, or Change status in the enhanced form**.

2. Select the **Waiting** status, and then select **OK**.


### Task 6: Set up active periods for batch jobs

1. Go to **System administration** > **Setup** > **Active periods for batch jobs**.

2. Select **+New**.

3. Enter a new period code, for example **Night**, the name of the period, and specify start and end times that the batch period is active.

4. Select **Save**.

### Task 7: Assign active periods to batch jobs

1. Navigate to **System administration** > **Inquiries** > **Batch jobs**.

2. Select the batch job that you want to assign a period to and select **Edit**.

3. In the **Active period** field, select the active period that you want to assign, and then select **Save**.

### Task 8: Assign the Batch manager role to a user

1. Select **System administration** > **Security** > **Assign users to roles**.

2. Select **Batch Job Manager** and select **Manually assign/exclude** user.

3. Select a user from the list, and then select **Assign to role**.

4. Close the page
