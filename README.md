# Blogify

A blogging platform built with Node.js, Express, and MongoDB. Users can create, read, update, and delete blog posts, as well as leave comments. Features user authentication and responsive design.

## Installation

To get started with Blogify, follow these simple steps:

1. **Install Dependencies:**
   ```bash
   npm install
   ```

2. **Set Up MongoDB:**
   - Ensure MongoDB is installed and running locally.
   - Update the connection URI in `config.js` if necessary.

3. **Start the Server:**
   ```bash
   npm start
   ```

## Usage

Blogify simplifies the process of blogging with its intuitive interface:

1. **Sign Up / Sign In:**
   - Access `/user/signup` to create a new account or `/user/signin` to log in.
   
2. **Explore Blogs:**
   - Visit the homepage (`/`) to discover a variety of blog posts.
   - Click on a post title to view its details, including comments.

3. **Create New Blogs:**
   - Authenticated users can share their insights by navigating to `/blog/add-new`.
   - Fill in the required fields and optionally upload a cover image.

4. **Engage with Comments:**
   - Leave comments on existing blog posts to engage with the community.
   - Scroll to the comment section at the bottom of each post.


## Folder Structure

- `middlewares/`: Houses middleware functions for tasks like authentication.
- `models/`: Contains Mongoose models for data entities like `Blog`, `Comment`, and `User`.
- `routes/`: Defines route handlers for different parts of the application.
- `services/`: Houses service files, such as authentication logic.
- `views/`: Holds EJS templates for rendering HTML pages.
- `public/`: Stores static assets like CSS, JavaScript, and images.
- `app.js`: Entry point of the Express application.
- `config.js`: Configuration file for environment variables and other settings.
- `package.json`: Metadata and dependencies for the Node.js application.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- EJS
- Bootstrap

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

