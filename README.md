# TaskTracker
Objective:

This application is intented for multiple users to add and complete tasks. Users can login/signup and the home page is only accessible to logged in users.

The home page has a list of all incomplete tasks, and the ability to add new tasks. Each user can select any task and mark that they are working on it, which changes the status of the task to "in progress", with the name of the user working on it. 

When the user that chose a task completes a task, they can mark the status of the task as"Complete" and that task disappears from the table for all users.

Solution:

The backend of this application is written in C# using ASP.Net Core with React framework. It is connected to a SQL Server Management Studio database via Entity Framework Core. The frontend code is written in JavaScript using the React and SignalR libraries. 
