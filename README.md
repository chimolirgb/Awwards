### Awards
This python/django web-app was created as a clone of the website 'Awards'. Date: 19th July 2021

## Project Description
This web-app allows a user to create a Profile,Category,Country,Technology,Color and Projects that are all under his username allowing other users to vote for them and visit the particular projects site.

### Setup/Installation Requirements
Live site can be accessed from the following link https:https://github.com/chimolirgb/Awwards

### Known Bugs
None

### Behaviour Driven Development
The program should return all projects on the directories page
Given:All projects
When: Url is changed to directory page
Then: All projects are displayed

Program should show the project with the highest number of votes on the caraousel on the home page
Given:A Project with the highest votes
When: Home page is accessed
Then: Project with highest votes is displayed

Admin site should be displayed when "admin/" url is chosen
Given: An admin url
When: User enters admin url in browser
Then: Admin Login is displayed

User authentication occurs when Admin tries to Login
Given:Admin page is accessed
When: User tries to login
Then: User details are authenticated to confirm if user is an admin

### Technologies Used

Vscode was the source code editor of choice.
Git and Github were used as my local and online repositories respectively.
Django was used as the framework of choice
Heroku was used in deploying the live site
Postman was used in testing the API

### License
Mtn Copyright(c)2021 Awards by Lucy Chimoli