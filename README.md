# Meal Finder App

Search and generate random meals from the [themealdb.com](www.themealdb.com) API

## Project Specifications

- Display UI with form to search and button to generate
- Connect to API and get meals
- Display meals in DOM with image and hover effect
- Click on meal and see the details
- Click on generate button and fetch & display a random meal

## Description

This is a JavaScript code that fetches meal data from an API and displays it on a webpage.

The code defines several constants and event listeners. The `search`, `submit`, `random`, `mealsEl`, `resultHeading`, and `single_mealEl` constants are used to reference various elements on the webpage.

The `searchMeal` function is used to search for meals based on a user-entered search term. It prevents the default form submission behavior, clears the `single_mealEl` element, and fetches meal data from an API based on the search term. The fetched meal data is then displayed on the webpage if any matches are found.

The `getMealById` function is used to fetch meal data based on a meal ID. It clears the mealsEl and resultHeading elements, fetches meal data from an API based on the ID, and displays the fetched meal data on the webpage.

The `getRandomMeal` function is used to fetch a random meal from the API. It clears the mealsEl and resultHeading elements, fetches a random meal from the API, and displays the fetched meal data on the webpage.

The `addMealToDOM` function is used to add a meal to the `single_mealEl` element. It extracts information about the meal's name, image, category, area, instructions, and ingredients from the fetched meal data and formats it in HTML to be displayed on the webpage.

Finally, there are several event listeners that listen for user interactions with the webpage. The submit event listener listens for form submissions to trigger the `searchMeal` function. The random event listener listens for clicks on the "Random" button to trigger the `getRandomMeal` function. The `mealsEl` event listener listens for clicks on meal items to trigger the `getMealById` function with the clicked meal's ID.

## Technologies used

![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate
