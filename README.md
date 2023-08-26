# CustomFeedbackForm
This was created to experiment with Google forms
Using the given method we can change the way our form is displayed rather than the default way we can set up our custom html which will be displayed
I am mentioning the steps required below
Step 1: Create a Google Form with the necessary fields required 
Step 2: Settings -> Get pre-filled link
Step 3: Add some info in the input fields for indentification
Step 4: Get Link -> Copy Link
Step 5: In the copied link find "viewform" and change it to "formResponse"
Step 6: In the copied link you will also find the field names as "entry.1335244525=email"
Step 7: Remove everthing from the link after "formResponse"
Step 8: In the html file use the above link as action='link' in the form tag
Step 9: Use the field names as name attributes in the form

