# The Odin Project
This repository is part of The Odin Project Foundations course series and each module and project will have the prefix 'odin-'.

## Project 1: Recipes
This is the Recipes project as part of The Odin Project Foundations course.

## Table of Contents
1. [Assignment](#assignment)
2. [Reflections](#reflections)
3. [Technology Stack](#technology-stack)
4. [Testing and Validation](#testing-and-validation)
5. [Deployment and Version Control](#deployment-and-version-control)
6. [Credits](#credits)
7. [Acknowledgements](#acknowledgements)

## Assignment

### Iteration 1: initial structure
1. Within the odin-recipes directory, create an index.html file.
2. Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.

### Iteration 2: recipe page
1. Create a new directory within the odin-recipes directory and name it recipes.
2. Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use at Allrecipes.
3. For now, just include an h1 heading with the recipe’s name as its content.
4. Back in the index.html file, add a link to the recipe page you just created. Example: Under the ```<h1>Odin Recipes</h1>``` heading, write out the link like so: ```<a href="recipes/recipename.html">Recipe Title</a>```. The text of the link should again be the recipe name.

### Iteration 3: recipe page content
Your new recipe page should have the following content:

1. An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or Allrecipes.
2. Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.
3. Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.
4. Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

### Iteration 4: add more recipes
1. Add two more recipes with identical page structures to the recipe page you’ve already created.
2. Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.

## Reflections
During this project I revisted the structure of a html document and how to add images and links to a webpage. As well as making use of ordered and unordered lists. 

## Technology Stack

### Languages
* HTML5

### Frameworks and Tools
* Git
* GitHub

## Testing and Validation
To test and validate the HTML code of the website, the W3C Markup Validation Service was used, resulting in zero errors or warnings.

## Deployment And Version Control

### Deployment
GitHub Pages was used in order to deploy the live version of the website. This was done by completing the following:
1. Locate and click on the Settings tab within the repository
2. From here on the left hand side go down and click Pages
3. The GitHub Pages page will be displayed, locate the Source and set the branch to main
4. If this has been completed successfully then a message will be displayed at the top with a green check "Your site is published at https://hardingrichard.github.io/odin-project/"  
  
[Click Here](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) for further guidance and instructions on how to deploy yours.

### Cloning
If you wish to clone the repository you can do so by [clicking here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) or completing the following:
1. Locate and click on the Code button at the top of the directory within the GitHub repository
2. This will dropdown the option of HTTPS, SSH and GitHub CLI and the option to open with GitHub Desktop or Download ZIP. Choose the option you prefer and click the copy to clipboard button
3. Open the Git bash terminal
4. Choose the working directory location to where you wish to have the cloned directory.
5. Type "git clone" followed by pasting the URL you copied in step 2.
6. Press Enter to complete and create your local clone.

### Version Control
[Click here](https://github.com/hardingrichard/odin-recipes/commits/main) to explore the history of the creation process and see what the website looked at different points in time and what changes were made. Regular commits were made in order to make it easier to view the thought process during the creation of the website and readme and also have saved back up points to avoid loss of work in case of any serious malfunctions.

## Credits

### Assets Used
The following images were used each recipe page:
* Image of [Lasagna](assets/images/lasagna.jpeg) on [AllRecipes](https://www.allrecipes.com/recipe/23600/worlds-best-lasagna/)
* Image of [Tacos](assets/images/tacos.jpeg) on [AllRecipes](https://www.allrecipes.com/recipe/242342/fiesta-slow-cooker-shredded-chicken-tacos/)
* Image of [Empanadas](assets/images/empanadas.jpeg) on [AllRecipes](https://www.allrecipes.com/recipe/71805/fried-empanadas/)

## Acknowledgements
With thanks to [The Odin Project](https://www.theodinproject.com) for providing an exceptional curriculum and resources that have significantly contributed to the development of this project. Their comprehensive courses and supportive community have been invaluable in my learning journey.