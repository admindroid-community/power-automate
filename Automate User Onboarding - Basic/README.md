## **Microsoft 365 User Provisioning Workflow**
This Power Automate flow streamlines Microsoft 365 user onboarding as it:

- Collects required user details
- Generates a secure password, and
- Sends the request for manager approval.

Once approved, the flow automatically:

- Creates the user in Entra ID
- Assigns the appropriate manager
- Emails the generated password directly to the manager.

For detailed flow execution, refer to: [*https://blog.admindroid.com/microsoft-365-user-onboarding-workflow-for-easy-user-provisioning/*](https://blog.admindroid.com/microsoft-365-user-onboarding-workflow-for-easy-user-provisioning/)

***Flow Result***

The Microsoft 365 user provisioning flow looks like this:

![M365 user provisioning workflow](https://blog.admindroid.com/wp-content/uploads/2023/07/provisioning-1024x534.png)

## **Automate M365 User Onboarding with AdminDroid**
While Power Automate can handle Microsoft 365 onboarding, building and maintaining flows can be time-consuming and prone to errors. [AdminDroid’s](https://admindroid.com/?src=GitHub) Microsoft 365 onboarding agent simplifies the process. Whether you need to onboard a single user or thousands, the agent takes care of everything in just minutes. Simply provide input through a form or CSV file, and the agent automatically executes the full provisioning checklist from start to finish:

- Create the user account with UPN and password.
- Enable the account by default.
- Force password change at first sign-in.
- Set additional attributes such as department, job title, and location.
- Assign the required Microsoft 365 license to the user.
- Add the user to groups in Microsoft 365.
- Configure Multi-Factor Authentication (MFA) status.
- Assign a manager to the user profile.
- Send the generated password to the user’s manager via email.

![User Onboarding Workflow](https://blog.admindroid.com/wp-content/uploads/2023/07/automate-user-onboarding-in-microsoft-365-workflow-1024x621.png?v=1757058399)

Not only for user onboarding, AdminDroid offers pre-built agents for numerous other Microsoft 365 tasks. You can also create custom workflow agents with 450+ management actions based on your organization's needs. Beyond automation, AdminDroid provides 3500+ prebuilt reports and 100+ interactive dashboards for comprehensive oversight and control of your Microsoft 365 environment.

*Want to see it in action? Check it out in our live demo*: [*https://demo.admindroid.com/#/workflow/edit-workflow/*](https://demo.admindroid.com/#/workflow/edit-workflow?id=1&nodeId=6051&version=1)
