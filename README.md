# Live Project

Introduction:

To conclude my boot camp at The Tech Academy, I participated in the development of a software for a local theater company here in Portland. We used Visual Studio as our IDE and the project was an MVC app that utilized the .NET Framework, a setup I’ve grown comfortable with throughout the C# boot camp. For the majority of the project, I developed the Blog Author section, making it easy for an administrator with no tech knowledge to create, edit, and delete authors. I gained experience working on front and back end assignments in this area of the program. Throughout this project I also gained more exposure to version control while working on a team, gained some familiarity working with Azure Devops, and participated in Daily Standups which helped keep my projects on the right track timewise. 


[Back End:](https://github.com/tabii238/Live-Project/tree/main/BackEnd)


- Created a [Blog Author Model:](https://github.com/tabii238/Live-Project/blob/main/BackEnd/BlogAuthorModel.png) 
   - In this story I created the BlogAuthor model, controller, and CRUD pages so that blog authors could be created, edited, and deleted by the user.

- Created an [Admin model:](https://github.com/tabii238/Live-Project/blob/main/BackEnd/HeadAuthor-AdminModel.png)
   - This assignment required creating a Head Author/Admin model only, with the controller and CRUD pages intended to be created in a later story.

- Created a [partial view](https://github.com/tabii238/Live-Project/blob/main/BackEnd/BlogAuthorPartialViewCode.png) for the index page:
   - For this assignment, I created a partial view in the Project’s Shared folder that displayed the blog authors details such as name, bio, and dates joined/left. On the Index page, I rendered this view for each author in the database.

[Front End:](https://github.com/tabii238/Live-Project/tree/main/FrontEnd)

- [Donation Page Styling:](https://github.com/tabii238/Live-Project/blob/main/FrontEnd/Code/DonationPageCode.png) 
   - This was the first assignment I completed, and I was tasked with styling the Donation Page beyond what a previous developer had created. I changed the font of the title of the page and added spacing so it wasn’t visually cramped, added an image behind the title and above the form, added a shadow behind the form and image, changed the text boxes so that they are gold when hovered over, changed the font of the text in the form to fit the general theme, and centered the Submit button in the form
   
- Blog Author CRUD pages Part 1: [Create](https://github.com/tabii238/Live-Project/blob/main/FrontEnd/Code/CreatePageCode.png) and [Edit](https://github.com/tabii238/Live-Project/blob/main/FrontEnd/Code/EditPageCode.png) pages:
   - I added styling to the forms on the Create and Edit pages, changed the date section so that the user can now select the date and time in one field, and also changed the “date-left” field so that it is now optional and only the “date-joined” field is required.
   
- Blog Author CRUD pages Part 2: [Details](https://github.com/tabii238/Live-Project/blob/main/FrontEnd/Code/DetailsPageCode.png) and [Delete](https://github.com/tabii238/Live-Project/blob/main/FrontEnd/Code/DeletePageCode.png) pages:
   - For this, I changed the format of the page to be a card with buttons on the top so that the user can transition between the “Author-Details” tab and the author’s blog posts on a separate card. The blog post section had not been finished and linked yet, so the rest of this would need to be developed further at a later date. I also added social media icons to the top right of the Author Details Card, each link taking the user to the Home Page of the social media site for now. Finally, I styled and added FontAwesome icons to the buttons at the bottom of the page. 
   
- Blog Author CRUD pages Part 3: [Index page:](https://github.com/tabii238/Live-Project/blob/main/FrontEnd/Code/IndexPageCode.png)
   - This page renders a partial view of the author’s details foreach author in the database. For styling, I had to move the “delete” and “edit” buttons inside the form, and also added a “details” button. I also styled the “Create” link at the top under the title and changed the fonts and colors on the page to fit the general theme. 

