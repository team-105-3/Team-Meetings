Members Present: Vincent Liu, Nick Elsasser, Lara Chunko, Tianchen Wang, Jacob Hough, Nikhil Rajaram

Slack Link: https://join.slack.com/t/smartcalworkspace/shared_invite/enQtNTYyMjIwMTc1MDA4LTNjZTgyNTM1Y2M4NmVlNTkxNmQxNTQxZTAyZDI5MWZiOWJlMDk0YjYyYjBjM2ZjYWUzNTU3ZTY4MDhiNWUzN2Y


<b>Goals:</b>

Vincent = make the calendar

Nick, Jacob, Nikhil = (backend, integration layer) data storage and retrieval 

basic login abilities done by next meeting:
  - Login sends request to server
  - Server gets login data from database
  - Sends response back to user
  - Tianchen, maybe Jacob = frontend (look of the website)
  
Roles discussed in meeting (not set it stone):
  - Nick: Handling request from login page
  - Nikhil: Login Database
  - Jacob: Handling requests
  - Lara: Front end login page
  - Tianchen: Front end login page
  - Vincent: Basic calendar class


<b>What we need at the bare minimum:</b>

Login page
  - Email
  - Password
  - Password reset (security question)
  
Database to store data
  - Store login info
  
Add events 
  - Extra: Recurring events
  
Remove events

Reminder system (email)

Implement calendar (day, time)
  - Extra: Multiple calendars
  
Smart planning


<b>Things to know / review:</b>

Java server
  - Basic server set up in repo here: https://github.com/team-105-3/Backend/tree/server/src/main 
  - Understand how the request is handled and how the response is generated
Ajax
  - Basic Ajax call to the server in repo here: https://github.com/team-105-3/Frontend/blob/master/testserver.html
  - Understand how a ajax call is created for the front end and sent to the backend
  - Understand how to get/handle the response from the backend
JSON
  - We’ll probably use JSON format for storing and sending data
  - Gson java library for backend will help with this
  - Know how to package data into JSON from front-end so it can be sent to the server
  - If you want to work on requests on the backend learn how to use Gson in java (slightly more complex than JSON in javascript)

<b>How to test front end calls to server:</b>
	- For now, the server is really simple, when you send an ajax request to the server it prints out the request data to the console of the server (IntelliJ console) and sends a string back to the user in response.

<b>To run the server:</b>
1) clone the server GitHub repo above to a folder. 
2) Open up the folder as an IntelliJ project. 
3) If there is no green run arrow in the top right go to step 5 otherwise step 4
4) Press the green arrow in the top right to run the server
5) If no green arrow then go to Main class and next to the main(String args[]) function on the left there is a little green arrow
6) Click that arrow to run the server

If you modify the server, create your own branch in git so your modifications don’t mess with the server on GitHub.
