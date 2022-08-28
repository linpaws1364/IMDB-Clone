# Welcome to Movie Info Project (IMDB clone)

Please use the following link to access the live project - https://linpaws1364.github.io/IMDB-Clone/

# Features
Home Page
1. Search any movie from the API and display the search results on the frontend (as I type the search results should update, just like Google does for suggestions).
2. Each search result of the movie should have a favourite button, clicking on which the movie should be added to “My favourite movies” (a list).
3. On clicking any particular search result (any movie), open a new page with more information about that movie (movie page)

Movie Page
1. Should show information about the movie like its name, photo, plot, etc (these are must, rest you can add if you want).

My favourite movies Page
1. Display a list of all the favourite movies.
2. Make this list persistent (should have the same number of movies before and after closing the browser/refreshing the browser).
3. Remove from favourites button: Each movie should have remove from favourites button, clicking on which should remove that movie from the list.

# Tech Stack Used
HTML, CSS, Bootstrap and Js

# Approach
The search bar can be used to search any movie/web series. Once relevant results come up, the details will be shown for the movie/web series along with an info button and Add to Favourite Button. On clicking the info button, a new page will open up showing details of the serach result like name, genre, director, plot etc. On clicking the Add to Favourite, the movie is removed from main page and added to favourites page. We can access the favourites list from favourite button in the nav bar. In the favourites list page, the list of added movies is shown along with remove button for each entry which can be used to remove the entry. We can go back to main page by clicking on Home button.
