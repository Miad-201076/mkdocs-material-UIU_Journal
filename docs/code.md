# System Architecture
## MVT Design Pattern

Our project utilizes the Model-View-Template (MVT) architecture, a well-established design pattern employed in the development of web applications. This methodology emphasizes the segregation of concerns, contributing to the creation of code that is more organized and easily maintainable. Below is a concise overview of each constituent element:

### Model Component

- Involves the data structure and business logic integral to the application.
- Specifies the database schema via models, implemented as Python classes.
- Interacts with the database to execute CRUD (Create, Read, Update, Delete) operations.

### View Component

- Manages the user interface and processing of user inputs.
- Retrieves data from the Model and conveys it to the Template.
- Encompasses the application's business logic pertinent to user interactions.

### Template Component

- Defines the presentation layer and outlines the structure of the output.
- Utilizes Django's template language for the dynamic generation of HTML.
- Accepts data from the View and renders it to present information to the user.

<br>

