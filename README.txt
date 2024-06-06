Karanvir Kumar Sharma
ISO Format

Part 1:
Part 2:

Part 3: Added a view: index.cshtml
tested the site with helloworld: worked fine.
Changed title, footer, menu link: in layout file
Privacy link updated in /Home/Privacy


20240523184153_IntitialCreate

Part 4:
1:45pm Added a data model class in Models with the name: Movie.cs
1:55pm Added NuGet packages
Took a little time but no error at this stage
2:10pm Scafforld movie pages
Added New Scafforlded Item using Add MVC controller with views, using Entity Framework wizard.

2:55pm Added some movies and Atleast four movies.

Migration: using powershell
Done

3:10pm: Tested the app. Worked fine so far.

3:25pm: Tried to update Release Date. Tried to edit, class
some steps: Possible using html editing manually.
Editing the class breaks every references.
Only typing "release date" manually in view pages does work but that would not fix the underline issue.

3:40pm Also tried changing class(although not recommended as it got 12 references but still did it), it broke the references but the pages worked and the issue was still not fixed)


Part 6:
3:45pm : Used Models/Movie.cs file and updated the file as instructed.
Release date was fixed after restarting the page.



20240530184153_IntitialCreate
2024-05-30
1330

1:30pm: Part 4 (covering up)
Checked and ran it. Worked fine.
Reviewed "Release Date". Worked fine also.

Part 5:
1:45pm: Program.cs
Updated the C# code.

1:55pm: JSON: ConnectionString update
Wrong step(not to edit/create, just to verify). As per the instructions, it was for the information only. Hence, moving on.

2:05pm: Created Github account

2:15pm: Added the seed initializer
Delete all the records in the database. From where?

2:30pm: Took me a while to figure out but remembered the last class.
Deleted all the records in https://localhost:7293/Movies and restarted.
It still did not fetch the records from Program.cs.
CTRL+F5 was the saviour.

3pm: Tried cloning github repository but it did not update correctly and created another redundant repository.

3:10pm: Successfully I was able to sign in to github in Visual basic but still sync was the issue.
No specific error but attempted to remove redundant repos and tried to sync again. Failed.
Removed all duplicates and moving on with the part 6 now.

Part 6:
3:25pm: models/movie.cs: Added the code to update the hyperlinks for links such as on edit.
Edited file: Views/Movies/Index.cshtml

2024-06-06
2:10pm: Getting error: An unhandled exception occurred while processing the request.
Checked error related to Rating. mentioned in SqlException: Invalid column name 'Rating'
Checked in the instructions on Microsoft website but nothing was realted to this specific error.

Two scenarios I found related to this in error page:
dependency injection>> Program.cs or Startup.cs page

In Views> Movies > Edit.chtml, Rating option was corrected in ReleaseDate segment( in Div Class form group)
Saved and re ran but the issue persisted.

2:30pm: Observed typo releasedate instead of Rating in Views > Movies and all pages such as Created, Edit, Details etc.
Corrected it and tried to run it.

The error was limited to https://localhost:7293/movies
but now, the whole site(https://localhost:7293) had this error but the error message remained the same.

3pm: Got help from Professor and was directed to perform commands,
Tools> Package manager console
Add-Migration AddRatingColumn
Update-Database

More errors started showing.

Closed and restarted Visual basics and retried the steps(as mentioned above). Worked this time and got the site working again with Release Date.





