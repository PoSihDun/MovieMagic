Coding Challenge
The Challenge
We need a React.js webpage that can search OMDB for movies and allow the user to save their 
favourite films they feel should be up for nomination. 
When they've selected 5 nominees, they should be notified they are finished.

We would like a simple to use interface that makes it easy to:

    • Search OMDB and display the results (movies only)
    • Add a movie from the search results to our nomination list
    • View the list of films already nominated
    • Remove a nominee from the nomination list

	
WORKING SOLUTION: 1.0
Technical Requirements
    1. Search results should come from OMDB's API (free API key: http://www.omdbapi.com/apikey.aspx)-done - Completed
    2. Each search result should list at least its title, year of release and a button to nominate that film- Completed
    3. Updates to the search terms should update the result list- Completed
    4. Movies in search results can be added and removed from the nomination list- Completed
    5. If a search result has already been nominated, disable its’ nominate button - Completed - Broken when page is refreshed
    6. Display a banner when the user has 5 nominations-Completed

Extras
    •   Save nomination lists if the user leaves the page-Completed
    •   Animations for loading, adding/deleting movies, notifications-Completed
   

File Structure
[src Folder]
	|
	|
	|------[Compenents Folder]--|
	|							|
	|------App.css				|------AddNomination.js	
	|							|	
	|------App.js				|------Alert.js
	|							|
	|------config.js			|------MovieList.js
	|							|
	|------index.js				|------MovieListHeading.js	
	|							|
	|------syles.css			|------RemoveNomination.js
								|
								|------SearchBox.js
	
	Tech:
	HTML,
	CSS,
	ReactJs,
	LocalStorage
	OMdb API
	Postman
	Bootstrap
	
	