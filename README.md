# Connect

Connect is a web application similar to Linktree that allows users to create a personalized page containing links to their social media profiles, websites, and other online content. This project is built using modern web technologies to ensure a smooth and responsive user experience.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Working](#working)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization
- Create and manage a personalized profile with multiple links
- Responsive design for mobile and desktop
- Easy link management with drag-and-drop functionality

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript, React
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Hosting:** Vercel (or similar)

````sql


## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/mihir2004/connect.git
    cd connect
    ```
2. Install dependencies for both client and server:
    ```sh
    cd client
    yarn install
    cd ../server
    yarn install
    ```

## Usage
1. Start the server:
    ```sh
    cd server
    yarn start
    ```
2. Start the client:
    ```sh
    cd client
    yarn start
    ```
3. Open your browser and go to `http://localhost:3000` to see the application in action.

## Working
1. **User Registration and Login**: Users can register for an account and log in using their credentials. The application uses JWT for secure authentication.
2. **Profile Creation**: Once logged in, users can create a profile where they can add multiple links to their social media accounts, websites, or any other online resources.
3. **Link Management**: Users can easily add, update, and delete links through a user-friendly interface. The links can be reordered using a drag-and-drop feature.
4. **Public Profile**: Each user gets a unique URL that they can share, which displays their profile with all the links they have added.

## API Endpoints
### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Log in an existing user

### User Profile
- `GET /api/user/:id` - Get user profile by ID
- `PUT /api/user/:id` - Update user profile

### Links
- `GET /api/links/:userId` - Get all links for a user
- `POST /api/links` - Create a new link
- `PUT /api/links/:linkId` - Update a link
- `DELETE /api/links/:linkId` - Delete a link

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
````
