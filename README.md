# Inventory Management System

This project is a comprehensive inventory management system developed in three different stages: an Android app, a web-based JavaScript app, and a database-enhanced web dashboard. The project demonstrates skills in Software Design and Engineering, Algorithms and Data Structures, and Databases, providing a complete solution for inventory management across multiple platforms.

## Table of Contents
1. [Overview](#overview)
2. [Software Design and Engineering](#software-design-and-engineering)
3. [Algorithms and Data Structures](#algorithms-and-data-structures)
4. [Databases](#databases)
5. [Getting Started](#getting-started)
6. [Project Structure](#project-structure)
7. [Future Enhancements](#future-enhancements)

## Overview

The Inventory Management System began as an Android app, then evolved into a web-based JavaScript application, and finally integrated advanced database functionalities with a dashboard for better data presentation. Each stage addresses different aspects of the project, focusing on improving design, algorithms, and data management.

## Software Design and Engineering

### Android App
- The initial version was developed as an Android application using Kotlin. The app supports basic CRUD operations for managing inventory items, including adding, viewing, updating, and deleting records.
- The `DataAdapter.kt` file handles data persistence and database interaction.

### Web-Based JavaScript App
- The project was extended to a web-based application, developed using JavaScript with a modern web architecture.
- It features a responsive user interface and maintains functionality from the Android app while offering cross-platform access.
- The app is built using components like `MainComponent.js` and `OtherComponents.js` and follows the Model-View-Controller (MVC) pattern for better code organization.
- The `public/` directory serves static files, while the `src/` directory contains the main app components.

## Algorithms and Data Structures

### Caching and Optimization
- The web-based app improves data handling through caching mechanisms implemented in JavaScript, optimizing data retrieval based on usage patterns. This helps reduce the number of direct database queries and improves overall performance.
- Algorithms for sorting and filtering inventory items have been implemented to allow users to search efficiently.

### Data Validation
- Data structures are used to validate user inputs and maintain consistent data formats across the system.
- Additional algorithms ensure the integrity of the inventory data by performing checks before data is added or modified.

## Databases

### Database Integration
- The project integrates a database backend that supports both the Android and JavaScript versions of the app.
- Queries are used to handle data manipulation tasks, such as searching, sorting, and aggregating inventory data.

### Web-Based Dashboard
- A web-based dashboard is included to visualize inventory data using queries. The dashboard supports data mining techniques to refine search results and present relevant information to the user.
- The dashboard interface allows users to interact with the data, providing insights into inventory levels, recent changes, and other key metrics.

### Mongoose Schema and Database Access
- In the JavaScript version, the Mongoose library is used for schema creation and database access, providing a structured way to handle data operations.
- Controllers and routes are defined to manage API endpoints, tested using Postman to ensure robust and secure database access.

## Getting Started

### Prerequisites
- Android Studio for the Android app version.
- Node.js and npm for the JavaScript web app.
- A MongoDB database for storing inventory data.
- Git for version control.

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/inventory-management-system.git
