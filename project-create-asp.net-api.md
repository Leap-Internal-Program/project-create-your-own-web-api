#  Project: Create ASP.NET Web API
## Summary
Create a ASP.NET Web API.

## Estimated time
Estimated time is six hours.

## Resources to Review
- LinkedIn Learning - [Building web APSs with ASP.NET core](https://www.linkedin.com/learning/building-web-apis-with-asp-dot-net-core-3/)
- MS Docs - [Tutorial: Create a web API with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio)

## Projects
Create a Web API following the examples from earlier in the week.  You will be using this API later in class when building a web client. Your web client in a future week will retrieve information from this API.

This is a partner project.  Upload the completed project to one person's GitHub.  Take turns working from you and your partners machine, switching the driver and navigator about once an hour.


### Example of good API projects
- A database for the books and movies someone owns.
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

Optionally create DTO objects

### Getting started
After brainstorming and choosing an idea, write down the MVP functionality of your application with your partner.  Then write down the additional features you would like to add.

A recomended approach is to come up with two or more model classes.  Use POCO models.  POCO stands for
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
- Create model classes
- Adding a database context that coordinates with Entity Framework
- Registering the database context
- Scaffolding your controller

