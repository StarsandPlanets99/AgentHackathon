Exercise - Create your first autonomous agent
Completed
100 XP
10 minutes
In this exercise, you use Copilot Studio to create an agent that helps HR with onboarding a new employee. This exercise requires you to create a Microsoft Dataverse table. For more information, see Create tables in Microsoft Dataverse.

Scenario
As a member of the HR team, you're building an HR agent to simplify the employee onboarding process. Your goal is to create an agent that can perform the following activities:

Provide general information and answer queries that relate to employee onboarding.
Submit a request automatically to onboard a new employee through the system.
Send an onboarding request approval email automatically to the hiring manager that includes tasks, such as procuring a laptop, setting up an email account, and other onboarding essentials.
Analyze the response for approval after the hiring manager responds to the email. Then, based on the response, take action to send an email to the IT/procurement team to procure a laptop and set up their access.
Wait for the IT/procurement team to confirm procurement and then email the new employee with onboarding instructions.
Create the autonomous agent
To create a new agent in Copilot Studio, sign in to Copilot Studio by using your work email.

On the Home screen, select Create in the left navigation pane. On the next page, select the Create New Agent box.

Screenshot of creating an autonomous agent.
![Create Autonomous Agent](..Images/exercise-create-autonomous-agent.svg)
From the Create New Agent screen, you can choose from two methods to create an agent:

Describe the chat window (1).
Create the agent manually by selecting Skip to configure (2).
For this exercise, select Skip to configure.

Screenshot of creating an autonomous agent, showing the Skip to configure option.

The Create New Agent screen has three fields: Name, Description, and Instructions. For this exercise, enter the following information in these fields:

Name (1) - Employee Onboarding Agent
Description (2) - An agent developed to simplify the employee onboarding process.
Instructions (3) - You are an agent responsible for employee onboarding. After you receive the onboarding request from HR, validate it and send the employee details to the hiring manager for approval. When the hiring manager approves it, forward the information to the IT and procurement teams so they can complete their respective tasks. After they finish their tasks, send the onboarding confirmation along with the onboarding instructions to the employee.
Screenshot of the Create New Agent screen showing the Name, Description, and Instruction fields filled in.

Select the Create button to create the agent.

Enhance agent intelligence
You can enhance the Employee Onboarding Agent that you created in the previous portion of this exercise by adding knowledge and intelligence to the agent.

To add generative reasoning to the agent, in the Orchestration section, turn on Use generative AI to determine how best to respond to users and events (preview). This selection allows generative AI reasoning to respond to questions from different users.

Screenshot of enhancing agent intelligence orchestration.

In addition to enhancing knowledge from generative AI, you can use the Knowledge section to add your enterprise knowledge base.

To upload your resources and create a knowledge base, select the Add knowledge button to ensure that your agent has the information for accurate and efficient responses.

Screenshot of enhancing agent intelligence, showing the Add knowledge option.

For this exercise, create a Dataverse table with the columns from the Employee details.csv file. (For more information, see Create tables in Microsoft Dataverse.)

In the Add knowledge wizard, select Dataverse (preview) to connect the table.

Screenshot of enhancing agent intelligence, showing the Dataverse preview option in the Add knowledge wizard.

On the Step 1 of 3: Select Dataverse tables wizard page, follow these steps to connect the table from Dataverse:

In the search bar (1), search for the table named Employee Details.
From the list of tables that contain Employee Details in their names, select the table that you want to connect to (2). You can select multiple tables as a knowledge source.
Select Next to continue (3).
Screenshot of enhancing agent intelligence, showing a table that contains Employee Details in its name.

On the Step 2 of 3: Preview data wizard page, follow these steps:

Choose the table name from the Select a table to review dropdown list (1).
Review the details of the selected table (2).
Select Next to continue (3).
Screenshot of enhancing agent intelligence, showing the Preview data step.

On the Step 3: Review and finish wizard page, follow these steps:

Name the knowledge source Employee Details (1).
For the knowledge source description, enter This knowledge source answers questions found in the following Dataverse tables: Employee Details (2).
Select the Add button to add the table as a knowledge source (3).
Screenshot of enhancing agent intelligence, showing the Review and finish step.

Select Knowledge in the navigation bar to view resource details.

Select the Add knowledge option (1) to add more resources.
Under the All area, you can check the status of the added resources (2).




