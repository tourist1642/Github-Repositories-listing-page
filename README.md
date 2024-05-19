### Github Repositories Listing Page

This project is an Angular 14+ single-page application (SPA) designed to take a GitHub username as input and display the public GitHub repositories belonging to that user.

#### Deployment Link
You can view the deployed application at [Github Repositories Listing Page](https://elegant-bartik-2a54a3.netlify.app).

### Prerequisites
Make sure you have Node.js and Angular CLI installed on your system.

### Getting Started

#### 1. Clone the Repository
Clone the repository to your local machine using the following command:
```sh
git clone https://github.com/tourist1642/github-repositories-listing-page.git
cd github-repositories-listing-page
```

#### 2. Install Dependencies
Install the necessary dependencies using npm:
```sh
npm install
```

#### 3. Development Server
Run the following command to start the development server:
```sh
ng serve
```
Navigate to `http://localhost:4200/` in your browser. The app will automatically reload if you change any of the source files.

### Application Structure

#### User Input
The app takes a GitHub username as input through a form. When the form is submitted, it fetches the public repositories of the given username using the GitHub API.

#### Display Repositories
The repositories are displayed in a list format, showing essential details such as the repository name, description, and the number of stars.

### Code Scaffolding
To generate new components, directives, pipes, services, classes, guards, interfaces, enums, or modules, use the Angular CLI command:
```sh
ng generate component component-name
```
or
```sh
ng generate directive|pipe|service|class|guard|interface|enum|module
```

### Build
To build the project, run:
```sh
ng build
```
The build artifacts will be stored in the `dist/` directory. For a production build, use the `--prod` flag:
```sh
ng build --prod
```

### Running Tests

#### Unit Tests
To execute the unit tests via Karma, run:
```sh
ng test
```

#### End-to-End Tests
To execute the end-to-end tests via Protractor, run:
```sh
ng e2e
```

### Further Help
For more help on the Angular CLI, use the `ng help` command or refer to the [Angular CLI README](https://github.com/angular/angular-cli/blob/main/README.md).

### Conclusion
This Angular SPA allows users to input a GitHub username and retrieve a list of public repositories for that user. The application leverages Angular's powerful features to provide a seamless user experience and interact with the GitHub API.

For further assistance or contributions, feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/tourist1642/github-repositories-listing-page).
