# AI Image Generator (MERN)

A full stack AI image generation web app built using the MERN stack. Users can generate images from text prompts, explore a gallery, and experiment with random prompts.

---

## Features

- Generate images from text prompts using AI
- Supports concurrent image generation up to 5 prompts
- Community gallery to view generated images
- Random prompt generator for inspiration
- Download generated images
- Responsive UI built with React
- Backend secured using environment variables
- Rate limiting to prevent API abuse

---

## Tech Stack

Frontend:
- React (Vite)
- Axios

Backend:
- Node.js
- Express.js
- MongoDB

AI:
- Hugging Face Stable Diffusion API

---

## How It Works

User -> React UI -> Express API -> Hugging Face -> Image -> MongoDB -> Gallery

1. User enters a prompt or uses random generator
2. Frontend sends request to backend
3. Backend calls Hugging Face model
4. Image is generated and returned as base64
5. Image is displayed and optionally stored
6. Gallery shows generated images

---

ヽ✿ by Sanvi Mahajanヽ✿
