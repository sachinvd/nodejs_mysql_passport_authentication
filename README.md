# nodejs_mysql_passport_authentication
Authenticates user using passport-local using mysql as a database and mustache as a template engine.

#Requirements
1. MySQL
Create a table with following field or update app.js accordingly
Login table,
ID
username
passport

2. I have used mustache template engine instead of standard jade template

#ThingsToAdd
1. for password verification bcrypt can be used instead of plane text verification.
