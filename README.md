# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

Assgn3:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Favorite Food</title>
    
    <!-- Internal CSS -->
    <style>
        /* General Body Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        /* Header Styles */
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        /* Navigation Styles */
        nav {
            background-color: #444;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        /* Section Styles */
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
        }

        section img {
            display: block;
            margin: 0 auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Favorite Food Page!</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About My Food</a></li>
            <li><a href="#recipe">Recipe</a></li>
            <li><a href="#nutrition">Nutritional Information</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About My Favorite Food</h2>
        <p>My favorite food is Pizza! It's a delicious combination of dough, cheese, and various toppings like pepperoni, mushrooms, and olives. I love how customizable it is and how it brings people together.</p>
        <img src="https://images.pexels.com/photos/4584974/pexels-photo-4584974.jpeg" alt="Pizza" width="300">
    </section>

    <section id="recipe">
        <h2>Recipe</h2>
        <p>Here’s a simple recipe for making your own pizza at home:</p>
        <ul>
            <li>Ingredients:</li>
            <ul>
                <li>Pizza dough</li>
                <li>Tomato sauce</li>
                <li>Cheese (mozzarella)</li>
                <li>Your favorite toppings (pepperoni, mushrooms, etc.)</li>
            </ul>
            <li>Steps:</li>
            <ol>
                <li>Preheat the oven to 475°F (245°C).</li>
                <li>Roll out the pizza dough on a flat surface.</li>
                <li>Spread the tomato sauce evenly on the dough.</li>
                <li>Sprinkle the cheese and add your toppings.</li>
                <li>Bake for 10-12 minutes or until the crust is golden brown.</li>
            </ol>
        </ul>
    </section>

    <section id="nutrition">
        <h2>Nutritional Information</h2>
        <p>Here's the approximate nutritional value for one slice of pepperoni pizza:</p>
        <ul>
            <li>Calories: 285 kcal</li>
            <li>Protein: 12g</li>
            <li>Fat: 12g</li>
            <li>Carbohydrates: 35g</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 My Favorite Food Page</p>
    </footer>

</body>
</html>

