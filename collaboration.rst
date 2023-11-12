.. Collaboration Guidelines

========================
Collaboration Guidelines
========================

Welcome to the collaborative development process at GoDjango LLC. This document outlines the guidelines and best practices to ensure smooth and effective collaboration on our GitHub repositories.

Version Control
---------------

1. **Branching Strategy:**
   - Use feature branches for developing new features or fixing bugs.
   - Naming convention: `feature/your-feature-name`, `bugfix/issue-number`, etc.

2. **Pull Requests:**
   - Create a pull request for each feature or bug fix.
   - Provide a clear and concise title and description.
   - Reference relevant issues in the description.
   - Reviewers should be assigned for every pull request.

3. **Code Reviews:**
   - All changes must go through a code review process.
   - Address and resolve review comments before merging.
   - Use inline comments for specific feedback.

Coding Standards
----------------

4. **Coding Style(Per language):**
   - Python: Follow the coding style and conventions defined in [style guide](https://www.python.org/doc/essays/styleguide/).                           
   - JS, JSX, or TS: Follow the coding style and conventions defined in [eslint style guide](https://eslint.style/).
   - C: Follow the coding style and conventions defined in [GNU Style guide](https://www.gnu.org/prep/standards/html_node/Writing-C.html).                          
   - Others included in Google standards: Follow the coding style and conventions defined in [google style guide](https://google.github.io/styleguide/)(The above style guides overwrite these ones, i.e.: python).

5. **Commit Messages:**
   - Write clear and descriptive commit messages.
   - Use present tense ("Add feature" not "Added feature").
   - Reference relevant issues in commit messages.

6. **Documentation:**
   - Keep code and project documentation up-to-date.
   - Use docstrings and comments where necessary.

Issue Tracking
--------------

7. **Creating Issues:**
   - Use GitHub issues to report bugs, request features, or discuss improvements.
   - Provide a clear and concise title and description.
   - Use labels to categorize issues.

8. **Closing Issues:**
   - Reference the closing keyword in commit messages to close related issues automatically (e.g., "Closes #123").

Collaboration Etiquette
-----------------------

9. **Communication:**
   - Use GitHub discussions for non-code discussions.
   - Be respectful and constructive in comments and discussions.

10. **Merging:**
    - Avoid force pushes to branches that others are working on.
    - Ensure that the build is passing before merging.

11. **Continuous Integration:**
    - Set up and configure CI/CD pipelines for each repository.
    - Ensure that all tests pass before merging.

Security
--------

12. **Security Vulnerabilities:**
    - Report security vulnerabilities privately through [contact@godjango.dev](mailto:contact@godjango.dev).
    - Do not disclose security-related information in public discussions.

We aim to maintain a clean, organized, and collaborative development environment by following these guidelines. If you have any questions or suggestions for improvement, feel free to open a discussion or contact godjangollc.

Thank you for your contribution!

