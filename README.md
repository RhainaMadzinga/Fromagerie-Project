# Fromagerie-Project
Overview

This is a small, independent project designed for managing cheese inventory in a fromagerie (cheese shop). The purpose of this software is to keep track of different types of cheeses available for sale, including information about each cheese’s name, price per kilogram, and stock status. The system consists of two main classes:

Cheese: Represents a single cheese item, including details like name, price, and availability.

Fromagerie: Manages a collection of different cheeses using an ArrayList, allowing for operations such as adding, removing, and checking stock levels for cheeses.
This standalone project is designed for straightforward use in small-scale cheese shop management but can be easily expanded or integrated into larger inventory management systems if needed.

# Project Structure
Cheese Class
The Cheese class stores information about individual cheese varieties. Each cheese object includes:

- name (String): The unique name of the cheese (e.g., "Brie", "Cheddar").
- price per kg (double): The price of the cheese per kilogram.
- inStock (boolean): Indicates whether this cheese is currently in stock.

This class provides methods to access and modify each field, supporting basic cheese information retrieval and updates.

Fromagerie Class

The Fromagerie class manages an inventory of cheeses using an ArrayList of Cheese objects. This class is partially implemented; your task is to complete it by adding methods to handle the cheese inventory. You’ll be using Java’s ArrayList collection and iteration techniques to manage the cheeses efficiently.

Key functionalities to implement in the Fromagerie class may include:

- addcheese (Cheese cheese): Adds a new cheese to the inventory.
- removeCheese(String name): Removes a cheese from the inventory by its name.
- listInStockCheeses(): Lists cheeses that are currently in stock.
- updateCheeseStock(String name, boolean inStock): Updates the stock status of a specific cheese.

