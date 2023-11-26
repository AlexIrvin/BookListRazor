<H1>BookListRazorPage </H1>
<h3>This Web Application explores the creation of a Book List using the .NET Core framework. </h3>
<h3> Lessons Learned </h3>
<p>Through this project I gained a better understanding for not only entity framework, asynchronous design, and CRUD applications, but also, razor pages, client-side data validattion, JSON serialization, and styling with external CSS and JavaScript.<br>
  I plan on expanding upon the concepts I learned here with an upcoming project designed around cocktail recipes.</p>
<h3>Steps are as follows: </h3>
<h4> - Razor Pages and Server-Side Code - </h4>
<p1>1.) Initialized ASP.NET Core Web App<br>
2.) Installed NuGet Packages: Microsoft.EntityFrameworkCore, .SqlServer, and .Tools.<br>
3.) Built out ApplicationDbContext.cs and tied into Program.cs.<br>
4.) Created data model in Book.cs with ID as primary key, and Name, Author, and ISBN as non-nullable fields.<br>
5.) Created BookList directory for razor pages with Index page for book list.<br>
6.) Utilized dependency injection to instantiate new object of ApplicationDbContext within Index page.<br>
7.) Included IEnumerable collection "Books", and utilized OnGet method to assign asynchronously retrieved list.<br>
8.) Added data migration and updated database via NuGet Package Manager Console.<br>
9.) Built out Index page and Create page, exploring use of ASP tag helpers, HTML tags, and Bootstrap.<br>
10.) Explored use of model binding attributes like [BindProperty] for passing HTTP requests into input models.<br>
11.) Built out input validation functionality on server-side to display in web form.<br>
12.) Built in client-side input validation with use of call to _ValidationScriptsPartial on Create.cshtml<br>
13.) Built out Edit page, passing in id variable to Get method from index page via tag helper.<br>
14.) Added Delete functionality with OnPostDelete method for Index page and an action confirmation popup with onclick code. </p1><br>
<h4> - JavaScript Data Table - </h4>
<p1> 15.) Included CSS and JS from Cloudflare, Toastr, and SweetAlerts.<br>
16.) Built API with BookController.cs for JSON Serialization to use in javascript data table.<br>
17.) Added in Edit and Delete functionality via BookController and tagged buttons with CSS and JS fucntionality.<br>
18.) Built Upsert page, using Edit page as framework, and adding including functionality for Creating as well. </p1><br>

