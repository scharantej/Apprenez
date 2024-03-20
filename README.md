## Flask Application Design for Building a French Language Learning Site for MBA Graduates

### HTML Files

- **index.html**: This will serve as the homepage of the website, providing an overview of the site's purpose and features. It will contain links to other pages and resources.
- **lessons.html**: This page will host the French language lessons specifically tailored for MBA graduates. It will include interactive exercises, vocabulary lists, and grammar explanations.
- **resources.html**: This page will provide supplementary materials such as downloadable PDFs, audio files, and links to external resources that support the learning process.

### Routes

- **`@app.route("/")`**: The route for the homepage, which displays the content of `index.html`.
- **`@app.route("/lessons")`**: The route for the lessons page, which displays the content of `lessons.html`.
- **`@app.route("/resources")`**: The route for the resources page, which displays the content of `resources.html`.
- **`@app.route("/login")`**: The route for a potential login page, if user authentication is desired.
- **`@app.route("/register")`**: The route for a potential registration page, if user registration is required.