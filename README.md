# DALL-E-2.0-Image-Generation-Back-End

This application utilizes OpenAI's DALL-E 2 API to generate images based on user prompts. The backend is built with Node.js, Express.js, Cloudinary for image upload and MongoDB with Mongoose.

# Features

- Generate unique images by providing a prompt
- Share generated images with the community
- Download generated images to your device

# Getting Started

## Prerequisites

- Node.js
- MongoDB
- Cloudinary account
- OpenAI API key

## Installation

1. Clone the repository

```
git clone https://github.com/BraveHeart-tex/DALL-E-2.0-Image-Generation-Back-End
```

2. Install dependencies

```
npm install or yarn add
```

3. Create a .env file in the root directory with the following variables

```
MONGODB_URL="YOUR URL"
OPENAI_API_KEY="YOUR KEY"
CLOUDINARY_CLOUD_NAME="YOUR CLOUD NAME"
CLOUDINARY_API_KEY="YOUR API KEY"
CLOUDINARY_API_SECRET="YOUR API SECRET"
```

4. Start the application

```
npm start
```

## API endpoints

- /api/v1/post (GET) : Get the created posts
- /api/v1/post (POST): Create a new community post based on the prompt.
- /api/v1/dalle (POST): Generate a new image with the given prompt.

## Built With

- Node.js
- Express.js
- Cloudinary
- MongoDB
- Mongoose

# Note

This is the backend part of the project. make sure you have the frontend part of the project running as well in order to interact with this backend. You can find the frontend repository <a href="https://github.com/BraveHeart-tex/DALL-E-2.0-Image-Generation-Front-End" _blank>here</a>
