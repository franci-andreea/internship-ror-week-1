# Ruby on Rails Internship Assignment 1

## Requirements
- Create the front page of a food ordering service respecting a given design
- Hovering a food item has to include an animation

## Implementation
The technologies used for this assignment are: HTML, CSS and JavaScript.
The structure of the website is composed of 3 main components: header, body, footer.

The header represents the main presentation panel of the page. It includes the navigation bar, a welcoming message and a restaurant background image.

The body contains 4 filters and a list of (some hardcoded) food items. The first 3 filters are implemented as dropdown menus and are based on the following: 
the category (Second Course, Dessert, Entrees), the sorting and if it is a Vegetarian dish or not. The price range filter was implemented using noUiSlider 
with 2 handles. Each food item is mapped using a general style class. For displaying a specific number of items per row I have used flex-wrap.

The footer includes the contact details of the food ordering service.

## Difficulties / Blockers
- Implementing the price range slider was the hardest part of the project
- Modifying a background image contained in the <header> without altering other elements inside this tag.

## What have I learned?
- How to use flexbox properly considering the parent and the child elements
- How to structure an HTML page using header, body and footer components
- How to customize the noUiSlider and use it for future front pages
