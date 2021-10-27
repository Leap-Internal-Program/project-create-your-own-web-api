#  Project: Create ASP.NET Web API
## Summary
Design and create your own ASP.NET Web API.

## Estimated time
Estimated time is six hours.

## Resources to Review
- LinkedIn Learning - [Building web APSs with ASP.NET Core](https://www.linkedin.com/learning/building-web-apis-with-asp-dot-net-core-3/)
- MS Docs - [Tutorial: Create a web API with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio)

## Projects
Create a Web API following the examples from earlier in the week.  Your web client in a future week will retrieve information from this API.

This is a partner project.  Upload the completed project to one person's GitHub.  Take turns working from you and your partners machine, switching the driver and navigator about once an hour.

### Example of good API projects
- A personal database for adding books and movies
- Productivity app that tracks work orders
- Family chore tracking application

### Objectives and requirements
| Project objectives |
| :-- |
| Demonstrate learning through following an example of another project. |
| Have a minimum of ten endpoints. | 
| Minimum of two POCO classes |
| Make a minimum of five commits. |
| Use the await keyword when making async call to the database. |
| Make calls with Postman to an API. |
| Implement Entity Framework. |

Optionally create DTO objects.

### Getting started
Spend time brainstorming and choosing an idea.  Remember you will be calling this API in future weeks. Write down the MVP functionality of your application with your partner.  The MVP functionality may be a list of endpoints for the project.  Then write down any additional features you would like to add.

A recomended approach is to start with two or more model classes.  Use POCO models.  POCO stands for
- Plain
- Old
- CLR
- Objects

POCO classes have properties and the class will be used to define the data to be stored in the database.  An example POCO class is: 

```csharp
public class TodoItem
{
    public long Id { get; set; }
    public string Name { get; set; }
    public bool IsComplete { get; set; }
}

```
You may extend the functionality of your application, for example by having it save to a SQL database instead of keeping the information in memory.  It is recommended to reach out to the instructor for guidance and discussing the functionality of your application.

Remember to review the below steps from [Tutorial: Create a web API with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio):
- Create model classes
- Adding a database context that coordinates with Entity Framework
- Registering the database context
- Scaffolding your controller

