# 🚀 Contributing to CloudCostControl-FreeTier-Cloud-Services-Awesome-List

We welcome your contributions to `CloudCostControl-FreeTier-Cloud-Services-Awesome-List`! As a community-driven resource for optimizing cloud costs, your input is invaluable. This repository adheres to the stringent standards set by the **Apex Technical Authority**, ensuring a high-velocity, zero-defect, and future-proof project.

## 1. Our Guiding Principles

*   **Apex Technical Authority Standards:** All contributions must align with the rigorous requirements outlined by the Apex Technical Authority, emphasizing professional archival and elite architecture. (See `.github/AGENTS.md` for detailed directives).
*   **Zero-Defect:** Strive for impeccable code and documentation. Thorough testing and validation are paramount.
*   **High-Velocity:** Optimize workflows for rapid iteration and deployment.
*   **Future-Proof:** Design with scalability, maintainability, and evolving cloud landscapes in mind.
*   **Community-Driven:** This is a collaborative effort. Respect diverse perspectives and foster an inclusive environment.

## 2. Getting Started

### 2.1. Prerequisites

*   **Git:** Ensure you have Git installed and configured.
*   **Node.js & npm/yarn/pnpm:** For front-end development and build tools (if applicable).
*   **Python 3.10+:** Essential for the core functionality of this project. Ensure `uv` is installed for package management.
*   **Ruff:** For linting and formatting.
*   **Browser:** Latest versions of Chrome, Firefox, Safari.

### 2.2. Cloning the Repository

bash
git clone https://github.com/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List.git
cd CloudCostControl-FreeTier-Cloud-Services-Awesome-List


### 2.3. Development Environment Setup

While this project primarily curates an 'Awesome List' and may not have a complex backend, any development or updates should follow these guidelines:

1.  **Install Python Dependencies:**
    bash
    uv pip install -r requirements.txt
    
    *Note: If specific development or testing dependencies are needed, they will be listed in `dev-requirements.txt` or similar.* 

2.  **Install Project Hooks (Optional but Recommended):**
    bash
    pip install pre-commit
    pre-commit install
    
    This will run linters and formatters automatically before each commit.

## 3. Contribution Workflow

We follow the standard GitHub Pull Request workflow:

1.  **Fork the Repository:** Create your own fork of the `CloudCostControl-FreeTier-Cloud-Services-Awesome-List` repository.
2.  **Create a New Branch:** Branch out from the `main` branch for your specific feature or fix.
    bash
    git checkout -b feature/your-feature-name
    
3.  **Make Your Changes:** Implement your contribution. Ensure it adheres to the project's standards and principles.
    *   **For List Additions/Updates:** Follow the established format in the main list file (e.g., `README.md`). Verify any new services align with the 'free-tier' and 'cost-optimization' ethos.
    *   **For Code Changes:** Ensure all code is well-documented, adheres to PEP 8 (as enforced by Ruff), and includes comprehensive tests.
4.  **Test Your Changes:** Run the test suite.
    bash
    pytest
    
    Ensure all tests pass and coverage remains high.
5.  **Lint and Format:** Ensure your code is clean and formatted.
    bash
    ruff check .
    ruff format .
    
6.  **Commit Your Changes:** Commit with clear, concise messages.
    bash
    git add .
    git commit -m "feat: Add new category for AI-powered cost analysis tools"
    
7.  **Push to Your Fork:** Push your branch to your forked repository.
    bash
    git push origin feature/your-feature-name
    
8.  **Open a Pull Request:** Create a Pull Request against the `main` branch of the original `chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List` repository.
    *   Clearly describe your changes and the problem they solve.
    *   Reference any relevant issues.

## 4. Code of Conduct

This project is governed by the Contributor Covenant, version 4.0. Please read the full text in the [CODE_OF_CONDUCT.md](https://github.com/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List/blob/main/CODE_OF_CONDUCT.md) file to understand what actions, in general, are expected and forbidden in our community. Harassment and other unacceptable behavior are not tolerated.

## 5. Reporting Issues and Suggesting Features

*   **Issues:** Please use the GitHub Issues tracker to report bugs or problems. Provide detailed steps to reproduce the issue and relevant environment information.
*   **Feature Requests:** Suggest new features or improvements via GitHub Issues. Be specific about the desired functionality and its benefits.

## 6. License

By contributing to `CloudCostControl-FreeTier-Cloud-Services-Awesome-List`, you agree that your contributions will be licensed under the **CC BY-NC 4.0 License**. See the [LICENSE](https://github.com/chirag127/CloudCostControl-FreeTier-Cloud-Services-Awesome-List/blob/main/LICENSE) file for details.

--- EOD ---