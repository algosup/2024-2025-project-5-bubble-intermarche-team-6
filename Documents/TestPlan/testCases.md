# Test Cases - Bubble Intermarché

## Table Of Content

</summary>

- [Test Cases - Bubble Intermarché](#test-cases---bubble-intermarché)
  - [Table Of Content](#table-of-content)
  - [I. Introduction](#i-introduction)
  - [II. Prototype version](#ii-prototype-version)

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
