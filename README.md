# Deploy React to Vercel and Express to Render

This project demonstrates how to deploy a React frontend to Vercel and an Express backend to Render.

## Technologies Used

* React
* Vite
* Express.js
* Node.js
* Vercel
* Render
* Environment Variables
* GitHub

## Project Structure

```text
deploy-react-express/
├── client/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── server/
│   ├── server.js
│   ├── package.json
│   └── ...
│
└── .gitignore
```

## Features

* React frontend created with Vite
* Express backend API
* Environment variables using `.env`
* Sensitive files excluded using `.gitignore`
* React frontend prepared for Vercel deployment
* Express backend prepared for Render deployment
* Production environment variables verified

## Local Setup

### Frontend

```bash
cd client
npm install
npm run dev
```

### Backend

```bash
cd server
npm install
node server.js
```

The React application runs locally on port `5173`, while the Express server runs on port `5000`.

## Environment Variables

The backend uses environment variables such as:

```env
PORT=5000
NODE_ENV=development
```

The `.env` file is not uploaded to GitHub.

## Deployment

The React frontend can be deployed using Vercel.

The Express backend can be deployed using Render.

Production environment variables should be added directly in the Vercel and Render project settings instead of uploading `.env` files to GitHub.

## Learning Outcome

I learned how to prepare a full-stack React and Express project for production deployment, configure environment variables, use GitHub for source control, and deploy frontend and backend applications separately.
