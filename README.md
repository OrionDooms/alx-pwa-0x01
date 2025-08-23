# moviedataBase API.
API Explorer: Mastering RESTful Connections

## API Overview
MoviesDatabase API has a collection over 9 million of information for movies, tv-shows, actors. Includes youtube trailer url, awards, full biography, and many other usefull informations.

## Available Endpoints
### Titles
* /titles -  Returns array of titles according to filters/sorting query parameters provided.
* /x/titles-by-ids - Returns array of titles according to array of id's provided.
* /titles/{id} - Returns title acording to filters / sorting query
* /titles/{id}/ratings -Returns title rating and votes number
* /titles/series/{id} - Returns array of episodes only with episode id, episode number and season number in ascending order.
* /titles/seasons/{id} -Returns number of seasons for the series (integer).
* /titles/seasons/{id}
path parameter (required) Returns number of seasons for the series (integer).
* /titles/episode/{id} - Returns episode according to filters / sorting query parameters provided
* /titles/x/upcoming - Returns array of upcoming titles according to filters / sorting query parameters provided
### Search
* /titles/search/keyword/{keyword} - Returns array of titles according to filters / sorting query parameters provided and the keyword provided in path.
* /titles/search/keyword/{keyword} - Returns array of titles according to filters / sorting query parameters provided and the keyword provided in path.
### Actors
* /actors - Returns array of actors according to filters provided.
*  /actors/{id} - path parameter (required) : imdb id of actor
### Utils
* /title/utils/titleType - Returns array of title types,