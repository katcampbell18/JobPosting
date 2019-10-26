You are to write an application that is kind of like Craigslist, but for jobs only. It will allow a user to post a job that someone needs, and everyone else has the ability to see all the jobs that have been posted. 

Users can edit and delete their own jobs. 

Build an application that allows users to add jobs, list jobs and view jobs.

Your client has requested specifically for a unified look across all your pages. Your program manager has made these styling mandatory:

Same navigation bar across all pages. 
In the navigation bar, give your app a name (eg. "Taylor&Oscar's Wedding"), or a logo.
Each button must have meaningful names (ie. "Home" is fine. "Link1" or "Page1" is not.)
Job object should have at least the following attributes:

title
description
postedDate
author
phone
Features/Functionalities:

The home page ("/") path should point to a list of all jobs
Every page (or template) should have link (or button) to the add path 
("/add") which will lead to the new job form
Use a repository to store your jobs
The user should be able to update, view single jobs on their own page, and delete jobs.
The postedDate variable must be a Date object using the Date class.
There must be a navigation bar that includes a simple search function that uses a query from your repository.
The search should then display a list of jobs with whatever variable you choose to search with.
Add Bootstrap and styling to make your pages look Professional.
Once your application is working, put it on GitHub.
Submit your GitHub repository link.
Done Already?

Add in more than one variable to your query method.
Add an alert with Javascript to tell them they submitted a job posting.
*SPECIAL HARD CHALLENGE*

If you completed that please now give the ability to take a search phrase that is separated by spaces  such as "grass work" and use your query to search "grass" and then "work" and show all the jobs with either grass or work. 
