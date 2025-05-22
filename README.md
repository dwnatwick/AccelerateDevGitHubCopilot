
# Library App

## Description

Library App is a simple application designed to manage books, users, and borrowing activities in a library system. It provides functionality for adding, updating, and searching for books, as well as managing user accounts and tracking borrowed items.

## Project Structure

- `src/`
    - `LibraryApp/`
        - `Program.cs`
        - `Models/`
            - `Book.cs`
            - `User.cs`
            - `Loan.cs`
        - `Services/`
            - `LibraryService.cs`
            - `UserService.cs`
        - `Interfaces/`
            - `IBookRepository.cs`
            - `IUserRepository.cs`
            - `ILoanRepository.cs`
    - `LibraryApp.Tests/`
        - `LibraryServiceTests.cs`
        - `UserServiceTests.cs`
- `README.md`
- `LICENSE`

## Key Classes and Interfaces

- **Book**: Represents a book in the library, including properties such as title, author, and ISBN.
- **User**: Represents a library user, including user details and account information.
- **Loan**: Tracks the borrowing of books by users, including due dates.
- **LibraryService**: Provides core library operations such as adding books, lending, and returns.
- **UserService**: Handles user registration and management.
- **IBookRepository, IUserRepository, ILoanRepository**: Interfaces for data access and repository patterns.

## Usage

1. Clone the repository:
     ```bash
     git clone https://github.com/yourusername/LibraryApp.git
     ```
2. Navigate to the project directory and build the solution:
     ```bash
     cd LibraryApp
     dotnet build
     ```
3. Run the application:
     ```bash
     dotnet run --project src/LibraryApp
     ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
