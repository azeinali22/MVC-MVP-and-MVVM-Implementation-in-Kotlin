# Introduction
In software development, Model-View-Controller (MVC), Model-View-Presenter (MVP), and Model-View-ViewModel
(MVVM) are the three architectural patterns which are used frequently.
* MVC (Model-View-Controller)
MVC is a design pattern that separates the application into three components. The Model manages the data and
business logic, the View is responsible for the user interface, and the Controller handles user input and updates the
Model and View.
* MVP (Model-View-Presenter)
MVP is a derivative of MVC that emphasizes a more decoupled approach. In MVP, the Presenter replaces the
Controller. It handles user interactions by processing inputs from the View, updating the Model, and pushing data
back to the View, making the View passive and focused on display logic.
* MVVM (Model-View-ViewModel)
MVVM is another architectural pattern designed primarily for data-binding frameworks. It allows for a more reactive
approach where the ViewModel holds the presentation logic and transforms data from the Model into a format
that the View can easily consume. MVVM eliminates the need for a Controller or Presenter, as the View binds
directly to the ViewModel’s properties, which updates the UI when the data changes automatically.
# Overview of the Application
The application designed as a simple counter-app that demonstrates the implementation of MVC, MVP, and
MVVM architectural patterns. This application mainly intended to highlight the differences and similarities of
these architectural styles rather than focus on complex functionality.

Click on Link to watch the screen recording of application:\
https://drive.google.com/file/d/15KPTLrcl_8PLAD2GXiQteqJakVvfzIxG/view?usp=sharing
