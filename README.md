# Project 1 - *Flicks Basic*

**Flicks Basic** is a movies app using the The Movie Database API(http://docs.themoviedb.apiary.io/#).

Time spent: **12** hours spent in total

## User Stories

The following **required** functionality is complete:

- [X] User can view a list of movies currently playing in theaters from The Movie Database.
- [X] Poster images are loaded using the UIImageView category in the AFNetworking library.
- [X] User sees a loading state while waiting for the movies API.
- [X] User can pull to refresh the movie list.

The following **optional** features are implemented:

- [X] User sees an error message when there's a networking error.
- [X] Movies are displayed using a CollectionView instead of a TableView.
- [X] User can search for a movie.
- [X] All images fade in as they are loading.
- [X] Customize the UI.

The following **additional** features are implemented:

- [X] Added button to toggle between CollectionView and TableView
- [X] Added launch screen and icons

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. Consider writing code to make the network request directly in swift instead of using a 3rd party library


## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/1ILoTdM.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with LiceCap (http://www.cockos.com/licecap/).

## Notes

Cocoapod installation required migrating to Cocoa Pods 1.0.0. 

## License

    Copyright 2017 Barbara Ristau 

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

# Project 2 - *Flicks the Sequel*

**FLICKS THE SEUQEL** is a movies app displaying box office and top rental DVDs using [The Movie Database API](http://docs.themoviedb.apiary.io/#).   

Time spent: **10** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can view movie details by tapping on a cell.
- [X] User can select from a tab bar for either **Now Playing** or **Top Rated** movies.
- [X] Customize the selection effect of the cell.

The following **optional** features are implemented:

- [X] For the large poster, load the low resolution image first and then switch to the high resolution image when complete.
- [X] Customize the navigation bar (implemented shadow styling in detail view controller) 

The following **additional** features are implemented:

- [X] Implemented autolayout.
- [X] Customized appearance of tab bar.
- [X] Implemented search bar inside navigation bar
- [X] Programmatically implemented styling to the nav bar, including shadow styling on the DetailsViewController
- [X] Modified code to facilitate smooth transition betweetn tableview and collectionview, within the appropriate endpoints
- [X] Added feature to save a movie as a favorite 
- [X] Added endpoint for upcoming movies and implemented in the tab bar controller
- [X] Added tab bar icon for the movies saved as favorites 

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. Modify the app to create a Movie struct or class, and use this to populate the different view controllers
2. Introduce to persistence for saving the movies and accessing them after restarting 

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src="http://i.imgur.com/78uOjs1.gif" title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with LiceCap (http://www.cockos.com/licecap/).

## Notes

Icons obtained via iconmnstr.com 

## License

    Copyright 2017 Barbara Ristau 

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
