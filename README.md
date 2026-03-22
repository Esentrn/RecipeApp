# Recipe Guide Application

Recipe Guide is a desktop application where users can store recipes and see which meals can be prepared using the ingredients they already have. The application was developed using **C# and WPF** and supports features such as dynamic search, filtering, recipe suggestions, and cost calculation.

---

## Project Features

### Dynamic Search and Filtering

- Search by recipe name or included ingredient
- Filter recipes by preparation time, cost, and number of ingredients

### Recipe Management

- Add, update, or delete recipes
- Add ingredients and their quantities to recipes
- Duplicate checks are performed to prevent the same recipe from being added again

### Ingredient Management

- Users can create new ingredients while adding a recipe or select from existing ingredients
- Ingredient stock quantity and unit price are stored in the database

### Recipe Suggestions

- See which recipes can be prepared based on available ingredients
- Recipes with missing ingredients are shown in red, while recipes with all required ingredients are shown in green
- View the total cost of missing ingredients

---

## Technologies Used

- **Programming Language:** C#
- **Framework:** WPF
- **Development Environment:** Visual Studio
- **Database:** Microsoft SQL Server

---

## Installation and Setup

### 1. Clone the Repository

Run the following commands in your terminal or command prompt:

```sh
git clone https://github.com/Esentrn/RecipeApp.git
cd RecipeApp
```

### 2. Run the Application

You can start the application by pressing `F5` in Visual Studio or by running the following command in the terminal:

```sh
dotnet run
```

---

## Screenshots

![Image](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp1.png)

![Image](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp2.png)

![Image](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp3.png)

![Image](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp4.png)

![Image](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp5.png)
