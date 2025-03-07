# Think Out Loud - Online Blog

Think Out Loud is an online blog application built with **Next.js**, **MySQL**, **UploadThing**, and **NextAuth**. It allows users to log in using their Google account, create and view blog posts, and store media files using UploadThing.

## Features
- **Google Authentication** via NextAuth.js
- **Blogging Platform** to create, read, and manage blog posts
- **Media File Uploads** using UploadThing
- **MySQL Database** powered by **Neon Tech**
- **Deployed on Vercel** for easy access and scalability

**Test App**: This is a test app and has not yet been verified by Google. You can access the deployed version here: [Think Out Loud Blog](https://tol-blog.vercel.app/).


## Installation

To get started with this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/Dohaelm/TOL--Blog.git
```
### 2. Create .env file
Create a .env file at the root of the project and fill in the following details:
```bash
DATABASE_URL=your-database-url
NEXTAUTH_SECRET=your-nextauth-secret
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
UPLOADTHING_TOKEN=your-uploadthing-token
REDIS_URL=your-redis-url
REDIS_SECRET=your-redis-secret
```
### 3. Install dependencies 
```bash
npm install
```
### 4. Start server ! 
```bash
npm run dev 
```




