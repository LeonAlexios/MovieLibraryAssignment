[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/xXvJQoMP)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=13891172&assignment_repo_type=AssignmentRepo)
# Movie Library Application Development

We are embarking on creating a Movie Library application. This project involves working with an initial movie data file, specifically `movies.csv`.

## Key Features and Implementations

### 1. **List All Movies in the File**
- **Efficient Display**: Implement a user-friendly way to list movies without just scrolling through all entries. Consider using a NuGet package like `ConsolePager` for smart pagination.

### 2. **Add Movies to the File**
- **Unique IDs**: Ensure that duplicate IDs are not entered. Implement logic to determine the next appropriate `movieId` for new entries.
- **No Duplicate Titles**: Prevent the addition of movies with titles that exactly match existing entries.

## Development Considerations

- **Exception Handling**: Robustly manage exceptions to ensure application stability.
- **Architecture**: Contemplate the creation of additional classes and methods to maintain a clean and modular codebase.
- **Logging**: Integrate a logging framework to facilitate debugging and monitoring.
- **Testing**: Include at least one unit test to validate your application's functionality.
