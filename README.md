Create an application with Angular2 with the following capabilities:

1 text box, 1 search button

Entering the "3rd" letter in the text box, make a service call to get matching suggestions and render the suggestion in the textbox overlay

Display a message "select from typeahead" when the user clicks on Search button without making a selection from the textbox suggestions

Display results on click of the search button when the user made a selection from the textbox suggestions

Display a spinner while the search results are retrieved

Provide a back link in the results page and when the user clicks on the results page take him back to the landing page with the entered keyword populated in the textbox

Cache the keyword in Session 

Store a cookie in the Browser


Assumption:

Create a mock service to render the json for both suggestions and results. The json must contain a body with meta-data and result section. 

Inject the service in the Components

Generic logging framework to log all debugging statements

Generic exception handling framework for the angular components and display "error messages"
