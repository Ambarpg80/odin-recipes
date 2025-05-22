# Odin-Recipes

This is a practice repo to help me get back into coding daily. If you're looking at my work here on github you'll see I haven't been active in the past couple of months. Before that, I was teaching myself Python and going through the curriculum belonging to Flatiron School (which I attended). I learned Ruby as part of the Fullstack curriculum and was given access to the Python curriculum after graduation. I didn't like Python much though I am looking to try it again at a later date. Just not currently. Currently I am looking to go back to Javascript and dive deeper into Frontend development by expanding into Typescript and learning the Angular framework. I'm also looking to perhaps pick up Node, and Express on this journey. We'll see.

## Assignment 
Iteration 1: initial structure

    Within the odin-recipes directory, create an index.html file.
    Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.

Iteration 2: recipe page

    Create a new directory within the odin-recipes directory and name it recipes.
    Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use at Allrecipes. Be sure to include the usual boilerplate HTML. This boilerplate code should be in every .html file you create.
    For now, just include an h1 heading with the recipe’s name as its content.
    Back in the index.html file, add a link to the recipe page you just created. Example: Under the <h1>Odin Recipes</h1> heading, write out the link like so: <a href="recipes/recipename.html">Recipe Title</a>. The text of the link should again be the recipe name.

    Add a link back to the index page on your recipe page for easier navigation. You can place this link at the top or bottom of your recipe page (e.g., lasagna.html). Here’s an example:

   <a href="../index.html">Home</a>

    This allows users to quickly return to the home page after viewing the recipe.

Iteration 3: recipe page content

Your new recipe page should have the following content:

    An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or Allrecipes.

    Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.

    Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.

    Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

Iteration 4: add more recipes

    Add two more recipes with identical page structures to the recipe page you’ve already created.
    Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.

Example:

  <ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
  </ul>

Your links won’t be flashy, but for now, just focus on building them out.

I used the site [Dominican Cooking](https://www.dominicancooking.com/) for recipe references and photos.