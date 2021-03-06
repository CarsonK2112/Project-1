# project_fun

## Team: project_fun
* Carson
* Nate
* Rocio
* Adam

## Links:
Link to repo: <https://github.com/nrmarsh36/project_fun>

Link to page: <https://nrmarsh36.github.io/project_fun/>

## Technology Used:
* Pure.css for responsive layout <https://purecss.io/>
* Foundation.css for responsive layout <https://get.foundation/>
* Bootstrap.css for responsive layout <https://getbootstrap.com/docs/3.4/css/>
* jQuery for dynamic HTML & CSS <https://jquery.com/>
* localStorage with JSON to retain saved date plans after a browser refresh
* $.ajax API calls to the spoonacular and tastedive API's
* spoonacular API for getting recipe results <https://spoonacular.com/food-api>
* tastedive API for getting movie, TV, video game, and music results <https://tastedive.com/read/api>

## Description:
![Screenshot of Date Night](images/date_night_overview_screenshot.jpg)
 
The purpose of this project is to create a dating-aid website that allows the user to choose between five categories: a movie, game, television series, music, and a food recipe. These options are pick and choose between any combination of the five. The system is modular in that picked options can be removed/added at will. The final options are then saved as a single saved date entry on the website which will remain even when the page refreshes. Multiple dates can be saved on the site.

The crux of the sites functionality is the use of two API's, Spoonacular and Tastedive. Both of these APIs are utilized by the search bars of the website, specifically Tastedive for movies, television, games, and music while Spoonacular comes into play for the food recipe search.

At the top of the page there is a navbar with the titular website name on the left, and on the right hand side workable links for the movie, game, tv shows, music, food, and the about section. Clicking on any of these links will take you to that respective portion of the website.
![Screenshot of Navbar](images/navbar.png)
The meat of the page is made up of the five search bar sections dedicated to movies, games, tv series, music, and food. Each section asks the user to type in their favorite option for each category and the request is sent to the API's data repertoire to pull the best matches. These matches will show up on the website with a description of the match and in the case of food a link to the recipe's website.
![Screenshot of Movies](images/movie_snip.png)
![Screenshot of Games](images/game_snip.png)
![Screenshot of Shows](images/show_snip.png)
![Screenshot of Music](images/tunes_snip.png)
![Screenshot of Food](images/dinner_snip.png)
Near the bottom of the page is the Date Summary section, which features two components. The first is the two options to show either the current date or the date list (showing multiple date entries if they exist). The second component comes into play when either of those options are selected, with a dropdown portion that shows the contents of the date or the list of dates. Clicking on the list of dates creates a dropdown that shows the actual list with the option to click on them and show the date's contents.
![Screenshot of Date Summary](images/date_summary_past_snip.jpg)
![Screenshot of Date Info](images/date_info_snip.jpg)
At the bottom of the page is an about section which summarizes the purpose of the website and user instructions.
![Screenshot of About](images/about.png)