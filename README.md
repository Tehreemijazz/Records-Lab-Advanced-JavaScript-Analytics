# Records Lab – Advanced JavaScript Analytics

Records Lab is an interactive, data-processing dashboard built with **HTML, CSS, and Vanilla JavaScript**. It demonstrates advanced JavaScript concepts through a collection of 150+ task records, including data manipulation, functional programming, modern data structures, iterators, generators, and performance comparisons.

The project provides a practical way to understand how JavaScript handles data processing, filtering, asynchronous execution, and efficient lookups.

## Features

### 1. Interactive Dashboard
- Displays total records, total value, average value, and completion percentage.
- Visualizes records by category.
- Shows task status distribution.
- Provides a searchable and filterable records table.
- Supports sorting by different columns.
- Includes pagination.
- Allows marking tasks as completed.
- Tracks record views using WeakMap.

### 2. Data Management
- Generates 150+ sample task records.
- Validates incoming records.
- Rejects invalid or incomplete data.
- Supports duplicate removal based on selected properties.
- Implements immutable data updates.
- Provides a reset option to restore sample data.

### 3. Advanced JavaScript Data Structures

| Concept | Implementation |
| Map | Stores records by ID and groups records by status, user, and category. |
| Set | Maintains unique categories, users, and statuses. |
| WeakMap | Tracks record views without modifying record objects. |
| Symbol | Creates a unique internal source identifier. |

### 4. Functional Programming
- `pipe()` – Combines multiple functions.
- `compose()` – Executes functions from right to left.
- `curry()` – Converts functions into partially applicable functions.
- `memoize()` – Caches function results to avoid repeated calculations.
- Pure functions for calculations and data processing.
- Immutable updates and transformations.

### 5. Iterators and Generators
- Custom `RecordCollection` iterable.
- Implements `[Symbol.iterator]()` and `next()`.
- Uses `for...of` and iterable protocols.
- Generator-based batch processing.
- Processes records in batches of 10 using `yield` and `yield*`.

### 6. JavaScript Event Loop Demonstration
Demonstrates the execution order of:
- Synchronous code.
- Microtasks using `Promise.then()`.
- Microtasks using `queueMicrotask()`.
- Macrotasks using `setTimeout()`.

### 7. Performance Comparison
Compares:
- `Array.find()` for searching records.
- `Map.get()` for retrieving records.
- Map creation and initialization cost.
- Lookup speed differences.

The benchmark uses 50,000 records and performs 2,000 ID lookups.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Google Fonts – Public Sans

### JavaScript Concepts
- Map, Set, WeakMap, Symbol
- Higher-order functions
- Closures
- Currying and composition
- Memoization
- Iterators and generators
- Array methods
- Promises and microtasks
- Event loop
- DOM manipulation
- Performance measurement

## Project Structure

Records-Lab/
│
├── index.html
└── README.md

The application is organized into logical JavaScript modules within the main HTML file:

- fp module: Functional programming helpers.
- Data module: Data generation, validation, storage, indexing, filtering, and processing.
- Demo module: Event loop and performance demonstrations.
- UI module: Dashboard rendering and event handling.

## Getting Started

### 1. Clone the Repository

git clone -------

### 2. Navigate to the Project Folder

cd Records-Lab

### 3. Run the Application

Open `index.html` directly in your browser.

You can also use the **Live Server** extension in Visual Studio Code.

No additional dependencies or installation steps are required.

## Application Sections

| Section | Description |
| Dashboard | Displays records, statistics, filters, and data management tools. |
| Execution Order | Demonstrates synchronous code, microtasks, and macrotasks. |
| Performance | Compares Array searching with Map lookups. |
| Explanation | Describes the JavaScript concepts and project architecture. |

## Learning Objectives

This project demonstrates practical applications of advanced JavaScript concepts:

1. Understand and use modern JavaScript data structures.
2. Apply functional programming techniques.
3. Work with custom iterators and generators.
4. Understand JavaScript's event loop and asynchronous execution.
5. Improve data retrieval using Map-based indexing.
6. Apply immutable data management techniques.
7. Build interactive dashboards using DOM manipulation.
8. Understand memoization and performance optimization.

## Data Validation and Safety

- Rejects invalid records during loading.
- Validates required fields and data types.
- Checks task statuses, dates, and numeric values.
- Escapes dynamic text before rendering it as HTML.
- Handles empty search results.
- Keeps pagination within valid boundaries.

## Browser Compatibility

Designed for modern browsers that support ES6+ JavaScript features, including:

- Chrome
- Microsoft Edge
- Firefox
- Safari

## Author

Tehreem Ijaz

Computer Science Graduate | Aspiring Software Developer