# Test Cases - Bubble Intermarché

## Table Of Content

</summary>

- [Test Cases - Bubble Intermarché](#test-cases---bubble-intermarché)
  - [Table Of Content](#table-of-content)
  - [I. Introduction](#i-introduction)
  - [II. Prototype version](#ii-prototype-version)
  - [III. MVP version](#iii-mvp-version)
  - [IV. Future Test Cases: Version 1](#iv-future-test-cases-version-1)

</details>

## I. Introduction

Each test case ID relates to a category, which also relates to a product version:

| Category ID | Category Name |
|------------|----------------|
| 1 | Prototype version |
| 2 | MVP version |
| 3 | Version 1 |

Priorities in the test cases can vary: Low, Moderate, High.
The 'High' test cases must be validated first.

## II. Prototype version

| Test Case ID | Test Case Name            | Test Case Description                                                | Expected Result                                                 | Actual Result | Tested | Priority | Pass/Fail |
| ------------ | ------------------------- | -------------------------------------------------------------------- | --------------------------------------------------------------- | ------------- | ------ | -------- | --------- |
| **1.01** | Program launch | The user launches the program. | No error, the app launches successfully. | / | / | High | / |
| **1.02** | User input detection | The user inputs in the research field. | No error, the app detects keyboard inputs. | / | / | High | / |
| **1.03** | User input meal | The user inputs a meal in the research field. | No error, the app detects a meal input and redirect the user to the appropriate page. | / | / | High | / |
| **1.04** | User input Wine | The user inputs a wine in the research field. | No error, the app detects a wine input and redirect the user to the appropriate page. | / | / | High | / |
| **1.05** | User input Cheese | The user inputs a cheese in the research field. | No error, the app detects a cheese input and redirect the user to the appropriate page. | / | / | High | / |
| **1.06** | Cheese to Wine recommendation | Based on their cheese input, the user gets wine recommandation from the program. | The app recommends appropriate wines to the user. | / | / | High | / |
| **1.07** | Dish to Cheese recommendation | Based on their dish input, the user gets cheese recommandation from the program. | The app recommends appropriate cheeses to the user. | / | / | High | / |
| **1.08** | Wine to Cheese recommendation | Based on their wine input, the user gets cheese recommandation from the program. | The app recommends appropriate cheeses to the user. | / | / | High | / |
| **1.09** | User cheese diet | The program recommends cheeses taking in account the user's dietary preferences/restrictions. | The app recommends appropriate cheeses to the user (Lactose intolerant -> recommends only lactose-free cheeses). | / | / | Moderate | / |
| **1.10** | User wine diet | The program recommends wines taking in account the user's dietary preferences/restrictions. | The app recommends appropriate wines to the user (Does not drink alcohol -> recommends only alcohol-free wines or fruit juices). | / | / | Moderate | / |
| **1.11** | User set favorites | The user sets favorite cheeses and wines. | The app stocks favorite cheeses and wines, and the user can find them in the dedicated tab. | / | / | Low | / |
| **1.12** | User remove favorites | The user removes favorite cheeses and wines. | The app removes cheeses and wines from favorites, and the user cannot find them anymore in the dedicated tab. | / | / | Low | / |
| **1.13** | Invalid input handling | User enters invalid characters or unsupported input (e.g., "123!@#") | App shows a friendly error message or fallback recommendation. | / | / | Moderate | / |
| **1.14** | Input autocomplete | The research field suggests autocomplete options based on input. | Suggestions are relevant and update in real-time as user types. | / | / | Low | / |
| **1.15** | Case insensitivity | User inputs uppercase or mixed-case terms. | App interprets input correctly regardless of letter case. | / | / | High | / |
| **1.16** | No match found | User enters an item not in the database. | App displays "no result" message with potential alternatives. | / | / | Moderate | / |
| **1.17** | Language support fallback | App is opened in a different device language. | App defaults to French or English with a fallback mechanism. | / | / | Low | / |
| **1.18** | Product image display | Search results include product names with images. | Images are displayed correctly with associated labels. | / | / | Low | / |
| **1.19** | Keyboard usability | Mobile user focuses on the research field. | On-screen keyboard opens, input remains visible and usable. | / | / | High | / |
| **1.20** | Input field accessibility | Test accessibility of research field with screen readers. | Field is labeled and read correctly. | / | / | Low | / |

## III. MVP version

| Test Case ID | Test Case Name             | Test Case Description                                          | Expected Result                                       | Actual Result | Tested | Priority | Pass/Fail |
| ------------ | -------------------------- | -------------------------------------------------------------- | ----------------------------------------------------- | ------------- | ------ | -------- | --------- |
| **2.01**     | Location-based suggestions | App uses store location to suggest in-stock items.             | Suggestions are relevant to current store.            | /             | /      | Moderate | /         |
| **2.02**     | Barcode scanner input      | User scans product barcode.                                    | App displays product info and pairing suggestions.    | /             | /      | High     | /         |
| **2.03**     | Error recovery             | App loses internet connection during search.                   | User is shown error with retry or offline fallback.   | /             | /      | Moderate | /         |
| **2.04**     | Search result filters      | User applies dietary filters (e.g., vegan, lactose-free).      | Results match applied filters accurately.             | /             | /      | High     | /         |
| **2.05**     | Save dietary profile       | User sets dietary preferences.                | Preferences are saved and applied to future searches. | /             | /      | Moderate | /         |
| **2.06**     | Navigation tab usability   | User navigates using bottom tabs (Search, Favorites, Profile). | Navigation works smoothly and highlights current tab. | /             | /      | Moderate | /         |
| **2.07**     | Basic analytics tracking   | App logs searches and favorites anonymously.                   | Analytics logs are created and sent.                  | /             | /      | Low      | /         |

## IV. Future Test Cases: Version 1

| Test Case ID | Test Case Name                 | Test Case Description                                                      | Expected Result                                      | Actual Result | Tested | Priority | Pass/Fail |
| ------------ | ------------------------------ | -------------------------------------------------------------------------- | ---------------------------------------------------- | ------------- | ------ | -------- | --------- |
| **3.01**     | In-store mode detection        | App detects when user is in an Intermarché store.                          | Switches to in-store mode with optimized UI.         | /             | /      | Moderate | /         |
| **3.02**     | Route to product               | Based on user location in-store, app shows fastest route to selected item. | Route is accurate and updates as user moves.         | /             | /      | High     | /         |
| **3.03**     | Voice input support            | User speaks a product name or dish.                                        | App processes voice and returns appropriate results. | /             | /      | Low      | /         |
| **3.04**     | Promotional deals integration  | App shows deals or discounts tied to search results.                       | Promotions appear inline with recommendations.       | /             | /      | Moderate | /         |
| **3.05**     | Real-time stock API            | App checks stock in selected store.                                        | Out-of-stock products are flagged or excluded.       | /             | /      | High     | /         |
| **3.06**     | Recommendation explanation     | App provides "why" behind pairing (e.g., cheese + wine logic).             | Tooltip or explanation is shown on request.          | /             | /      | Low      | /         |
| **3.07**     | Multi-language support         | User switches app language (e.g., English, French, Spanish, German).               | All UI elements and results change accordingly.      | /             | /      | Moderate | /         |
| **3.08**     | User feedback system           | User rates suggestions or reports wrong pairing.                           | Feedback is stored and acknowledged.                 | /             | /      | Low      | /         |
| **3.09**     | Accessibility compliance audit | App is tested against WCAG 2.1 AA standards.                               | No critical accessibility violations found.          | /             | /      | High     | /         |
| **3.10**     | AI-enhanced personalization    | Recommendations evolve with user behavior over time.                       | Suggestions become more tailored with use.           | /             | /      | Moderate | /         |
