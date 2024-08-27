
---

# The Ephemeral Pages

Welcome to **The Ephemeral Pages**, a beautifully crafted online store dedicated to the art of scrapbook journaling. This project aims to provide users with a seamless experience to explore, purchase, and learn about various scrapbooks, journaling supplies, and creative ideas for documenting their memories.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contribution](#contribution)
- [License](#license)

## Introduction

**The Ephemeral Pages** is an elegant online store offering a wide selection of scrapbooks, decorative items, and creative inspiration for scrapbook enthusiasts. Whether you are documenting your travels, preserving family memories, or simply indulging in a creative hobby, The Ephemeral Pages provides the perfect tools and resources for every project.

## Features

- **Beautiful, Responsive Design:** A modern and elegant user interface designed with mobile responsiveness in mind.
- **Product Listings:** Explore a wide range of scrapbooks, journaling supplies, and decorative elements with images, prices, and a "Buy Now" option.
- **Class Registration:** Users can log in and register for upcoming scrapbooking classes.
- **Secure Authentication:** User registration and login with password encryption.
- **Interactive Animations:** Button hover effects and dynamic content using anime.js.
  
## Installation

### Prerequisites

- Node.js and npm
- MySQL database

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/techchips/the-ephemeral-pages.git
   cd the-ephemeral-pages
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Configure the Database:**
   - Create a MySQL database and configure the connection in `config/db.js`.
   - Set up environment variables in a `.env` file:
     ```bash
     DB_HOST=localhost
     DB_USER=root
     DB_PASS=1234
     DB_NAME=ephemeral_pages
     JWT_SECRET=your_jwt_secret
     ```

4. **Run the Server:**
   ```bash
   node app.js
   ```
   The server should now be running on `http://localhost:5000`.

## Usage

- **Access the Website:** Once the server is running, open your browser and go to `http://localhost:5000`.
- **Explore Products:** Browse through the available scrapbooks and decorative elements.
- **Register/Login:** Create an account to register for classes.
- **Purchase Products:** Add products to your cart and proceed to checkout (e-commerce functionality may be implemented in a future version).

## Technologies Used

- **Frontend:**
  - HTML, CSS, JavaScript
  - Anime.js for animations
  - Responsive design with media queries
- **Backend:**
  - Node.js, Express.js
  - MySQL for data storage
  - Bcrypt.js for password hashing
  - JSON Web Tokens (JWT) for authentication

## Contribution

We welcome contributions! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

