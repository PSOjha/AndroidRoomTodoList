# AndroidRoomTodoList

    This application makes it easy to manage your task list on Android phones & tablets.
    
we are going to be creating a ToDo Listing application using the Android Architecture Components.

#### Why Room

The Room persistence library provides an abstraction layer over SQLite to allow fluent database access while harnessing the full power of SQLite. The library helps you create a cache of your app's data on a device that's running your app. This cache, which serves as your app's single source of truth, allows users to view a consistent copy of key information within your app, regardless of whether users have an Internet connection.

    implementation "android.arch.persistence.room:runtime:1.0.0"

    annotationProcessor "android.arch.persistence.room:compiler:1.0.0

#### The output of the above application in action is given below.

![android-room-todolist-output](https://user-images.githubusercontent.com/32029236/109394190-bae4d880-794b-11eb-9be8-fbc32aa9d9bb.gif)


#### User Stories

 User can successfully add and remove items from the todo list
