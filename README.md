# EJS Node.js Project Template

This repository provides a base template for a Node.js project using EJS as the templating engine. It includes a basic structure with essential files and directories for setting up a web application.

## Project Structure

```
│   .gitignore
│   app.js
│   home.html
│   index.html
│   package-lock.json
│   package.json
│   README.md
├───public
│   ├───css
│   │       styles.css
│   │
│   └───images
└───views
    │   about.ejs
    │   contact.ejs
    │   index.ejs
    │   projects.ejs
    │
    └───partials
            footer.ejs
            header.ejs
```

### Files and Directories

-   **app.js**: The main server file where the Express app is configured and started.
-   **home.html, index.html**: Static HTML files for basic front-end content.
-   **package.json, package-lock.json**: Files that manage the project's dependencies.
-   **public**: Contains static assets such as CSS files and images.
    -   **css/styles.css**: Custom styles for the application.
    -   **images/**: Directory for storing image assets.
-   **views**: EJS templates for dynamic rendering.
    -   **about.ejs, contact.ejs, index.ejs, projects.ejs**: Individual pages for the application.
    -   **partials**: Reusable EJS components like headers and footers.

## Setup Instructions

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/repository-name.git
    ```

2. **Navigate into the project directory**:

    ```bash
    cd repository-name
    ```

3. **Install dependencies**:

    ```bash
    npm install
    ```

4. **Start the server**:

    ```bash
    npm start
    ```

    The server should now be running at `http://localhost:3000`.

## Usage

-   Modify the EJS files in the `views` directory to update the templates.
-   Add new CSS files or images to the `public` directory as needed.
-   Update `app.js` for additional routes and middleware.

## Contributing

Feel free to fork this repository and contribute by submitting a pull request. Please ensure your changes are well-documented.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
