# Blog Website

This is a blog web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to create, view, and manage blog posts effectively.

## Features

- **Home Page:** Displays a list of blog posts sorted by date, with the latest posts appearing first.
- **Post Management:** Users can compose new posts, view individual posts, and delete posts.
- **Navigation:** Includes a navbar with links to the Home, About, Compose, and Contact pages.
- **Responsive Design:** The application is responsive and works well on various devices.

## Prerequisites

Before running the application, make sure you have the following installed:

- Node.js
- MongoDB Atlas account or a local MongoDB server running

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/blog.git
   cd blog

2. **Install dependencies:**

    npm install

3. **Set up MongoDB:**

    - Create a MongoDB Atlas account if you don't have one.
    - Replace the MongoDB connection string in app.js with your MongoDB URI.

## Running the Application

To start the server, run:

    node app.js

The server will start running at http://localhost:3000.

## Usage

**Navigation**
    
    - Home: Navigate to http://localhost:3000 to view all blog posts.
    - About: Visit http://localhost:3000/about to learn more about the blog.
    - Compose: Access http://localhost:3000/compose to create a new blog post.
    - Contact: Reach http://localhost:3000/contact for contacting the blog owners 
    
**Compose a New Post**

Navigate to http://localhost:3000/compose to compose a new post:

    - Enter the title and content of the post in the respective fields.
    - Click the "Publish" button to create the post.

**View Posts**

    - Visit the home page at http://localhost:3000 to view all blog posts.
    - Each post summary includes a "Read More" link to view the full post.

**Delete a Post**

    - To delete a post, click on the post title to view the full post.
    - Click the "Delete" button at the bottom of the post to remove it.