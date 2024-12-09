# Ice Cream Parlor Management System

## Project Overview
This is a Python-based Ice Cream Parlor Management application that allows users to manage flavors, ingredients, allergens, and a shopping cart using a SQLite database.

## Prerequisites
- Python 3.8 or higher
- SQLite3

## Setup and Installation

### 1. Clone the Repository
bash
git clone https://github.com/yourusername/ice-cream-parlor.git
cd ice-cream-parlor


### 2. Create a Virtual Environment (Optional but Recommended)
bash
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate


### 3. Install Dependencies
bash
pip install sqlite3


### 4. Project Structure

ice-cream-parlor/

├── main.py               # Main application entry point

├── models.py              # Data models for Flavor, Ingredient, Allergen, Cart

├── database.py            # Database connection and operations

└── README.md              # This readme file


### 5. Running the Application
bash
python main.py


## Application Features
- Add and view ice cream flavors
- Search for flavors
- Manage ingredients
- Add allergen information
- Shopping cart functionality

## Database
- The application uses SQLite to persistently store:
  - Flavors
  - Ingredients
  - Allergens
- A local ice_cream_parlor.db file will be created automatically

## Usage Guide

### Main Menu Options
1. Add Flavor
   - Enter flavor details like name, description, seasonality, and price

2. View Flavors
   - See all flavors or filter seasonal flavors

3. Search Flavors
   - Find flavors by keyword in name or description

4. Add Ingredient
   - Track ingredients with name, quantity, and unit

5. Add Allergen
   - Record allergen information

6. Manage Cart
   - Add/remove flavors
   - View cart contents
   - Calculate total price

7. Exit
   - Close the application

## Troubleshooting
- Ensure Python 3.8+ is installed
- Check that all required files are in the same directory
- Verify SQLite3 is available in your Python environment

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request
