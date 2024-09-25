# **Contributing to REGARDS**

Thank you for your interest in contributing to REGARDS! We welcome contributions from developers, data scientists, and enthusiasts of all skill levels. This document provides guidelines on how you can participate and make valuable contributions to the project.

## **Table of Contents**

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Improving Documentation](#improving-documentation)
  - [Submitting Pull Requests](#submitting-pull-requests)
- [Development Setup](#development-setup)
- [Style Guide](#style-guide)
- [Community and Support](#community-and-support)

## **Code of Conduct**

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). We are committed to fostering a welcoming and respectful environment, and we expect all contributors to help us maintain that standard.

## **How Can I Contribute?**

### **Reporting Bugs**

Found a bug? Let us know!

1. **Search Existing Issues**: Before opening a new issue, please check if the bug has already been reported.
2. **Create a New Issue**:
   - Go to the [Issues](https://github.com/yourusername/REGARDS/issues) page.
   - Click **New Issue** and select the **Bug Report** template.
   - Provide as much detail as possible, including steps to reproduce, expected results, and screenshots if applicable.

### **Suggesting Features**

Have an idea for a new feature? We’d love to hear it!

1. **Search Existing Feature Requests**: Check the current feature requests to avoid duplicates.
2. **Create a New Feature Request**:
   - Go to the [Issues](https://github.com/yourusername/REGARDS/issues) page.
   - Click **New Issue** and select the **Feature Request** template.
   - Describe your idea, its benefits, and any implementation suggestions.

### **Improving Documentation**

Good documentation is critical to the success of REGARDS. You can help improve our documentation by:

1. **Fixing Typos and Clarifying Instructions**: Submit pull requests to correct errors in existing documentation.
2. **Adding New Content**: Create guides, tutorials, or enhance existing sections to make the project more accessible.
3. **Suggest Documentation Enhancements**:
   - Open an issue to discuss changes or additions before making significant updates.

### **Submitting Pull Requests**

Pull requests are the primary way to contribute code changes to REGARDS.

1. **Fork the Repository**: Click the **Fork** button on the top right of the repository page.
2. **Create a Branch**:
   - Create a branch for your changes:  
     ```bash
     git checkout -b feature/your-feature-name
     ```
3. **Make Your Changes**:
   - Keep changes focused on a single feature or fix.
   - Ensure code is clean and follows the project’s style guide.
4. **Test Your Changes**: If applicable, run existing tests and add new tests to cover your changes.
5. **Commit Your Changes**: Write clear and descriptive commit messages.
6. **Push to Your Fork**:
   - Push your changes to your forked repository:  
     ```bash
     git push origin feature/your-feature-name
     ```
7. **Open a Pull Request**:
   - Go to the [Pull Requests](https://github.com/brosiah96/REGARDS/pulls) page on the main repository.
   - Click **New Pull Request** and follow the prompts to open your request.
   - Clearly describe your changes and link to any related issues.

8. **Review and Feedback**:
   - Your pull request will be reviewed, and feedback may be provided. Be prepared to make adjustments as needed.

## **Development Setup**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/REGARDS.git
   cd REGARDS
   ```
2. **Install Dependencies**:
   - Ensure you have Python installed, then install required packages:
     ```bash
     pip install -r requirements.txt
     ```
3. **Run the Application**:
   - Start the application using:
     ```bash
     streamlit run src/dashboards/main.py
     ```
4. **Run Tests**:
   - Use the test suite to ensure your changes do not break existing functionality:
     ```bash
     pytest
     ```

## **Style Guide**

- **Code Formatting**: Follow PEP 8 standards. Use tools like `black` and `flake8` to format and lint your code.
- **Naming Conventions**: Use descriptive names for variables, functions, and classes.
- **Comments**: Write clear comments to explain complex logic.
- **Documentation**: Update documentation files (`README.md`, `docs/`) when your changes impact usage or setup.

## **Community and Support**

- **GitHub Discussions**: Participate in discussions about project direction, new features, and community support.

---

Thank you for contributing to REGARDS! Your efforts help make this project better for everyone. We look forward to collaborating with you.

---
