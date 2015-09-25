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
  teaser: /popularmovies/projectView.jpg
---

###Overview
Popular Movies is an android application that displays popular and highest rated movies.  
It also allows a user to keep a list of favorite movies locally using a content provider. It is also  
optimized for both phone and tablet experience using a two pane display.  

![FirstView](/images/popularmovies/MovieGridView.PNG)
![MovieDetailDesc](/images/popularmovies/MovieDetailDesc.PNG)
![SortByOptions](/images/popularmovies/SortByOptions.PNG)

Features
------------------
+ Display/discover movies sorted by most popular, highest rated, or favorites
+ Add movie to favorites/Remove from favorites
+ View favorite movies even when offline
+ View details of each displayed movie: rating, release date, overview, reviews
+ Watch movie trailer from available trailers
+ Send trailer link to friends 

Libraries used:
---------------------
+ [Picasso](http://square.github.io/picasso/): for image downloading and caching 

##Using the Source

<p>
To use this application, download an api key from [themoviedb](https://www.themoviedb.org/documentation/api).
Insert api key in the file 'string_api_key.xml' in the field marked. 
The file is under values resources folder. </p>

###Additional Screenshots
Obtained using Genymotion emulator Galaxy S4 and Nexus 10 tablet

![MoreMovieDetail](/images/popularmovies/ViewMovieDetails.PNG)
![FavoriteAdded](/images/popularmovies/AddToFavs.png)
![SecondViewScroll](/images/popularmovies/ScrollMovieGridView.PNG)