# Time-tracker
works like a timer but when the timer is ended an event is created on google calendar.

## How to:
nothing complicated, click start to begin the timer and click end to stop the timer. Ending the timer will result in an event being created on the selected google calendar.

## Things to note: 
google calendar does not create events of a time period shorter than 1 minute. Also you need credentials from google cloud apis. Register an applicaion and get credentials; the calendar logic file will handle authentication. Just create a crednetials.json file, using the credentials from google, in the credentials folder.

The token and credentials folders should be empty because they contain sensitive info.

