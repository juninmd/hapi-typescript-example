# AGENTS.md File Guidelines

These guidelines are designed to ensure the creation and maintenance of high-quality, robust, and maintainable AI coding agents within the AGENTS repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   Every function, class, or component must have a single, well-defined purpose.
*   Avoid duplicating code across multiple files.
*   Leverage shared components and reusable logic whenever possible.
*   Refactor existing code to eliminate redundancy.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize clarity and readability over unnecessary complexity.
*   Keep code concise and focused.
*   Minimize cognitive load for the developers.
*   Avoid overly clever or obscure solutions.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses must be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to depend on methods they don't use.
*   **Dependency Inversion Principle:** Interfaces should be preferred over concrete implementations.

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only what is currently required for the current task.
*   Avoid premature optimization.
*   Focus on solving the immediate problem; future requirements can be addressed later.

## 5. Code Structure & Organization

*   **File Size Limit:** Each file should not exceed 180 lines of code.
*   **Modular Design:** Break down large files into smaller, logical modules.
*   **Consistent Naming Conventions:** Employ clear and descriptive naming conventions for all files, functions, and variables.
*   **Comments:** Provide concise and relevant comments to explain complex logic or non-obvious decisions. Comments should not add new functionality.
*   **Docstrings:** Write detailed docstrings for each function and class explaining their purpose, arguments, and return values.  Follow a consistent docstring format.

## 6. Testing Strategy

*   **Unit Tests Only:** All development must be driven by unit tests.
*   **Test Coverage Target:** Achieve a minimum of 80% test coverage.  This will be tracked through automated testing tools.
*   **Test Case Design:**  Each test case should focus on a single, well-defined scenario.
*   **Test Framework:** Use a standard testing framework (e.g., pytest, unittest) appropriate for the chosen language.
*   **Test Data Management:** Generate and manage test data effectively.  Avoid reliance on external data sources.
*   **Isolation Testing:** Tests should be isolated to prevent unintended side effects.

## 7. Coding Standards

*   **Indentation:** Consistent use of 2 spaces for indentation.
*   **Line Length:** Maximum line length of 120 characters.
*   **Whitespace:**  Proper use of whitespace to improve readability.
*   **Error Handling:** Implement robust error handling to prevent crashes and provide informative error messages.

## 8.  Specific Requirements (Example - adjust as needed)

*   **API Design:**  Document all APIs clearly using Swagger/OpenAPI.
*   **Data Structures:** Utilize appropriate data structures for efficiency.
*   **Error Handling:**  Implement consistent error handling and logging.
*   **Logging:**  Use a logging framework to track program behavior and errors.

## 9.  Maintainability & Documentation

*   Document all significant design choices and rationale.
*   Use descriptive variable and function names.
*   Provide a comprehensive index of files and functions.
*   Utilize static analysis tools (e.g., pylint, flake8) to identify potential issues.

## 10.  Dependencies

*   Clearly define and manage all dependencies.
*   Use a dependency management system (e.g., pip, Maven, npm).
*   Ensure dependencies are well-documented and easily reproducible.

These guidelines are intended to provide a framework for the development of AGENTS.md, a functional and maintainable project. Any deviation from these principles will be considered a violation of the project’s intended purpose.  Regular review and updates to these guidelines will be performed as needed.