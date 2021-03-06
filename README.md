# Udacity FEND Course
## Project 5: Restaurant Reviews

[See it live here!](https://stevenremenapp.github.io/reviews/)

### Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### Access Project

Access this project by downloading or cloning the master branch and starting a localhost server in the root folder using port 8000 (I used python to do this, but I'm sure there are other ways). Then go to that localhost address in your browser.

### Items Added/Updated

Responsiveness:

-   Media queries and appropriate styling so the web app looks good on any size screen
-   Flexbox added where necessary to make individual page items most attractive and responsive

Accessibility:

-   Alt text added to images via JavaScript
-   Keyboard accessibility added to map markers (links will work when Enter key is selected on map marker)
-   Added "map marker" to the alt text for the map marker images to make it clearer for screen reader users
-   Added role=application to all maps
-   Moved the Leaflet map attribute links to the top right so they are never hidden from the user
-   Corrected breadcrumb to follow accessibility best practices
-   Added aria-label to links in the header and footer to make them clearer for screen reader users
-   Added a clearer aria-label ("view details of this restaurant") to the 'View Details' links
-   Corrected semantic heading levels on all HTML pages to follow h1 -> h3 appropriately

Service Worker:

-   Added a service worker script to cache assets of this web app

Hosting:

-   Adjusted pathnames throughout the files so that the project could be correctly hosted on Github pages.

### Acknowledgements

Many thanks to the Udacity community for helping me complete this project!
