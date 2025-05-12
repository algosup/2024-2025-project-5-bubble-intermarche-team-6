# Test Plan - Bubble Intermarché

## Table Of Content

</summary>

- [Test Plan - Bubble Intermarché](#test-plan---bubble-intermarché)
  - [Table Of Content](#table-of-content)
  - [I. Introduction](#i-introduction)
    - [A. Product Overview](#a-product-overview)
    - [B. Test Objectives](#b-test-objectives)
  - [II. Plan](#ii-plan)
    - [A. Test Team](#a-test-team)
    - [B. Testing Environment \& Tools](#b-testing-environment--tools)
  - [III. GitHub Issues \& Pull Request](#iii-github-issues--pull-request)
    - [A. GitHub Issues](#a-github-issues)
    - [B. Pull Request](#b-pull-request)

</details>

## I. Introduction

### A. Product Overview

**Bubble Intermarché** is a simple and smart product assistant that helps customers in Intermarché stores:

- Find products easily by **addressing and locating them inside the store** (aisle-level geolocation).
- Get **precise product suggestions** based on natural input like `"red wine"` or `"goat's cheese"`.
- Browse organized **product categories** (e.g., Alcohol, Cheeses, Bio products).
- Support **both English and French** for broader accessibility.

⚠️ This is a **prototype (Proof of Concept)** – strict adherence to Intermarché's official brand identity is not required.

### B. Test Objectives

To create an efficient and reliable product, we need to have **objectives** when it comes to testing the product.

We need to ensure:

- The application is free of bugs that would harm the user experience (including navigation, language, etc).
- The application is easy to use and navigate.
- The application is accepting inputs from the user, such as cheeses, wines and dishes.
- The application is suggesting paired dishes, wines or cheeses depending on the user input.

## II. Plan

### A. Test Team

The following people will be on the system integration test team:

| Role | Name | Responsibilities |
|------|------|------------------|
| Technical Leader     | Habi CAILLEAU | Helps the QA to review the app and validate parts to go into production. Helps to create test cases. |
| Project Manager      | Alexandre BOPP   | Reviews all documents when a Pull Request is submitted from the `documents` branch with the Quality Assurance. Helps to create test cases. |
| Quality Assurance    | Enzo GUILLOUCHE    | Reviews the app and documents, creates and performs test cases, makes template for Pull Requests and Issues, makes Issues if necessary and validates Pull Requests. |

### B. Testing Environment & Tools

Our team members have **different Operating Systems**, which are *Windows* and *MacOs*.
The project will be developed and the tests will be run on the following environments:

(1) **Apple MacBook Air M3 2024**

- Apple M3
- 16 GB
- macOS Sequoia 15.1.1

(2) **Lenovo ThinkBook 14**

- Intel Core i7-1065G7
- 16 GB
- Windows 11 Pro 21H2

And here are the **tools** used for the development and tests:

- Visual Studio Code
- Bubble

---

## III. GitHub Issues & Pull Request

### A. GitHub Issues

GitHub Issues are used to track, manage, and resolve defects or enhancements. The following process will be followed when opening an issue:

1. **Issue Creation**:
   - Each issue must have a clear and descriptive title.
   - Provide a detailed description of the problem, including steps to reproduce it if applicable.
   - Assign the issue to the relevant team members and add appropriate labels (e.g., bug, enhancement, documentation).

2. **Issue Triage**:
   - The QA or technical lead will review issues and prioritize them based on severity and impact.
   - High-priority issues should be addressed before moving on to new feature development.

3. **Issue Resolution**:
   - Developers must provide comments and updates on the issue’s progress.
   - Once fixed, the issue should be linked to the corresponding pull request.

4. **Issue Closure**:
   - After verification and testing, the issue is marked as resolved and closed by the QA.
   - If the issue persists, it should be reopened and assigned for further investigation.

Template of **document issue**:



Template of **code issue**:



### B. Pull Request

Pull requests are used to propose, review, and merge changes into the main branch. The following process must be followed when submitting a PR:

1. **Pull Request Creation**:
   - PRs must include a clear title and description summarizing the changes.
   - Link any relevant issues that the PR addresses.

2. **Review Process**:
   - At least one reviewer (QA or technical lead) must approve the PR before merging.
   - Reviewers should check for correctness, readability, and the absence of regressions.
   - Any requested changes must be addressed before approval.

3. **Merging**:
   - Once approved, the developer or the reviewer can merge the PR.
   - Squash and merge should be preferred for small changes; standard merge for larger features.
   - Delete the feature branch after merging to keep the repository clean.

4. **Post-Merge Actions**:
   - Ensure the latest changes are pulled into local environments.
   - Monitor production (if applicable) for unexpected issues after deployment.

The adherence to coding standards is not mentioned here as developers will work on Bubble. No code will be written and commited on the repository then.

Template of **PR**:



