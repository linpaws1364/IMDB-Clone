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
The search bar can be used to search any movie/web series. Once relevant results come up, the details will be shown for the movie/web series along with an info button and Add to Favourite Button. On clicking the info button, a new page will open up showing details of the search result like name, genre, director, plot, etc. On clicking the Add to Favourite, the movie is removed from the main page and added to the favorites page. We can access the favorites list from a favorite button in the nav bar. On the favorites list page, the list of added movies is shown along with a remove button for each entry which can be used to remove the entry. We can go back to the main page by clicking on the Home button.

# Screenshots 

1. Main Page

![FlicBuff _ Your Movie Companion](https://user-images.githubusercontent.com/101203567/187538865-f3b6aded-6717-4612-9497-f9c47b4a5a0f.png)

2. Info Page

![FlicBuff _ Movie Description](https://user-images.githubusercontent.com/101203567/187539078-ae5817ff-d52f-4246-bdf2-d47ec1fcce76.png)

3. Favourites Page

![FlicBuff _ Favourite Movies](https://user-images.githubusercontent.com/101203567/187539175-5173bc69-d4ee-42e5-8bab-4b4736bafb64.png)
