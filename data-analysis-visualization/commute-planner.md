# Data Aggregation / Visualization Applications

## Commute Planner

#### Overview

Trying to plan your commute during a busy rush hour is the worst! Build an app to help plan your commute using public metro APIs.

#### MVP

* Users can view public metro data in a user-friendly format to understand things like peak transit times, frequency of train/vehicles, commute options, etc. What you display is up to you, as long as it's related to public transit data!
* Users can filter this data based on various fields (location, direction, transit type, and more).

#### Stretch Goals 

* Display results on top of a map with an interactive view.
* Show live indicators that warn when certain lines or delayed or cancelled.
* Support for multiple cities.
* Support for other types of transit (eg bike shares).

#### Technical Challenges

* Working with potentially irregular datasets.
* Connecting with multiple APIs.
* Displaying data in a user-friendly way.

#### Suggested Stack

* Consider using a noSQL database if your datasets are not naturally relational such as MongoDB or Firebase.
* Data Viz library such as D3 (if you want the most flexibility) or Chart.js (if you want basic graphs).
* React.

#### References

*[On My Line](https://www.youtube.com/watch?v=jBFyB05tqOY)