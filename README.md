# MyStore_1
Simple ASP.NET project with SQL database

# Issues during Development
### First Major Issue: Running the webpage
Ran into this error: `Process with an ID of #### is not running` in Visual Studio 2022.
Referred to [this Stack Overflow page](https://stackoverflow.com/questions/26424902/process-with-an-id-of-is-not-running-in-visual-studio). The working solution for me personally was deleting the original project folder "MyStore" and IISExpress and installing the latest .NET 6.0 SDK [here](https://dotnet.microsoft.com/en-us/download/visual-studio-sdks).
