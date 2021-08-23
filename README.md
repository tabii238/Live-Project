# TechAcademy_LiveProject

Introduction:

To conclude my boot camp at The Tech Academy, I participated in the development of a software for a local theater company here in Portland. We used Visual Studio as our IDE and the project was an MVC app that utilized the .NET Framework, a setup I’ve grown comfortable with throughout the C# boot camp. For the majority of the project, I developed the Blog Author section, making it easy for an administrator with no tech knowledge to create, edit, and delete authors. I gained experience working on front and back end assignments in this area of the program. Throughout this project I also gained more exposure to version control while working on a team, gained some familiarity working with Azure Devops, and participated in Daily Standups which helped keep my projects on the right track timewise. 

Back End: 

- Created blog author model: in this story I created the BlogAuthor model, controller, and CRUD pages so that blog authors could be created, edited, and deleted by the user.

- Created Admin model: This assignment required creating a Head Author/Admin model only, with the controller and CRUD pages intended to be created in a later story.

- Created a partial view for the index page: Created a partial view in the Project’s Shared folder that displayed the blog authors details such as name, bio, and dates joined/left. On the Index page, I rendered this view foreach author in the database.

Front End:

- Donation Page Styling: This was the first assignment I completed, and I was tasked with styling the Donation Page beyond what a previous developer had created. 
   - Changed the font of the title of the page and added spacing so it wasn’t visually cramped,
   - Added an image behind the title and above the form, 
   - Added a shadow behind the form and image,
   - Changed the text boxes so that they are gold when hovered over,
   - Changed the font of the text in the form to fit the general theme, 
   - Centered the Submit button in the form.
   - 
- Blog Author CRUD pages Part 1: Create and Edit pages:
   - Added styling to the forms on the Create and Edit pages
   - Changed the date section so that the user can now select the date and time in one field.
   - Also changed the “date-left” field so that it is now optional and only the “date-joined” field is required.
   - 
- Blog Author CRUD pages Part 2: Details and Delete pages
   - Changed the format of the page to be a card with buttons on the top so that the user can transition between the “Author-Details” tab and the author’s blog posts on a separate card. The blog post section had not been finished and linked yet, so the rest of this would need to be developed further at a later date. 
   - Also added social media icons to the top right of the Author Details Card, each link taking the user to the Home Page of the social media site for now.
   - Styled and added FontAwesome icons to the buttons at the bottom of the page. 
   - 
- Blog Author CRUD pages Part 3: Index page: This page renders a partial view of the author’s details foreach author in the database. 
   -  For styling, I had to move the “delete” and “edit” buttons inside the form, and also added a “details” button. 
   - Also styled the “Create” link at the top under the title and changed the fonts and colors on the page to fit the general theme. 

