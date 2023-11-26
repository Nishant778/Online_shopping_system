# Online_shopping_system

## Description:-

The "Online Shopping System" project is a Java-based application that allows users to shop for various products. It is designed with a focus on Object-Oriented Programming (OOP) principles, including encapsulation, inheritance, and abstraction.


## Overview of the Project:-

The project simulates an online shopping system where users can access the system by providing an account number and PIN. Once authenticated, they can navigate through product categories (Men, Women, Children) and select items to purchase. The project also calculates and displays billing details.


## Structure:-

The project is structured into several classes and interfaces to maintain code modularity and organization. Key classes and interfaces include:

--> CustomerDetails: Extends Men class and implements the Decide interface. This class handles user details, authentication, and item selection.

--> Men, Women, and Kids classes: These classes represent the product categories and inherit from each other in a multilevel inheritance hierarchy.

--> Bill: Responsible for calculating and displaying billing information.
Decide interface: Contains the selection method, which is overridden in the CustomerDetails class for abstraction.


## How to Run the Project:-

--> Clone or download the project from the repository.

--> Open the project in your Java development environment.

--> Compile and run the CustomerDetails class, which serves as the entry point.


## Key Principles and Concepts:-

### 1) Encapsulation

The project encapsulates the account number and PIN as private fields in the CustomerDetails class, ensuring that they can only be accessed and modified through defined methods.

### 2) Inheritance

Multilevel inheritance is used in the product category classes (Men, Women, Kids) to create a hierarchical structure, allowing for the extension of functionalities.

### 3) Abstraction

Abstraction is achieved through the Decide interface, which defines the selection method that is implemented in the CustomerDetails class. This enables abstraction for product selection.

### 4) Polymorphism (Variable Shadowing)

Polymorphism is employed in the CustomerDetails class using variable shadowing. Specifically, the variable amt2pay is defined as 0 initially. After each purchase, the price of the item is sent as an actual argument to the totalAmt method in the Bill class. In the Bill class, the amt2pay variable is used to accumulate the total cost by adding up all the prices of the purchased items. This demonstrates polymorphism through the dynamic association of amt2pay with different purchase operations, providing flexibility in handling total costs.


## Functionality and Usage:-

-->User authentication with account number and PIN.

-->Navigation through product categories (Men, Women, Children).

-->Product selection and purchase.

-->Billing and receipt generation.

-->Option to continue shopping or exit.



