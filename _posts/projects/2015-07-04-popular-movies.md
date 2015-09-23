---
layout: article
title: "Popular Movies"
categories: projects
modified: 2015-04-09T11:57:41-04:00
tags: [training]
comments: false
ads: false
share: true
image:
  teaser: /popularmovies/MovieGridView.png
---

Popular Movies is an android application that displays popular and highest rated movies. It also allows a
user to keep a list of favorite movies locally using a content provider. It is also optimized for both phone and tablet experience using a two pane display.

Features
------------------
+ Display/disocver movies sorted by most popular, highest rated, or favorites
+ Add movie to favorites/Remove from favorites
+ View favorite movies even when offline
+ View details of each displayed movie: rating, release date, overview, reviews
+ Watch movie trailer from available trailers
+ Send trailer link to friends 

Libraries used:
---------------------
+ [Picasso](http://square.github.io/picasso/): for image downloading and caching 

Using the Source
------------------
To use this application, download an api key from [themoviedb](https://www.themoviedb.org/documentation/api).
Insert api key in the file 'string_api_key.xml' in the field marked. 
The file is under values resources folder. 

Screenshots
-------------------
Obtained using Genymotion emulator Galaxy S4 and Nexus 10 tablet

![FirstView](/images/popularmovies/MovieGridView.PNG)
![SecondViewScroll](/images/popularmovies/ScrollMovieGridView.png)
![SortByOptions](/images/popularmovies/SortByOptions.png)

![MovieDetailDesc](/images/popularmovies/MovieDetailDesc.png)
![MoreMovieDetail](/images/popularmovies/ViewMovieDetails.PNG)
![FavoriteAdded](/images/popularmovies/AddToFavorites.PNG)

![TabletView](/images/popularmovies/TabletView.PNG)

