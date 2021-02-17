# Creating an azure function

## create new function

```
Cmd + Shift + P
``` 
to open the command palette
type: Azure Functions: Create New Project

choose javascript, http trigger, and some authorization level

Choose the run icon from the VSCode menu bar ( on the left )

in the drop down at the top, choose Node.js, and the drop down to the right choose - Run Script: start

The terminal should open below, and run your http trigger

Check the url posted below and it should read:
"This HTTP triggered function executed successfully. Pass a name in the query string or in the request body for a personalized response."

Now add "?name=ewan_mcgreggor" to the url

The browser should now display:
"Hello, ewan_mcgreggor. This HTTP triggered function executed successfully."

Congrats, you did a great job!
