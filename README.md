# GitFolio
This is a MERN stack application from the "MERN Stack Front To Back" . It is a small social network app that includes authentication, profiles and forum posts.
Quick Start rocket
Add a default.json file in config folder with the following
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
Install server dependencies
npm install
Install client dependencies
cd client
npm install
Run both Express & React from root
npm run dev
Build for production
cd client
npm run build
