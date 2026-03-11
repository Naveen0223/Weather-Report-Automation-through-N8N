# Weather-Report-Automation-through-N8N
This N8N workflow sends the customized weather report everyday to the employees working in different locations accordingly. The Email sent will be in a HTML format which looks professional and attractive enhancing the UI/UX to the employees of an orgaization.


Nodes used:

->Schedule Trigger node (Time based)
->Get Rows in sheet (Spreadsheet, require credentials)
->Loop Over Items
->HTTP Request (To get the weather report)
->Edit Fields (To select the required fields)
->Switch (To add constraints based on weather condition)
->Edit Fields
->Send a message (Through Gmail)
