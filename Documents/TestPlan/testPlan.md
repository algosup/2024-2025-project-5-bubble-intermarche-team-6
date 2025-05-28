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
  - [IV. Testing Procedures](#iv-testing-procedures)
    - [A. Test Execution](#a-test-execution)
      - [1. Test Cases](#1-test-cases)
      - [2. Order of Testing](#2-order-of-testing)
  - [B. Pass / Fail Criteria](#b-pass--fail-criteria)

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
- The application is suggesting paired dishes, wines or cheeses relative to the user input.

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
- Bubble.io

---

## III. GitHub Issues & Pull Request

### A. GitHub Issues

GitHub Issues are used to track, manage, and resolve defects or enhancements. The following process will be followed when opening an issue:

**Issue Creation**:
- Provide a detailed description of the problem, including steps to reproduce it if applicable.
- Assign the issue to the relevant team members and add appropriate labels (e.g., bug, enhancement, documentation).

**Issue Triage**:
- The QA or technical lead will review issues and prioritize them based on severity and impact.
- High-priority issues should be addressed before moving on to new feature development.

**Issue Resolution**:
- Developers must provide comments and updates on the issue’s progress.
- Once fixed, the issue should be linked to the corresponding pull request.

**Issue Closure**:
- After verification and testing, the issue is marked as resolved and closed by the QA.
- If the issue persists, it should be reopened and assigned for further investigation.

Moreover, Issues **related to deliverables** have been created.

They act as **milestones**: once we finish a document for instance, and it has been reviewed / merged, we can close the issue related to that specific document.

<img width="750" alt="Screenshot 2025-05-12 at 10 00 45" src="https://github.com/user-attachments/assets/deff691c-591e-4130-afc6-fe491f96bf02" />

Template of **document issue**:

<img width="750" alt="Screenshot 2025-05-12 at 10 02 09" src="https://github.com/user-attachments/assets/370598ae-eeb0-466b-bd77-d14140715fba" />

Template of **bug issue**:

<img width="750" alt="Screenshot 2025-05-12 at 10 01 44" src="https://github.com/user-attachments/assets/2e788591-68b9-44d7-b0c6-85b36e704d17" />

### B. Pull Request

Pull requests are used to propose, review, and merge changes into the main branch. The following process must be followed when submitting a PR:

**Pull Request Creation**:
- PRs must include a clear description summarizing the changes.
- Link any relevant issues that the PR addresses.

**Review Process**:
- At least one reviewer (QA or technical lead) must approve the PR before merging.
- Reviewers should check for correctness, readability, and the absence of regressions.
- Any requested changes must be addressed before approval.

**Merging**:
- Once approved, the developer or the reviewer can merge the PR.
- Squash and merge should be preferred for small changes; standard merge for larger features.
- Delete the feature branch after merging to keep the repository clean.

**Post-Merge Actions**:
- Ensure the latest changes are pulled into local environments.
- Monitor production (if applicable) for unexpected issues after deployment.

The adherence to coding standards is not mentioned here as developers will work on Bubble. No code will be written and commited on the repository then.

Template of **PR**:

<img width="750" alt="Screenshot 2025-05-12 at 10 03 54" src="https://github.com/user-attachments/assets/84c08500-38b6-4d4f-8bce-fa7d0a76dd5b" />

## IV. Testing Procedures

### A. Test Execution

#### 1. Test Cases

For each requirement, system feature, or suggestion to be tested, the tester will execute a set of pre-defined test cases.
Each test case will have a series of actions and expected results.
As each action is performed, the results are evaluated.
If the observed results are equal to the expected results, a checkmark ✅ is placed in the “Pass/Fail” column.
If the observed results differ from the expected results, a checkmark ❌ is placed in the “Pass/Fail” column.

#### 2. Order of Testing

The order of testing will be driven primarily by the test order. Within each test, the following order of testing will be followed:

- **Test 1**: Navigation & Language
  - A. Ensure that the application can be navigated through.
  - B. Verify that there is no spelling errors.

- **Test 2**: Input
  - A. Ensure users can input dishes, wines and cheeses in desired fields.
  - B. Validate inputs can be processed by the application.

- **Test 3**: Process Suggestions
  - A. Verify processing of inputs through the system.
  - B. Confirm the correctness of suggestions and computation logic.

- **Test 4**: Output Validation
  - A. Ensure final outputs conform to expected outputs (e.g wine if users search for wines).
  - B. Compare actual results with predefined expected values.

## B. Pass / Fail Criteria

To pass the system integration test, the Bubble Intermarché application must satisfy the following criteria across all relevant domains:

**1. Core Functionality**:

✅ Product Location and Navigation

The system accurately locates products within the store at the aisle level for at least 95% of known product inputs (based on a controlled test dataset of about 300 products).

Navigating from one product to another should complete within 3 steps max (user clicks/pages).

✅ Natural Language Understanding

The system must correctly interpret and respond to at least 90% of input phrases related to product queries (e.g., "goat cheese", "red wine", "bio milk").

The application must return relevant and categorized suggestions in both English and French, with accurate translation and intent recognition.

✅ Product Suggestions

When given a valid input (e.g., "cheese" or "white wine"), the application suggests:

- At least 3 related items, categorized properly.
- At least one complementary suggestion, such as a wine paired with cheese.

**2. Data Integrity**:

✅ Dataset Consistency

The internal product database must:

- Contain no duplicate categories.
- Maintain category consistency (e.g., no wine in the Cheese category).
- Be validated via automated checks before each deployment.

✅ Language Data

The multilingual dataset must ensure:

- Consistent labeling of the same item in English and French.
- No empty fields or mismatched translations.

**3. Performance**:

✅ Application & Requests Response Time

All user queries must return product results within 700 milliseconds on all environments.
Maximum accepted latency is 1 second under normal operating conditions or with a poor Internet connexion for the web version.

**4. Ease of Use**:

✅ Usability and UI

The application should pass usability testing with at least 80% positive feedback from the testing team regarding:

- Clarity of instructions.
- Input acceptance.
- Quality of product matches.

✅ Error Handling

Unrecognized input must yield a friendly and helpful error message, including an example of valid queries.
Incomplete or empty input fields must be highlighted and explained clearly.

**5. Security and Reliability**:

✅ Access Control

The application must not allow access to admin/debug functions from the user interface or via query manipulation.

✅ Crash Handling

No crash or unresponsive state should occur after 1 hour of continuous use or under malformed user inputs.

✅ Recovery

After a page reload or session refresh, the application must preserve the user's last valid query or suggestion.

**6. Integration and Extensibility**:

✅ API Compatibility

Any external tool or interface calling the assistant’s functionality (e.g., for mobile or web version) must:

- Receive results in standard JSON format.
- Get responses with accurate schema and product metadata, explained in the [Technical Specifications](./../Technical/technicalSpecifications.md).

✅ Extensibility Test

Adding a new product category (e.g., "Snacks") must be achievable within 15 minutes without codebase overhaul.

**7. Testing Success Criteria**:

✅ Test Case Completion

All test cases for UI, product matching, multilingual support, and suggestion logic must pass at least 90% of test cases.

✅ Validation Tools

Static validation tools must show no critical errors in the product and language datasets.

✅ Edge Cases

Assistant must handle at least 80% of predefined edge cases (e.g., spelling mistakes, plural/singular confusion, mixed languages) correctly.
