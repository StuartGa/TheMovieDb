##  💻 Proyect - The Movie Db


##  :wave: Welcome



###  🔧 Minium requierements

[![Kotlin](https://img.shields.io/badge/Kotlin-1.5-purple?longCache=true&style=popout-square)](https://kotlinlang.org)

[![Android Studio](https://img.shields.io/badge/Android_Studio-4.2-blue.svg?longCache=true&style=popout-square)](https://developer.android.com/studio)

[![Android](https://img.shields.io/badge/Android-5.4-green.svg?longCache=true&style=popout-square)](https://www.android.com)

##  :gear: Requierements

- Android Studio

- S.O Windows o MacOS

##  🛠️ Functionality

The Movie DB  is an application that consumes TheMovieDB API to be able to present the data of movies, within this application you will be able to find the catalog of movies, you will be able to indicate your favorite movies, you will be able to see the detail of these and you will also be able to see the related videos



##  :notebook: Especifications

 - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
 - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
 - [DataBinding](https://developer.android.com/topic/libraries/data-binding/)
 - [Navigation](https://developer.android.com/guide/navigation/)
 - [Room](https://developer.android.com/training/data-storage/room)
 - [Lifecycle](https://developer.android.com/topic/libraries/architecture/lifecycle)
 - [RxJava](https://github.com/ReactiveX/RxJava)
 - [Retrofit](https://square.github.io/retrofit/)
 - [OkHttp](https://square.github.io/okhttp/)
 - [Glide](https://github.com/bumptech/glide)
 - [MVVM](https://developer.android.com/jetpack/docs/guide)

##  :notebook: Missing Specs

-[Filters]:
In this case, I use the method GET /movie/now_playing to request the list  https://developers.themoviedb.org/3/movies/get-now-playing
and filter with chips https://material.io/components/chips#choice-chips 
For popular movies, I use the method GET/movie/popular to request the list https://developers.themoviedb.org/3/movies/get-popular-movies
and filter with chips https://material.io/components/chips#choice-chips
then need listen the changes on the chips to request and prepare the fragments lifecycle and present the mutable data

-[offline]:
first  create local SQLite Date Base then obtained JSON and storage in this database and a flag when the phone doesn't have a internet conection  when phone in offline mode and then send data to web server when phone is online



</div>


<footer>

<h3> Autores ✒️</h3>


* Stuart [![Web](https://img.shields.io/badge/GitHub-StuartGa-14a1f0?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/StuartGa)





<footer>



