# SkillReceive

SkillReceive is a web application designed to help people **share and learn new skills** through online courses and hands-on experiences.

Users can explore available skills, join courses, and become creators to share their own knowledge and experiences with others.

The application was developed using **C# and ASP.NET Core MVC**, with Entity Framework Core and SQL Server for data management.

## Features

- Browse and search for available skills and courses.
- Filter and sort skills by different criteria.
- Register and log in to a personal account.
- Join online courses and hands-on experiences.
- Become a creator and publish your own courses.
- Manage, edit, and delete created courses.
- Administrator approval and management of skills.
- Support for English and Bulgarian.

## Technologies Used

- **Backend:** C#, ASP.NET Core MVC (.NET 6)
- **Frontend:** HTML, CSS, JavaScript, Bootstrap, Razor
- **Database:** Microsoft SQL Server
- **ORM:** Entity Framework Core
- **Authentication:** ASP.NET Core Identity

## Getting Started

### Prerequisites

Before running the application, make sure you have:

- .NET 6 SDK
- Microsoft SQL Server
- Visual Studio, Rider, or another compatible IDE (optional)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/alexmanev-code/SkillReceive.git
   cd SkillReceive
   ```

2. Configure your SQL Server connection using .NET user secrets:

   ```bash
   cd SkillReceive
   dotnet user-secrets set "ConnectionStrings:DefaultConnection" "YOUR_CONNECTION_STRING"
   cd ..
   ```

3. Restore dependencies:

   ```bash
   dotnet restore
   ```

4. Run the application:

   ```bash
   dotnet run --project SkillReceive/SkillReceive.csproj
   ```

5. Open the localhost address displayed in the terminal.

Once the application is running, you can register an account, explore available skills, join courses, or become a creator.

## License

This project is licensed under the MIT License. See [LICENSE.txt](LICENSE.txt) for details.
