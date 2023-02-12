## Redux-on-Rails

#### Overview
Redux is a powerful tool to manage state in applications. However, there is a significant amount of boilerplate code that needs to be written across multiple files in order to integrate it into a React project. Redux-on-rails is an npm package and web application that can be used to reduce the amount of code that needs to be written by hand in order to add Redux to your web application. Reference project: [Redux Genie][https://www.youtube.com/watch?v=Ba1xlQnEyJg&list=PLx0iOsdUOUmm5E5LET5lb_P7Xb-q40LrD&index=12&t=0s]

#### MVP
A user should be able to run various commands on the CLI to generate boilerplate files that configure redux to do CRUD actions. This includes the creation of action types, action creators, thunk creators, and reducers. The structure can include a config file for additional customization. 

#### Technical Challenges
* Create and publish an npm package
* Use node to create and update files
* Regex for finding specific parts of files to update

#### Stretch Goals
* A user should be able to generate a config file using a web UI, which can then be downloaded and used in the project.
* A user can specify different modular file structures for how the redux code is laid out. 
