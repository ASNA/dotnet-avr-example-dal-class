## AVR for .NET DAL example

This class is an example of externalizing data access from an application. This provides a separation of concerns between application specific operations and those that are repeatable and reusable. The advantages this provides are:

* This class can be used in any project that needs a navigation list over a customer file. 
* This class can be used by either Windows, web, or even web services applications. 
* This class can be consumed by VB.NET, C#, or AVR. A common use of AVR is to empower RPG programmers
  to create IBM i-specific file operation and business logic classes that can later be consumed by C#
  programmers. This lets the C# programmers have effective access to the IBM i without needing to learn 
  its nuances, its RPG's record level access model, or worry about acquiring, configuring, and keeping the
  ADO.NET data provide up and running. 
* This (rather simplistic) class passes list data to its consuming project as a System.Data.DataTable. It may
  be desirable to use a generic List of Customer object or an array of Customer objects as an alternative 
  to the DataTable. However, the DataTable is quite servicable, especially in Windows applications.  

#### Annotated code

[ListByName.vr - The AVR for .NET DAL class ](https://asna.github.io/dotnet-avr-example-dal-class/ListByName.html)

