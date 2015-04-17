# Overview

In order to introduce you to the responsibilities of a front-end and/or web developer in Telerik and to assess your required skills, we would like you to create a SPA that will represent a simplified but interactive Team Pulse `board`. The `board` will contain `cards`, representing the data objects in the application.



# Data

The application works with the following data objects:

    {
        "id": integer,
        "title": string,
        "status": string,
        "type": string
    }

- `id` represents the ID of the item in the backend database
- `title` is a free text
- `status` can be one of the following predefined strings: "not started", "in progress", "done"
- `type` can be one of the following predefined strings: "bug", "story", "task"

The objects are stored and retrieved through a web service, that is connected to a database. All changes that are made on the data objects must be persisted, so that when the application is closed and opened again, the state is the same.



# Server

Create a RESTful web service using ASP.NET WebApi and use a database of your choice.

Use best practices for server-side development.



# Client

Use your favorite client-side application framework: Knockout, Backbone, Angular, etc. it is your choice and there is no wrong choice (except "no framework" :)).

Use best practices for client-side development.



# How it works

The `board` must have columns for each of the values of the `status` property. The `cards` in the board represent the data objects in the application and are displayed in the column with the corresponding status.

The `cards` contain the `title` of the corresponding data object.

The `cards` have different styles depending on their `type`.

When a `card` is dragged to another column, the application must change the corresponding object's `status` property and immediately persist the change.



# Design

Don't worry too much about the design, make it simple, but it is important to ensure the app looks and works the same in IE9+, Chrome and Firefox.



# Unit Tests

If you are applying for a regular or senior developer position, we would like to see unit tests for the main code paths in the application. Use the unit testing framework you feel most comfortable with.



# Evaluation

We want to see a functional and good looking, simple, maintainable and well organized application, that uses best practices for writing C#, JavaScript, HTML and CSS.

Any additional design or interaction features will be considered as a plus.

It is perfectly fine to use Team Pulse or similar tools for inspiration about the features and the design:

http://demos.telerik.com/teampulse-demo/
https://trello.com/








