# caffee-crust-lab01
Requirements documentation for the Caffee Crust Ordering System

# Caffee Crust System
## Overview
Cafe staff and customers need a streamlined way to place, manage, and track food and beverage orders efficiently.
The proposed system will help record menu selections, track order status, and process cafe transactions.
This system eliminates manual order errors and accelerates table service.

## Scope
- In scope: Browse cafe menu items (beverages, bakery, snacks).
- In scope: Place a new order with item titles and quantities.
- In scope: Track order status (Pending, Preparing, Ready, Completed).
- Out of scope: Table reservation management.
- Out of scope: Employee payroll and inventory supplier management.

## Stakeholders
- Customer: Browses the menu, places orders, and views order status.
- Barista / Kitchen Staff: Views incoming orders, updates preparation status, and marks orders ready.
- Project Maintainer: Manages repository configuration, documentation updates, and version releases.

## Functional requirements
- FR-01: The system shall let a customer create an order with selected menu items and quantities.
- FR-02: The system shall display the active list of pending and preparing orders for kitchen staff.
- FR-03: The system shall let staff mark an order status as completed or delivered.

## Nonfunctional requirements
- NFR-01: With 100 active menu items loaded, the menu catalog shall appear within 2 seconds in at least 95 of 100 trials on the cafe terminal.
- NFR-02: Every order placement and status update action shall be operable using only a keyboard or touchscreen gesture, checked against each documented workflow.

## Acceptance criteria
- FR-01: Given the item "Caramel Macchiato", saving a new order makes that item appear in the active kitchen queue.
- FR-02: Given two active orders, opening the kitchen dashboard shows both order summaries.
- FR-03: Marking a preparing order as complete changes its displayed status to Completed.

## Assumptions and open questions
- Assumption A-01: All cafe customers have access to the in-store digital kiosk or web app to place orders.
- Question Q-01: Will cash payments be integrated directly into the system or handled separately at the counter?
- Question Q-02: Which POS terminal hardware will be used to test NFR-01 performance benchmarks?
question no 3 : how much time do you want your order to get prepare ?

## Project status and viewing
This is a documentation-only project. No application has been built yet.
Clone the repository and open README.md in Notepad, or read it on GitHub.

## Author
Azeen — BS Software Engineering

## Contributing
Create a documentation branch, edit and review README.md,
commit and push the change, then open a pull request for review.