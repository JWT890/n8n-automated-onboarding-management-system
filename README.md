# zapier-automated-onboarding-management-system

This is a automated onboarding management system with Zapier.  

# Setup
First go to Google Forms and click on blank form and name it Onboading Form:  
<img width="1866" height="891" alt="image" src="https://github.com/user-attachments/assets/a13a0099-aa06-4d60-8517-d8ae6c2fb4cf" />  
Then in the first form change it to Employee Full Name with it as short answer and have it as required like in the first picture.  
Create a second question by clicking the plus option and name it Personal Email, set to required, then click the three dots and select email validation like so:  
<img width="1073" height="394" alt="image" src="https://github.com/user-attachments/assets/eec691b8-a277-4d4c-995d-7e5c9e5880ea" />  
Then create a new one and name it Role/Job Title with it set to short answer and required set to yes.  
Then create a another one with it named to Department.  
<img width="880" height="543" alt="image" src="https://github.com/user-attachments/assets/ed5290dd-a29b-4ccb-a929-8db14eeb75df" />  
Then for Employee Type:  
<img width="875" height="448" alt="image" src="https://github.com/user-attachments/assets/77b9d168-4a1b-4c96-b71f-77d903dffc01" />  
Then for Start Date have it set to date and required.  
Then For Manager have it set to Short Answer and required.  
Then for Manager email have it set to short answer with email validation and set to required.  
Then for Office Location have it set to dropdown like so:  
<img width="867" height="444" alt="image" src="https://github.com/user-attachments/assets/4eb94431-0196-41a8-8934-80b440ec0079" />  
Then do Equipment Needed and have it set to checkboxes:  
<img width="897" height="560" alt="image" src="https://github.com/user-attachments/assets/0fde8574-820b-450d-a1c5-2813afd06d05" />  
Then move over to settings and for the responses have it like this:  
<img width="799" height="644" alt="image" src="https://github.com/user-attachments/assets/c12bfd0a-bc2e-493c-86be-bb8d85c88b37" />  
Then go to the responses section and click link to Google Sheets link:  
<img width="985" height="529" alt="image" src="https://github.com/user-attachments/assets/8ecada45-c3a2-4fb5-ac12-464bda7de963" />  
Click on it and select create new spreadsheet and name it Onboarding Tracker. You will see this after creating it.  
<img width="1916" height="907" alt="image" src="https://github.com/user-attachments/assets/ad013716-1006-43e0-8cac-8474ab12a80b" />  

# Zapier
Then go to Zapier's dashboard and click on create Zap which will take to the zap dashboard:  
<img width="1822" height="982" alt="image" src="https://github.com/user-attachments/assets/b447f547-48f1-4630-9f97-43bef2d28467" />  
Then do the first creation of the action, choose app and event and look for google forms to choose, select new or updated form response and select continue.  
After clicking continue, select the form that was created and select a trigger question such as email and select continue and then select test trigger and should see the following data generated:  
<img width="378" height="762" alt="image" src="https://github.com/user-attachments/assets/09e28cbf-e425-4b8c-baa6-ea2fafbe9cb8" />  
Then go to the first action and search for the Google Sheets app. In action event, search for create spreadsheet row, choose account and select continue.  
Then in configure select the onboarding form spreadsheet with the generated responses and hit continue and see this tab:  
<img width="396" height="881" alt="image" src="https://github.com/user-attachments/assets/82f80888-38ff-4fc3-b23e-8621e0710208" />  
After inputing some data and testing it, its time to create the next action.  
Choose Gmail with the action event set to send email and continue. You will see a section of configuring the email, for this I'll use my personal email to send it too and give it a subject title like this:  
<img width="362" height="96" alt="image" src="https://github.com/user-attachments/assets/46e21e9d-dba4-40b2-93e8-5e7553996024" />  
And set the body to Html and input the information needed for IT request setup and onboarding checklist, select continue and hit test step.  
You should get an email like this and good for testing:  
<img width="1523" height="284" alt="image" src="https://github.com/user-attachments/assets/c190d20f-2e0f-4c89-a7b4-a93e0275eb3b" />  
Next its time to do another email setup for sending to HR, I'll use another email account, set body to Html and input the information needed for HR onboarding, select continue and hit test step.  
You should get an email like and good for testing:  
<img width="1526" height="293" alt="image" src="https://github.com/user-attachments/assets/28ac28d5-7e94-495a-a396-99ab0cb434ad" />  
Next its time to do another email setup for sending to the manager, I'll use another email account such as Outlook, make sure to CC the HR email, set body to HTML, input the information needed for new team member stuff, select continue and hit test step.  
Should get an email like this and good for testing:  
<img width="1321" height="826" alt="image" src="https://github.com/user-attachments/assets/c20fd9e1-77ea-40a3-9a16-d10862f0af62" />  

