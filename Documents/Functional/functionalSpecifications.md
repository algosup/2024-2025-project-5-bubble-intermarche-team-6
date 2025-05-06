<br />
<div align="center">
  <h1 align="center">Functional Specifications</h1>
  <p align="center">
    <strong>Bubble Intermarché - Team 6</strong>
    <br />
  
  </p>
</div>

<details>
<summary><b>📖 Table of Contents</b></summary>

- [1. Introduction](#1-introduction)
  - [1.1. Project Overview](#11-project-overview)
  - [1.2. Project Definition](#12-project-definition)
    - [1.2.1. Project Context](#121-project-context)
    - [1.2.2. Project Scope](#122-project-scope)
    - [1.2.3. Target Audience](#123-target-audience)
  - [1.3. Project Organization](#13-project-organization)
    - [1.3.1. Project Team](#131-project-team)
    - [1.3.2. Stakeholders](#132-stakeholders)
  - [1.4. Project Timeline](#14-project-timeline)
- [2. Persona / Use Cases](#2-persona--use-cases)
  - [2.1. Persona](#21-persona)
    - [2.1.1. Luca](#211-luca)
    - [2.1.2. Claire](#212-claire)
    - [2.1.3. Antoine](#213-antoine)
  - [2.2. Use Cases](#22-use-cases)
    - [2.2.1. Cheese to Wine recommendation](#221-cheese-to-wine-recommendation)
    - [2.2.2. Dish to Cheese recommendation](#222-dish-to-cheese-recommendation)
    - [2.2.3. Wine to Cheese recommendation](#223-wine-to-cheese-recommendation)
- [3. Functional Requirements](#3-functional-requirements)

</details>

## 1. Introduction

### 1.1. Project Overview

Our web application is designed to enhance the customer experience at Intermarché by helping users find the perfect wine and cheese pairings. The app guides users through a smooth, decision-tree-based flow where they can start from a dish, a cheese, or a wine and receive tailored recommendations.

The application will guide users through a series of simple and user-friendly steps that simulate sommelier-like expertise. Depending on the user’s input (dish, wine, or cheese), the app will return the most appropriate product matches. It supports both casual users looking for inspiration and gourmet shoppers seeking the perfect pairing.


### 1.2. Project Definition

### 1.2.1. Project Context

Saint Remy de Provence's Intermarché is a local grocery store that offers a wide range of products, including wine and cheese. The store is known for having a large amount of foreigner customers, especially during the summer months. The store's wine and cheese section is particularly popular, but customers often struggle to find the perfect pairing. **This is where our application comes in.**

### 1.2.2. Project Scope

This project is a Proof of Concept (PoC) for a web application and will focus on the following key features:

- 🤝 **User-Friendly Interface**: The application should be intuitive and easy to navigate, allowing users to find wine and cheese pairings quickly.

- ⚙️ **Enhanced Customer Experience**: By providing tailored recommendations, the app aims to improve customer satisfaction and encourage repeat visits to Intermarché.

- 🍷🧀 **Wine and Cheese Matching**: The application will match wines and cheeses based on user input, providing a seamless experience for users looking to enhance their meals.

### 1.2.3. Target Audience

- 👤 **Local Customers**: Regular shoppers at Intermarché who are looking for quick and easy pairing suggestions.

- 👥 **Tourists**: Visitors to Saint Remy de Provence who may be unfamiliar with local products and are looking for recommendations.

- 👨‍🍳 **Food Enthusiasts**: Individuals who are passionate about food and wine pairings and are looking for expert advice.

- 🤵‍♂️ **Dinner Hosts**: People planning special occasions or dinner parties who want to impress their guests with the perfect wine and cheese pairings.

## 1.3. Project Organization

### 1.3.1. Project Team

| Name | Role | Responsibilities | Socials |
|------|------|------------------|------------------|
| Alexandre BOPP | Project Manager | Oversees project development, manage timelines, and coordinate team efforts. | [LinkedIn](https://www.linkedin.com/in/alexandre-bopp-682a97250/)|
| Victor LEROY | Program Manager | Manages the functional aspects of the project, including user interface and user experience. | [LinkedIn](https://www.linkedin.com/in/victorleroy18/) |
| Habi CAILLEAU | Technical Lead | Leads the technical development of the application, ensuring best practices are followed. Responsible for writing the technical specifications document. | [LinkedIn](https://www.linkedin.com/in/habi-cailleau-3b72b5293/) |
| Axel DAVID | Software Engineer | Develops the web application, implement features. | [LinkedIn](https://www.linkedin.com/in/axel-david-6384bb32a/) |
| Enzo GUILLOUCHE | QA Engineer | Responsible for testing the application, ensuring it meets quality standards and is free of bugs. | [LinkedIn](https://www.linkedin.com/in/enzoguillouche/) |

### 1.3.2. Stakeholders

| Name | Role | Responsibilities |
|------|------|------------------|
| Intermarché | Client | Provides the project requirements and feedback. |

## 1.4. Project Timeline

| Date | Milestone | Description |
|------|-----------|-------------|
| 04/23/2025 | Project Kickoff | Initial meeting to discuss project goals and objectives. |
| 05/16/2025 | Functional Specifications | Completion of the functional specifications document. |
| 05/28/2025 | Technical Specifications | Completion of the technical specifications document. |
| 06/06/2025 | Test Plan | Completion of the test plan document. |
| 06/16/2025 | First Prototype | Delivery of the first prototype of the application. |

## 2. Persona / Use Cases

### 2.1. Persona

#### 2.1.1. Luca

![img](img/luca.png)

#### 2.1.2. Claire

![img](img/claire.png)

#### 2.1.3. Antoine

![img](img/antoine.png)

## 2.2. Use Cases

### 2.2.1. Cheese to Wine recommendation

**Description**:  
While browsing in Intermarché, Luca picks up a regional cheese (e.g., “Tomme de Provence”) and wants to find a wine that complements it. Since he’s unfamiliar with French cheeses and doesn’t speak the language fluently, he uses the app to get a simple, local wine recommendation that will pair well and represent the region.

**Normal Flow**:  
1. Luca selects “Start from a Cheese” on the app homepage.  
2. He types the name of the cheese or selects it from a visual list (e.g., “Tomme de Provence”).  
3. The system retrieves pairing data for that cheese.  
4. The app displays a curated list of wines that pair well with it.  
5. The app highlights the best local or regional match.  
6. Luca optionally explores wine descriptions and price ranges.

**Alternative Flows**:  
- 2A. Cheese not recognized → App suggests similar cheeses or allows visual selection from categories (e.g., soft, hard, goat).  
- 5A. No local wine match → App suggests the next-best national pairing.

**Postconditions**:  
Luca receives a tailored wine suggestion that complements his selected cheese, with a focus on local/regional options.


### 2.2.2. Dish to Cheese recommendation

**Description**:  
Claire is preparing a meal for guests and wants to find the perfect cheese to accompany the dish. She uses the app to input the name of her dish (e.g., “coq au vin”). The system identifies the dish type (e.g., meat) and offers relevant cheese pairings. Claire can view similar cheeses and receive the best match to impress her guests.

**Normal Flow**:  
1. Claire selects “Start from a Dish” on the homepage.  
2. She types in the name of her planned dish (e.g., “ratatouille”).  
3. The system classifies the dish as vegetable-based.  
4. Claire chooses to receive cheese recommendations.  
5. The app displays a curated list of cheeses that match vegetable-based dishes.  
6. The app highlights the best match for the selected dish.  
7. Claire optionally explores similar cheese options.

**Alternative Flow**:  
- 2A. The dish is not recognized → The app offers a dropdown of predefined dishes or suggests editing the input.  

**Postconditions**:  
Claire receives one or more cheese recommendations tailored to her dish, helping her prepare a well-matched meal.

### 2.2.3. Wine to Cheese recommendation

**Description**:  
Antoine is planning a tasting evening and starts with a wine he enjoys (e.g., “Châteauneuf-du-Pape”). He uses the app to receive expert-level cheese recommendations that pair well with the selected wine. He also wants to explore a few similar pairing ideas for variety.

**Normal Flow**:  
1. Antoine selects “Start from a Wine” on the homepage.  
2. He inputs the name of his wine or selects it from a curated list.  
3. The system fetches pairing rules based on wine type (e.g., red, bold, Rhône Valley).  
4. The app displays recommended cheeses that match the wine.  
5. The app highlights a top pairing and offers 2–3 alternative cheese options.  
6. Antoine can tap any cheese to view flavor notes, textures, and suggested occasions.

**Alternative Flows**:  
- 2A. Wine not recognized → App prompts user to select a wine category (e.g., red/bold/dry) instead.  
- 4A. No cheese match → App shows generic pairings for similar wine styles.

**Postconditions**:  
Antoine receives a cheese pairing that complements his wine and expands his tasting experience, with optional deep-dives into flavor and origin.

## 3. Functional Requirements

To better understand how the app works, the diagram below presents a simplified view of the decision-tree flow that users follow when interacting with the Wine & Cheese Matcher. 

*(As the diagram is quite detailed, it is recommended to zoom in for better readability.)*

![flowchart](img/flowchart.png)

The application must support the following core features:


