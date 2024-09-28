The project issuetracker to track issue/ bugs for a project done thorugh node+ejs


Following tools i have used- -:
1. Nodejs
2. Express
3. ejs
4. Mongodb
All coding done in Vs code

FOllowing are the key feature i have added-:

1.Build a neat UI

2.Home Page
    Show a list of projects.
     Give a button to create a new Project (On creating a new project it should appear in the list)
     
3.Create Project Page
    -> Accept the following fields to create a project
       . Name
       .Description
       .Author
       
4.Project Detail Page
  -> When the user clicks on a project (in home page) redirect the user to this page which will show bugs related to this project
     User should be able to perform following actions on this page
     Filter by multiple labels i.e. I should be able to filter by 2 or more labels at the same time
     Filter by author
    Search by title and description
    A button to create an issue
    
5.Create issue page
    User should be able to create an issue for a project
     Accept the following fields
       Title
       Description
       Labels (multiple labels can be added to a project, IF a project has a label already show it (in dropdown) as the user types the label in)
       Author
