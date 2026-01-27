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
After testing it. 














