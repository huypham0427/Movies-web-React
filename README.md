# Project - *Movies*

**Movies** is a movies app using the [The Movie Database API](https://developers.themoviedb.org/3).

Time spent: **19** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can view a list of movies currently playing in theaters. Poster images load asynchronously.
- [x] User can view movie details by tapping on a cell.
- [x] User sees loading state while waiting for the API.
- [x] User sees an error message when there is a network error.
- [x] User can pull to refresh the movie list.
- [x] Simple responsive.

The following **optional** features are implemented:

- [x] Add a tab bar for **Now Playing** and **Top Rated** movies.
- [x] Add a search bar.

## Video Walkthroguh
Here's a walkthrough of implemented user stories:

![gif](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

## License

    Copyright [2016] [Huy Pham]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

API_URL="https://api.themoviedb.org/3/movie/now_playing?api_key=<<api_key>>&language=en-US&page=1&fbclid=IwAR07o-_oLvsPWeAJQ0VwYxI2kEAaTA2UPo2XNrBqucDNfCL5Au0RBXSF8nk"

API_IMG="https://image.tmdb.org/t/p/w500/"

API_SEARCH="https://api.themoviedb.org/3/search/movie?api_key=<<api_key>>&language=en-US&page=1&include_adult=false"