For the next step, create an account with Jira then go to atlassian.com/try/cloud/signup and create a test site such as testsite2309.atlassian.net, select the role you are and so forth till you get here:  
<img width="1910" height="901" alt="image" src="https://github.com/user-attachments/assets/6c6ff531-aef5-4103-add2-7cde9f3dfa42" />  
Then go back to Zapier and add Jira Software Cloud with the action event of create issue and allow access to the new site by setting the value to true and the site name like so:  
<img width="966" height="622" alt="image" src="https://github.com/user-attachments/assets/cf832cd1-c671-4c26-8851-341b0b3e48b8" />  
*Note leave it false since you are not signing into a gov one.*  
Then go find the tab that says create a project and name it Onboarding like so:  
<img width="1906" height="902" alt="image" src="https://github.com/user-attachments/assets/076fe28f-c8a6-41c7-ab76-d71bf79a0162" />  
Then in Zapier, select the project as Onboarding, issue type as task, assign to yourself with a description, set priority to high, and set the summary to something like IT Setup and the info needed, select continue and hit test step:  
<img width="1634" height="605" alt="image" src="https://github.com/user-attachments/assets/5a064aab-800f-4a4b-b67b-745249904a40" />  
<img width="1282" height="793" alt="image" src="https://github.com/user-attachments/assets/e15353e6-2cca-4e78-8890-128af8644328" />  

Then for the next step is to create a Jira ticket with HR tasks  
Once again choose Jira Software, select project Onboarding once again with create issue task, assign to yourself with a description, set priority to high, and set the summary to something like HR Onboarding and the info needed, select continue and hit test step:  
<img width="1636" height="731" alt="image" src="https://github.com/user-attachments/assets/b2b3d4e6-e94a-408c-97d5-fef218f158ef" />  
<img width="1271" height="786" alt="image" src="https://github.com/user-attachments/assets/c144a5dc-1086-4b94-b94f-84c66a8a07e8" />  

Then for the next step is to create a Jira ticket with Manager prep tasks  
Once again choose Jira Software, select project Onboarding once again with create issue task, assign to yourself with a description, set priority to medium, set the summary to something like Manager prep and info needed, select continue and test step:  
<img width="1884" height="840" alt="image" src="https://github.com/user-attachments/assets/0516ae81-dba6-4654-b866-3ffd351cd485" />  
<img width="1282" height="794" alt="image" src="https://github.com/user-attachments/assets/571c7791-18d9-49d8-b0c3-a20432169ce7" />  

Then for the next step is to update the dashboard with Jira links  
Set up another action with Google Sheets, action with Update Spreadsheet Row, and add the Links to the Jira Tickets in there, make sure to also create a early action step that for the Onboarding Tracker with a dashboard for the Jira tickets.  
Like so:  
<img width="368" height="371" alt="image" src="https://github.com/user-attachments/assets/69d55951-936c-4bea-870c-655d94757c6f" />  
<img width="1843" height="709" alt="image" src="https://github.com/user-attachments/assets/6aaadf85-1411-4694-b8aa-19a860a607d6" />  

Then as a final step is to create a action that sends the manager an email.  
Set up a gmail sender, with the subject matter, body to plain, input information needed, select continue and test the step:  
<img width="775" height="703" alt="image" src="https://github.com/user-attachments/assets/7aafb911-9b08-40ae-ba77-4939d40ca8e5" />  

After testing, publish the Zap with a name of New Hire Onboarding Automation and make sure it is saved.  
Then go to the Google Sheets dashboard with the info for IT Status, HR Status and Manager Status to conditionally format them with Complete being green, in progress being yellow, and pending being red or different cases:  
<img width="1834" height="499" alt="image" src="https://github.com/user-attachments/assets/b12d9a45-f710-4305-9602-294b91d71ff5" />  















































