# Issues Directory Overview

The Issues directory is designed to help manage and track problems and tasks during the development of SmartHome. It is organized into two main subdirectories:

- **prototype:** Contains markdown files and folders that document issues related to the prototyping phase (primarily Python-based development).
- **deploy:** Contains markdown files and folders that document issues related to the production deployment (C/C++ control system).

Within each of these directories, you'll find additional subdirectories:
- **completed:** This folder holds resolved issues for easy reference and historical tracking.

## Creating an Issue

To create a new issue, follow these steps:

1. Navigate to the appropriate directory (**prototype** or **deploy**) based on the current focus of your work.
2. If you feel this issue is part of a larger issue include it in the appropriate folder.
4. Create a new markdown file with a descriptive name (e.g., `issue_memory_leak.md`).
3. Inside the file, include the following sections:
   - **Title:** A brief title of the issue.
   - **Description:** A detailed explanation of the issue.
   - **Steps to Reproduce:** How to reproduce the issue, if applicable.
   - **Expected Behavior:** What you expected to happen.
   - **Actual Behavior:** What is actually happening.
   - **Proposed Solution:** (Optional) Ideas for resolving the issue.
   - **Additional Information:** Any other relevant details.
   - **Resolution:** (Optional) Once the issue is resolved, document the resolution here.
4. Once an issue is resolved, move the file (or its contents) to the `completed` folder within the respective directory.
5. Update any relevent documentation to reflect the resolution.
6. In the issue file describe the resolution and any changes made to the codebase.

This structure will help maintain clear documentation, making it easier to track progress and revisit past issues as needed.