# CONTRIBUTING TO DEV OPS CLOUD FREE TIER SERVICES CATALOG

Welcome! We're thrilled you're interested in contributing to the **DevOpsCloud-FreeTier-Services-Catalog-Global-Awesome-List**. This project thrives on community collaboration to maintain an indispensable, up-to-date catalog of global free-tier SaaS, PaaS, and IaaS offerings, along with essential DevOps and Cloud tools.

Our mission is to empower DevOps engineers, Site Reliability Engineers, and Cloud Architects with the knowledge to optimize infrastructure, enhance workflows, and achieve unparalleled cost-efficiency. Your contributions are vital to our success.

## 1. CODE OF CONDUCT

This project adheres to the Contributor Covenant Code of Conduct, Version 2.1. Please read the full [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) to understand the expected standards of behavior.

## 2. GETTING STARTED

### 2.1. Project Overview

This repository is a curated list of free-tier cloud services and DevOps tools. The primary content resides in a structured HTML file (or Markdown, depending on the current implementation). We prioritize accuracy, comprehensiveness, and ease of use.

### 2.2. Development Environment Setup

As this project is primarily content-driven (HTML/Markdown), the setup is minimal. However, to ensure consistency and validate changes, we recommend the following:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/DevOpsCloud-FreeTier-Services-Catalog-Global-Awesome-List.git
    cd DevOpsCloud-FreeTier-Services-Catalog-Global-Awesome-List
    ```

2.  **Install Dependencies (if applicable for validation tools):**
    *   For linting and formatting checks, ensure you have Node.js and npm/yarn/pnpm installed.
    *   Install project dependencies:
        ```bash
        # Using npm
                npm install
        # Or using yarn
                yarn install
        # Or using pnpm
                pnpm install
        ```

3.  **Linting and Formatting:**
    *   We use Biome for lightning-fast linting and formatting.
    *   Run checks:
        ```bash
        npm run lint
        # or
        yarn lint
        # or
        pnpm lint
        ```
    *   Apply fixes automatically:
        ```bash
        npm run format
        # or
        yarn format
        # or
        pnpm format
        ```

### 2.3. Running Tests (if applicable)

*   While the core is content, any associated scripts or validation tools will have tests.
*   Execute tests:
    ```bash
    npm run test
    # or
    yarn test
    # or
    pnpm test
    ```

## 3. CONTRIBUTION WORKFLOW

We follow a standard GitHub pull request workflow:

1.  **Fork the Repository:** Create your own fork of the `DevOpsCloud-FreeTier-Services-Catalog-Global-Awesome-List` repository.
2.  **Clone Your Fork:** Clone your forked repository to your local machine.
    ```bash
    git clone https://github.com/your-username/DevOpsCloud-FreeTier-Services-Catalog-Global-Awesome-List.git
    cd DevOpsCloud-FreeTier-Services-Catalog-Global-Awesome-List
    ```
3.  **Create a New Branch:** Create a descriptive branch for your changes (e.g., `feat/add-new-service`, `fix/update-pricing-info`).
    ```bash
    git checkout -b feat/add-new-service
    ```
4.  **Make Your Changes:** Add new services, update existing entries, or improve documentation. Ensure your changes adhere to the project's standards (see Section 4).
5.  **Test Your Changes:** Run linters and tests to ensure your changes haven't introduced regressions.
    ```bash
    npm run lint && npm run test
    ```
6.  **Commit Your Changes:** Commit your changes using the Conventional Commits specification.
    ```bash
    git add .
    git commit -m "feat: Add <Service Name> with free tier details"
    ```
7.  **Push to Your Fork:** Push your branch to your fork on GitHub.
    ```bash
    git push origin feat/add-new-service
    ```
8.  **Open a Pull Request:** Go to the original repository and open a new pull request from your branch to the `main` branch.

## 4. CONTRIBUTION GUIDELINES

### 4.1. Content Standards

*   **Accuracy:** Ensure all information, especially pricing and tier details, is accurate and up-to-date. If possible, link directly to the official free tier documentation.
*   **Clarity:** Descriptions should be concise and informative, clearly stating the service's purpose and its free tier limitations.
*   **Relevance:** Focus on services and tools directly related to DevOps, Cloud Computing, SaaS, PaaS, and IaaS.
*   **Structure:** Follow the existing format for adding new entries. Consistency is key.
*   **No Promotional Content:** Avoid marketing jargon or overly promotional language.

### 4.2. Technical Standards

*   **Linting & Formatting:** All code (if applicable) and structured data files must pass Biome checks.
*   **Testing:** Ensure any new scripts or significant changes are accompanied by relevant tests.
*   **Conventional Commits:** Use the format `type: subject` (e.g., `feat: Add new AWS service`, `fix: Correct Azure free tier details`, `docs: Update CONTRIBUTING.md`).
*   **Semantic Versioning:** While this is primarily a content repository, any versioned artifacts or scripts will follow SemVer.

### 4.3. Adding New Services/Tools

*   **Search First:** Before adding, search the existing list to ensure the service isn't already cataloged.
*   **Best Placement:** Add new entries in the most logical section. If unsure, create a new subsection or add to a general `Miscellaneous` or `New Additions` section, and we can refine placement later.
*   **Minimal Information:** At a minimum, include:
    *   Service Name
    *   Link to Service
    *   Brief Description
    *   Key aspects of the Free Tier
    *   Relevant Tags (e.g., `SaaS`, `PaaS`, `DevOps`, `Monitoring`, `CI/CD`, `Database`)

### 4.4. Updating Existing Entries

*   If you find outdated information (e.g., pricing changes, feature deprecations), please open an issue or a pull request to correct it.
*   Specify the exact change required and provide a source link if possible.

## 5. REPORTING ISSUES

If you discover inaccurate information, broken links, or have suggestions for improvement, please open an **Issue** on GitHub.

*   **Use Clear Titles:** Be specific (e.g., "Outdated Free Tier Info for Service X", "Broken Link for Tool Y").
*   **Provide Details:** Include the service/tool name, the incorrect information, the correct information, and any relevant links.
*   **Suggestion:** Use the `enhancement` or `question` issue template.

## 6. PULL REQUEST REVIEW PROCESS

*   All pull requests will be reviewed by at least one maintainer.
*   We aim to provide feedback within 2-3 business days.
*   Be prepared to make changes based on feedback. This is a collaborative process.
*   Ensure your PR is rebased onto the latest `main` branch before merging if significant changes occur during the review period.

## 7. QUESTIONS?

If you have any questions not covered here, feel free to open an issue tagged `question` or reach out to the project maintainers.

Thank you for contributing!