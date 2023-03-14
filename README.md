# Movie-summary
Movie App using 
HTML, 
CSS, and 
Javascript
FUNCTIONS USED IN JAVASCRIPT
getMovies() — A function to fetch movies from API and returns the results using fetch function.The results will be passed to showMovies() function.
showMovies() — A function to showcase the results in the browser which basically inserts the HTML code dynamically.The data to this function is passed from the getMovies() function.
getClassByRate() — A function which returns the color based on movie rating obtained from API. This color is used in CSS to choose the color of the movie rating text.
a MovieSearchEventListener for event listening. When you type the title of the film into the search bar and press Enter, the event listerner is activated and the form is actually submitted. The movie whose name matches the one supplied in the search field will be fetched from the API, and all the related titles will be displayed automatically on the list.
CSS Styling
Flex was used to organise the list of movies that the API returned. the div class overview, the movie-info div class, which keeps information about the movie such its name and rating, and the img tag that contains the movie's image
