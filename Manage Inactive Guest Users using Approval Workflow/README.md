## Approval Workflow for Inactive Guest Management in Microsoft 365 Using Power Automate
This Power Automate flow enables admin-controlled lifecycle management of inactive guest users in Microsoft 365. This flow is ideal for organizations dealing with a high volume of external collaborators across different projects or departments. Most importantly, it is a better alternative for admins who must rely on Access reviews and Lifecycle workflows after Microsoft’s guest governance billing enforcement. 

**How flow works:**

The workflow runs automatically at predefined intervals based on admin input. 

For example, 

1. If the recurrence is set to 30 days, the flow executes once every 30 days.
1. Next, the flow identifies all guest users who have been inactive beyond the defined threshold (e.g., 90 days). You can adjust the inactive days threshold based on your requirements.
1. The details of these inactive guest users are stored in a SharePoint list for review.
1. A link to the SharePoint list is then sent to the admin’s inbox for quick access.
1. The admin can review the list and choose an action in the **ActionTaken** column, such as **Keep**, **Disable**, or **Delete**.
1. The selected actions are **executed automatically after 48 hours** (Customizable). Any updates made after this 48-hour window will not be considered. This time window ensures that decisions are not left pending indefinitely and helps enforce timely action.
1. Finally, a detailed report of all executed actions, including who performed the action, what action was taken, and the status (success/failure), is generated and sent to the approver admins as a CSV file via email.

For more details, refer to: <https://blog.admindroid.com/remove-inactive-guest-users-using-power-automate-approval-workflow/>

***Sample Output:***

The following are sample outputs of the flow.

**Inactive guest user list created in SPO will look as below.**

![Inactive guest user report created in SharePoint using PowerAutomate](https://blog.admindroid.com/wp-content/uploads/2026/03/Inactive-guest-user-report-sharepoint-power-automate-1080x474.png)

**Choosing an action for inactive guests in the SPO list will appear as shown below**

![Execute actions on inactive guest users in Microsoft365](https://blog.admindroid.com/wp-content/uploads/2026/03/execute-actions-inacitve-guest-users-microsoft-365-1024x653.png)

***Flow Image:***

The approval workflow for inactive guest user management looks like this:

![Power automate approval workflow for inactive guest users](https://blog.admindroid.com/wp-content/uploads/2026/03/Power-automate-inactive-guest-user-managemet.png)

![Power automate approval workflow for inactive guest m365users](https://blog.admindroid.com/wp-content/uploads/2026/03/Power-automate-inactive-guest-users-removal.png)
## Microsoft 365 Automation Made Simple with AdminDroid
Power Automate is a robust tool, but creating complex workflows can be overwhelming, especially for beginners. What if you could achieve similar automation without any extra steps?

With [AdminDroid’s Microsoft 365 automation tool](https://admindroid.com/?src=GitHub), you can design advanced admin workflows through a simple drag-and-drop interface. Its no-code builder allows you to set up actions, define conditions, and use dynamic content without scripting, which makes automation in Microsoft 365 easier and more approachable.

With over 10 pre-built agents, you can:

- Set up a new SharePoint site in just a few clicks with automated approvals
- Roll out SPO sites with restricted re-sharing and predefined sharing settings in minutes 
- Automate Microsoft 365 user offboarding to ensure secure access removal 
- Streamline the user onboarding process in M365 with ready-to-use workflow

Beyond these ready-made agents, you can build custom workflows using 450+ management actions, and gain insights with 3,500+ reports and 100+ interactive dashboards to effectively monitor your Microsoft 365 environment.

Want to see how it works? Explore the live demo: [*https://demo.admindroid.com/#/workflow/default-workflows/*](https://demo.admindroid.com/#/workflow/default-workflows/)


