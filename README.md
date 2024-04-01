# MyStore_1
Project placed on hiatus following the deaths of 2 close family members in summer and late 2023.

# Purpose of the Project
- Learn basic connections between C#, ASP.NET, and SQL tables 
- Find a good starting point to relearn C# and linking it to SQL

# Issues during Development
### First Major Issue: Running the webpage
Ran into this error: `Process with an ID of #### is not running` in Visual Studio 2022.
Referred to [this Stack Overflow page](https://stackoverflow.com/questions/26424902/process-with-an-id-of-is-not-running-in-visual-studio). The working solution for me personally was deleting the original project folder "MyStore" and IISExpress and installing the latest .NET 6.0 SDK [here](https://dotnet.microsoft.com/en-us/download/visual-studio-sdks).

### Second Issue: Edit URL wasn't getting the item's ID
I forgot to set the value to the item's binding. 

What the mistake was: `<a class="btn btn-primary btn-sm" href="/Clients/Edit?id=">Edit</a>`

Should be: `<a class="btn btn-primary btn-sm" href="/Clients/Edit?id=@item.id">Edit</a>`
