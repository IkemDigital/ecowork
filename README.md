# Ecowork

**Ecowork** is an innovative platform aimed at connecting freelancers across Africa with clients both within the continent and around the world. Our mission is to create a vibrant ecosystem where talented freelancers can showcase their skills, and businesses can easily find the right professionals to meet their needs.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Frontend](#frontend)
- [Backend](#backend)
- [Hosting](#hosting)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Features

- Connect with a diverse pool of freelancers across various industries.
- User-friendly interface for both freelancers and clients.
- Robust search functionality to find talent easily.
- Secure messaging system for seamless communication.

## Technologies Used

- **Next.js**: A powerful React framework that enables server-side rendering, static site generation, and API routes. Next.js provides great performance and SEO benefits, making it an excellent choice for building modern web applications.

- **Strapi**: An open-source headless CMS that makes it easy to manage your content and build APIs quickly. Strapi offers a user-friendly admin panel and allows for flexible content types, making it a perfect fit for our backend.

## Frontend

The frontend of Ecowork is built using **Next.js**.

### Getting Started with the Frontend

1. Clone the repository:
   `bash`
   git clone <repository-url>
   cd ecowork-frontend
   npm install
   npm run dev

Open your browser and navigate to http://localhost:3000 to see the application in action.

### Backend

The backend of Ecowork is powered by Strapi.

### Getting Started with the Frontend

    cd ecowork-backend
    npm install
    npm run develop

# Hosting

Ecowork is currently hosted on an Oracle Server, providing a reliable infrastructure for our application. We have configured Nginx as a reverse proxy to serve our frontend and backend applications efficiently.
Nginx Configuration

Nginx helps manage incoming traffic, serving static files and routing API requests to the Strapi backend.

    For detailed Nginx configurations, refer to the nginx.conf file in the root directory.

# DNS Configuration

We utilize Cloudflare as our DNS provider to ensure fast and secure access to our web application. Cloudflare provides a robust suite of security features, including DDoS protection and SSL encryption.
Getting Started

To get started with Ecowork, clone the repository and set up both the frontend and backend as described in the sections above. Ensure you have Node.js installed on your machine to run the applications.
Contributing

We welcome contributions to make Ecowork better! If you would like to contribute, please follow these steps:

    Fork the repository.
    Create a new branch (git checkout -b feature/YourFeature).
    Make your changes and commit them (git commit -m 'Add some feature').
    Push to the branch (git push origin feature/YourFeature).
    Open a pull request.

# License

This project is licensed under the MIT License. See the LICENSE file for details.
