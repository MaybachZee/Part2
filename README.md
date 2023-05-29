# Part2

[A.To use my Recipe Application, you have to follow these instructions:]

1. Compile and run the application using a C# IDE such as Visual Studio.
2. Once the application is running, it will display a menu with several options.
3. To enter a new recipe, choose option 1. Follow the prompts to enter the recipe details, including the number of ingredients, ingredient names, quantities, units, number of steps, and step descriptions. Repeat this process to add multiple recipes.
4. To display the recipes, choose option 2. The application will list all the recipes in alphabetical order by name, along with their ingredients and steps.
5. To select and display a specific recipe from the list, choose option 3. Enter the number corresponding to the desired recipe.
6. For each ingredient in a recipe, you can enter additional information such as the number of calories and the food group. This can be done when entering a recipe or by selecting option 3 and modifying an existing recipe.
7. The application will calculate and display the total calories of all the ingredients in a recipe and if the total calories of a recipe exceed 300, the application will notify you.
8. You can scale a recipe by a factor of 0.5, 2, or 3 by choosing option 4 and following the prompts.
9. You can reset the quantities of ingredients to their original values by choosing option 5 and selecting a recipe.
10. To clear all the data and start fresh, choose option 6. This will remove all the entered recipes.
11. The application does not persist the data between runs, so all the entered data will be stored in memory only while the application is running.
12. You can exit the application by choosing option 7 or closing the console window.

These instructions guide you through using the Recipe Application to manage and interact with your recipes, including entering new recipes, displaying, modifying, scaling, and resetting recipes, as well as managing the data.

[B. Github Link:]

https://github.com/MaybachZee/Part1.git

[C. Brief Description on what i changed:]

In my first Recipe Application, the I used arrays to store recipes, ingredients, and steps. However, in the updated version, generic collections (List) are used instead. This change allows for more flexibility in dynamically adding and removing recipes, ingredients, and steps without needing to predefine fixed array sizes.
Additionally, in the updated code I introduces a RecipeManager class to manage the collection of recipes. This class includes methods for entering a recipe, displaying all recipes, selecting a specific recipe to display, scaling a recipe, resetting a recipe, and clearing all data.
The implementation now includes the ability to enter an unlimited number of recipes with user-assigned names. The recipes are displayed in alphabetical order by name. For each ingredient, the user can input additional information such as calories and food group. The software calculates and displays the total calories of all the ingredients in a recipe, and it notifies the user if the total calories exceed 300.
Overall, these changes enhance the functionality and usability of the recipe application by introducing a more flexible data structure, additional features, and improved organization through the RecipeManager class.
