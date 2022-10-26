# CMPG-323-Project-4---30857465
# Expectations & implementation:
- Read the data from Excel into UiPath & Ensure that the data is readable and iterated over in UiPath:

used an excel process scope

used a "for each excel row" to iterate through the info
- For each record in the data table, navigate to the URL in the browser that allows data to be entered to create a new record:

used a "for each excel row" to iterate through the info

used "Use Browser Chrome: Create Zone/Category/Device - Connected Office: Device Management" to navigate to page
- Insert the fields from each record into the fields on the web application to create a new record on the web application:

used a "type into" activity to enter the info from excel into the necessary fileds
- Click the ‘submit’ button on the web application to create a new record :

used a "click" activity to click the necessary buttons
- Navigate to the URL where you can view the newly created record on the web application:

used a "click - Back To List" activity to navigate back the the newly created record
- If the item was created successfully, update the data table record to depict that the record passed testing. If the item was not created, update the data table to depict that the
record failed testing:

used "check state" to ensure item was created
used a "write line" to update the table to show if it was sucessful or not
- view created record:

used a "click" with variable for the target and anchor to view the last created record
- update created record:

used a "click" to navigate to the update record page

used a "type into" to update the record

used a click to save it
- delete created record:

used a "click" with variable for the target and anchor to view the last created record

used "click" to click delete and confirm delete

# how to use:
step1: enter the excel file path in quotation marks 


![Screenshot 2022-10-26 220956](https://user-images.githubusercontent.com/83824060/198128606-58c39d4f-d491-4782-af2f-15ebb9867513.png)

step2: enter username

![2](https://user-images.githubusercontent.com/83824060/198127651-ceb4432a-9a81-4fe7-9b76-496d30bf816d.png)

step3:enter password

![Screenshot 2022-10-26 221138](https://user-images.githubusercontent.com/83824060/198127809-1a38cca5-34d5-4135-90cf-260fd6982909.png)

step4: click the drop down and select "enter"

![4](https://user-images.githubusercontent.com/83824060/198128294-c365cfd3-e54f-4c45-9702-64b2508c31d6.png)

step5: return to main.xaml and run the process

<img width="47" alt="last" src="https://user-images.githubusercontent.com/83824060/198128786-f0889b18-5a57-4b05-b356-78aed116a3fd.png">


