# Project Tour


* .gitignore: This file specifies intentionally untracked files that Git should ignore.

* First.png, Second.png, Third.png: These are image files. They might be used as assets in your project, such as logos or illustrations.

* package-lock.json: This file is automatically generated for any operations where npm modifies either the node_modules tree or package.json. It locks the version of each package that is installed.

* package.json: This file holds various metadata relevant to the project. This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.

* README.md: This is the README file for your project. It typically contains information about the project, how to set it up, how to contribute, and any other relevant details.

* tailwind.config.js: This file is used to configure Tailwind CSS, a utility-first CSS framework for rapidly building custom designs.

* public: This folder contains static assets like HTML files, images, and the favicon for your project.

* src: This folder contains the source code for your project.

* App.css, index.css: These are CSS files for styling your React components.

* App.js, index.js: These are JavaScript files that serve as the entry points for your React application.

* Components: This folder contains sub-components or modules of your application, organized by functionality. In this case:

* Cars: Contains files related to displaying information about cars.

* Currency: Contains files related to currency conversion.

* Home: Contains files related to the home page.

* IMDB: Contains files related to fetching and displaying information from the IMDB API.

* Navbar: Contains files related to the navigation bar component.

This structure seems to be for a web application that provides information about cars, currency conversion, and IMDB data, with a navigation bar for easy navigation between different sections of the application.







* notes:
*  - 1: The component folder would contain all the different user made components.
* - 2: All folders other than the Home and Navbar would contain a file, where one would use the 'axios.create()' method on the API and export it to the other folder, where it would be fetched.
* - 3: The home page folder would contain the home page component.
* - 4: The navbar folder would contain the navbar component.
* - 5: Note that strongly recommend the contributor to make more files in these folders and use atomic component to 'increase code readability'.
* - 6: Note that the contributor should use 'axios.create()' to fetch the API as it would be more suitable in fetching the given API.


## Tech Stack

* Reactjs and Tailwind CSS(Without this is also ok).


