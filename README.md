# Quora Posts RESTful App

A simple Express.js application to create, view, edit, and delete "Quora-style" posts.  
Built with Node.js, Express, EJS, and method-override.

## Features

- View all posts
- Create a new post
- Edit an existing post
- Delete a post
- View a single post

## Tech Stack

- Node.js
- Express.js
- EJS (Embedded JavaScript templates)
- method-override (for supporting PATCH/DELETE in forms)
- UUID (for unique post IDs)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/quora-rest-app.git
    cd quora-rest-app
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    node index.js
    ```

4. Open your browser and go to:
    ```
    http://localhost:8080/posts
    ```

## Project Structure

```
REST_CLASS/
├── index.js
├── package.json
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   ├── edit.ejs
│   ├── show.ejs
│   └── includes/
│       ├── header.ejs
│       └── footer.ejs
└── public/
```

## Usage

- **View all posts:** `/posts`
- **Add a post:** `/posts/new`
- **View a post:** `/posts/:id`
- **Edit a post:** `/posts/:id/edit`
- **Delete a post:** Use the delete button on the post

## License

MIT
