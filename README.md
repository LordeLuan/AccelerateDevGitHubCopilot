# Library App

## Description
Library App is a .NET-based library management system that allows users to manage patrons, loans, and books. It includes a console application for user interaction and supports JSON-based data storage.

## Project Structure
- `AccelerateDevGitHubCopilot.sln`
- `src`
  - `Library.ApplicationCore/`
    - `Entities/`
    - `Enums/`
    - `Interfaces/`
    - `Services/`
    - `Library.ApplicationCore.csproj`
  - `Library.Console/`
    - `appSettings.json`
    - `CommonActions.cs`
    - `ConsoleApp.cs`
    - `ConsoleState.cs`
    - `Json/`
    - `Library.Console.csproj`
    - `Program.cs`
  - `Library.Infrastructure/`
    - `Data/`
    - `Library.Infrastructure.csproj`
- `tests`
  - `UnitTests/`
    - `ApplicationCore/`

## Key Classes and Interfaces
### Library.ApplicationCore
- **Entities**
  - `Patron`
  - `Loan`
- **Enums**
  - `LoanExtensionStatus`
- **Interfaces**
  - `IPatronRepository`
  - `ILoanRepository`
- **Services**
  - `LoanService`
  - `PatronService`

### Library.Console
- **ConsoleApp**
- **CommonActions**
- **ConsoleState**

### Library.Infrastructure
- **Data**
  - `JsonData`
  - `JsonPatronRepository`
  - `JsonLoanRepository`

## Usage
1. Clone the repository.
2. Open the solution file `AccelerateDevGitHubCopilot.sln` in Visual Studio.
3. Build the solution to restore dependencies and compile the projects.
4. Run the `Library.Console` project to start the console application.
5. Follow the on-screen instructions to search for patrons, view details, and manage loans.

## License
This project is licensed under the MIT License.
