# Contributing to SmartHome

Thank you for your interest in contributing to SmartHome! Your contributions—whether code, documentation, or ideas—are highly appreciated. This document outlines how you can help improve the project.

## How to Contribute

### Reporting Issues
- **Check for Existing Issues:**  
  Before reporting a new issue, please review the [Issues Directory](./Issues) to see if it has already been reported.
- **Create a New Issue:**  
  If you discover a bug or have a feature request, create a new issue in the appropriate subdirectory (either `prototype` or `deploy`). Follow the nearby issue template guidelines to provide a clear description of the problem or suggestion.

### Contributing Code
- **Select a Section:**  
  SmartHome is divided into different sections (e.g., Prototype and Deploy). Choose the section where you would like to contribute, make sure you prototype your changes in the `Prototype` section before moving to the `Deploy` section.
- **Create an Issue:**  
  If you are planning to work on a new feature or significant change, create an issue to discuss the proposed changes with the project maintainers.
- **Fork the Repository:**
    Click the "Fork" button on the project’s repository page to create your own copy
- **Follow the Guidelines:**
    Review the contribution guidelines in the relevant section's README file. Ensure your changes align with the project's goals and coding standards.
- **Submit a Pull Request:**
    Once your changes are ready, submit a pull request to the main repository. Provide a clear description of your changes and reference the related issue.

### Style Guidelines
- **Code Style:**  
  Follow the existing code style and structure. Use clear, descriptive variable and function names.
  We use snake case for variable names, function names, and file names.
  For Classes we use PascalCase.

  We also follow the PEP8 style guide for Python code. Please ensure your code is formatted correctly and includes appropriate comments and typing.

  For C/C++ code, we follow the Google C++ Style Guide. Please ensure your code is formatted correctly and includes appropriate comments and typing.
  
- **Documentation:**
    Include comments in your code to explain complex logic or algorithms. Update the relevant documentation files to reflect your changes.
- **Testing:**
    Write unit tests for new functionality or bug fixes. Ensure all tests pass before submitting a pull request.


### Making Changes
1. **Fork the Repository:**  
   Click the "Fork" button on the project’s repository page to create your own copy.
   
2. **Clone Your Fork:**  
   Clone the forked repository to your local machine:
   ```bash
   git clone https://github.com/your-username/SmartHome.git
    ```

3. **Create a New Branch:**
    Create a branch with a descriptive name for your changes:
    ```bash
    git checkout -b feature/descriptive-branch-name
    ```

4. **Make Your Changes:**
    Implement your improvements or bug fixes. Follow the existing code style and structure. This project is organized into different sections (e.g., Prototype and Deploy), so please ensure your changes are made in the proper context.

5. **Run Tests:**
    Ensure that any changes do not break existing functionality by running the unit tests. For the Python prototype, for example:
    ```bash
    pytest
    ```

6. **Commit And Push Your Changes:**
    Write clear, descriptive commit messages:
    ```bash
    git add .
    git commit -m "Description of your changes"
    git push origin feature/descriptive-branch-name
    ```

7. **Submit a Pull Request:**
    Go to the main repository page and click the "New Pull Request" button. Provide a detailed description of your changes and submit the pull request for review.

### Review Process
- **Code Review:**  
  Your pull request will be reviewed by project maintainers. They may suggest changes or improvements.
- **Testing:**
    Automated tests will be run to ensure your changes do not break existing functionality.
- **Merging:**
    Once your changes are approved, they will be merged into the main branch.

## Code of Conduct
We expect everyone to follow our Code of Conduct. Please be respectful, considerate, and helpful when interacting with others in the community.

## Additional Guidelines
- **Commit Quality:** Keep commits focused and avoid mixing unrelated changes.
- **Documentation:** Update the relevant documentation when you modify functionality.
- **Relevance:** Ensure your contribution aligns with the project's goals of modularity, efficiency, and expandability.

Thank you again for contributing to SmartHome!


