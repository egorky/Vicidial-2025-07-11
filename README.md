# Vicidial Tailwind CSS Refactor

This project is a refactoring of the Vicidial agent interface to use Tailwind CSS for a more modern and responsive design.

## How to Build and Run

1.  **Install Dependencies:**

    Make sure you have Node.js and npm installed. Then, run the following command in the root of the project to install the necessary dependencies:

    ```
    npm install
    ```

2.  **Build the CSS:**

    To build the Tailwind CSS file, run the following command:

    ```
    npm run build:css
    ```

    This will generate the `tailwind_styles.css` file in the `www/agc/css` directory. The build process will continue to watch for changes in the input files and automatically rebuild the CSS.

3.  **Run the Application:**

    This project is a PHP application, so you'll need a web server with PHP support (like Apache or Nginx) to run it. Configure your web server to serve the `www` directory as the document root.

    Once the server is running, you can access the agent interface by navigating to `http://<your-server>/agc/vicidial.php` in your web browser.


That's it! You should now see the new and improved Vicidial agent interface.
