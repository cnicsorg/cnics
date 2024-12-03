# Contributing to Cnics

Thank you for your interest in contributing to Cnics! We welcome contributions from anyone interested in improving Cnics, whether it's fixing bugs, adding new features, improving the documentation, or helping with system-level tasks.

Please follow the guidelines below to help ensure your contributions are reviewed and merged efficiently.

## How to Contribute

There are several ways you can contribute to Cnics:
- Reporting Issues: If you encounter bugs, have questions, or have suggestions for improvements, open an issue.
- Code Contributions: If you want to help with fixing bugs, adding features, or improving performance, we welcome code contributions.
- Documentation: You can help improve our documentation by fixing typos, clarifying instructions, or adding new content to help others use Cnics effectively.
- System-Level Contributions: If you're familiar with low-level systems programming or the real-time computing requirements of Cnics, feel free to contribute improvements or optimizations to the core system.

## Reporting Issues

Before opening a new issue:
1. Search Existing Issues: Ensure that your issue hasn’t already been reported by searching the issues section.
2. Provide Details: If you are reporting a bug, please include:
   - The version of Cnics you're using.
   - A clear description of the problem.
   - Steps to reproduce the issue, if possible.
   - Any relevant logs or error messages.
3. Feature Requests: If you have an idea for a new feature or an improvement:
   - Describe the use case and why it's useful.
   - Suggest how it could be implemented or integrated into Cnics.

Once you've verified that your issue is not already reported, feel free to open a new issue with as much detail as possible.

## Making Changes

Here’s how you can contribute code to Cnics:

### Forking the Repository:
1. Fork the repository: Click the "Fork" button on the Cnics GitHub page to create a copy of the repository under your GitHub account.
2. Clone your fork: On your local machine, clone your fork:
   ```bash
   git clone https://github.com/your-username/cnics.git
   ```
### Creating a Branch:
1. Create a new branch: When working on changes, always create a new branch rather than working directly on the main branch. To create a new branch, run:
   ```bash
   git checkout -b my-feature-branch
   ```
   Choose a branch name that reflects the change you're making, e.g., fix-real-time-bug or add-new-math-library.
3. Make your changes: Work on your changes. Ensure that your code adheres to the project's coding conventions and guidelines.

### Submitting a Pull Request:
Once you have completed your changes:
1. Commit your changes: Commit your changes with a descriptive message. Example:
   ```bash
   git commit -m "Fix real-time task scheduling bug"
   ```
3. Push your branch: Push the branch to your fork:
   ```bash
   git push origin my-feature-branch
   ```
4. Open a pull request: Navigate to the Cnics GitHub repository and click on "New pull request." Make sure you’re comparing your feature branch with the main branch. Add a detailed description of your changes and any relevant information to help reviewers understand your contribution.

5. Wait for review: A maintainer will review your pull request. They may provide feedback or request changes. Once everything is in order, they will merge your changes.

## Code Style Guidelines

To maintain consistency across the Cnics codebase, please follow these guidelines:
1. Rust Formatting: We use Rustfmt to automatically format the Rust code. Please make sure your code is formatted using rustfmt before submitting.
   To install rustfmt, run:
   ```bash
   cargo install rustfmt
   ```
3. Code Comments: Please write clear and concise comments to explain your code, especially if the logic is complex or non-obvious. Every function or method should have a description of what it does and its expected inputs/outputs.

4. Commit Messages: Use clear and descriptive commit messages. Example:
   - Fix real-time task scheduling bug
   - Add optimization for numerical computation in shell
   The format should generally be:
      ```
     [type]: [short description]
   
     [detailed explanation if necessary]
      ```
   Types: Fix, Add, Update, Refactor, Docs.

5. Avoid Unnecessary Changes: When submitting a pull request, please avoid including formatting fixes or unrelated changes that aren’t part of the issue you’re addressing.

## Community Guidelines

We want Cnics to be a welcoming space for everyone, so please adhere to these guidelines when interacting with other community members:

1. Be respectful: Treat everyone with kindness and respect. Healthy communities are built on respect for others, so always communicate in a positive, constructive manner.

2. Be patient: Review processes may take time, so please be patient and open to feedback from other contributors.

3. Collaborate: Whether it's discussing new features or fixing bugs, collaboration is key. If you're unsure about how something should be implemented, feel free to ask for input from other contributors.

## License

By contributing to Cnics, you agree that your contributions will be licensed under [GPLv3](https://github.com/cnicsorg/cnics/blob/main/LICENSE).

Thank you for contributing to Cnics! We’re excited to see how your contributions help improve the system.
