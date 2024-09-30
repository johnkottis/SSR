# React SSR Project

This is a simple Server-Side Rendering (SSR) project using React and Express.js.

## Features
- **Server-Side Rendering (SSR)**: The React components are rendered on the server, providing better performance and SEO.
- **Express Server**: A lightweight server using Express to serve the rendered HTML and static assets.
- **Webpack for Bundling**: Client-side React code is bundled using Webpack.

## Project Structure
```
.
├── public
├── src
│   ├── App.js
│   └── index.js
├── server.js
├── webpack.config.js
└── package.json
```

## Setup Instructions

### 1. Install dependencies
Make sure you have Node.js installed. Run the following command to install the required dependencies:

```bash
npm install
```

### 2. Build the React app
Use Webpack to build the React application:

```bash
npm run build
```

### 3. Start the server
After building the React app, you can start the Express server:

```bash
npm start
```

The server will be running on `http://localhost:3000`.

### 4. Access the app
Visit `http://localhost:3000` in your browser to see the server-side rendered React app.

## Notes
- This project uses basic server-side rendering to render React components.
- Further enhancements can be made for routing, data fetching, and other advanced SSR features.

Enjoy!
