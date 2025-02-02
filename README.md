# My Grandma's Recipe Box!

## Description:
    My Grandma's Recipe Box provides healthy and home style recipes from my grandma's kitchen to the homechef.
    The user is able to search for recipes that has the ingredient of their choice. 
    The search form has an autocomplete feature that suggests recipe ingredients to user when they start typing the ingredient. 
    The user is able to filter on health label, cusinie type and meal type. The user is able to save favorite recipes in the Recipe History so that they can revisit the url of the recipe at a later date.

## User Story & Acceptance Criteria:
    As a homechef,
    I want to make easy-to-read recipe
    So that I can cook at home
    Given I want to find a recipe,
    When I enter an ingredient into my search bar,
    Then I can view a list of recipes containing that ingredient

    As a homechef,
    I want to select a food restriction
    So that I can make recipes that fit my personal needs
    Given I want to find a recipe,
    When I select a health label in my dropdown
    Then I can view a list of recipes that fit that restriction

    As a homechef,
    I want to save my favorite recipe
    So that I can easily revisit it
    Given I want to access a favorite recipe,
    When I select recipe from the history menu
    Then I can visit the url of the recipe

## Link to Deployed Application:
    https://nbulger1.github.io/my-recipes/

## Link to Github Repository:
    https://github.com/nbulger1/my-recipes

## Technologies Used:
* *CSS Framework Used:*
    UIKit 
    https://getuikit.com/docs/introduction

* *APIs Used:*

    Recipe Search API: /api/recipes/v2
    https://developer.edamam.com/edamam-docs-recipe-api


    Food Database Autocomplete API: /autocomplete
    https://developer.edamam.com/food-database-api-docs

* *Local Storage:*
    Local Storage was used to save and retrieve favorite recipes over multiple page loads until the user chooses to clear Recipe History.

* *Media Queries:*
    Media Queries were used to make the UI responsive to various screen sizes.

## Screen Recording:

![GIF demonstrating testing the recipe box for a variety of conditions as well as assessing all button functionality](./assets/images/screen_recording_final.gif)

## Directions for Future Development
* Improve upon error handling for incomplete calls
* Autocomplete click off upon selection of an ingredient
* Creating Multiple Keyword Options - Theoretical User Story
##
    As a homechef
    I want to search the ingredients I already have in my kitchen
    So I can find a recipe I don’t have go to the grocery store to make
##
* Shopping Cart Request - Theoretical User Story
##
    As a homechef
    I want to put the possible shopping list items into a cart
    So I can easily place a grocery delivery order
##
* Limitation - Allotted 10 clicks per minute which doesn’t allow for quick searching


