# **Express Blog Application**
This is a simple blog application built using Express.js and MongoDB. It allows users to create, read, update, and delete blog posts.

## Prerequisites
Before running this application, make sure you have the following installed:

Node.js
MongoDB
## Installation
Clone the repository or download the source code.
Navigate to the project directory in your terminal.
Install the required dependencies by running the following command:
Copy code
npm install
## Configuration
Open the app.js file in a text editor.
Modify the MongoDB connection URL (mongodb://127.0.0.1:27017/postDB) if necessary to match your MongoDB configuration.
Save the changes.
## Usage
Start the application by running the following command:
Copy code
node app.js
Open your web browser and visit http://localhost:3000 to access the blog.
## Routes
/: Displays the home page with a list of all blog posts.
/about: Displays information about the blog.
/contact: Displays contact information.
/compose: Allows users to compose a new blog post.
/posts/:post: Displays a specific blog post based on the provided post title.
## File Structure
app.js: Main application file containing the Express server setup and route definitions.
views/: Directory containing the EJS templates for rendering the views.
home.ejs: Template for the home page.
about.ejs: Template for the about page.
contact.ejs: Template for the contact page.
compose.ejs: Template for composing a new blog post.
post.ejs: Template for displaying a specific blog post.
public/: Directory for serving static files such as CSS and images.
models/: Directory containing the Mongoose schema and model definition for the blog posts.
## Contributing
Contributions to this project are welcome. Feel free to submit bug reports, feature requests, or pull requests.
