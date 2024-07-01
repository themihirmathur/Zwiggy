# Zwiggy | Food Delivery Web Application using Microservice Architecture 🛵🍱

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

Welcome to Zwiggy, an open-source Food Delivery Web Application designed using Microservice Architecture. This comprehensive project aims to provide a robust and scalable solution for food delivery services, catering to various user roles including Admins, Users, Restaurant Owners, and Delivery Personnel. The project is freely accessible, and this README introduces the initial phase, with further developments to follow.

![Screenshot 2024-07-01 at 2 17 22 PM](https://github.com/themihirmathur/Zwiggy/assets/92594107/93588cc8-dcfb-47ee-ab5c-9aeb0e4f9c2a)

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Project Overview

Zwiggy is structured to handle the complexities of a food delivery platform through a modular approach. Each role-specific application operates as an independent microservice, ensuring scalability, maintainability, and efficient development. 

### Key Features:
- **Admin Panel**: Manage users, restaurants, orders, and system settings.
- **User Interface**: Browse restaurants, place orders, track deliveries.
- **Restaurant Owner Dashboard**: Manage menus, orders, and delivery status.
- **Delivery Personnel App**: View delivery assignments, update delivery status.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Open for Contributors

We invite developers to contribute to Zwiggy. Whether you aim to modify specific aspects or collaborate on the entire project, your assistance is invaluable. Prior experience is not mandatory; if you have frontend development skills, you are welcome to join.

### Contribution Guidelines:
- Fork the repository
- Create a new branch (`git checkout -b feature-branch`)
- Commit your changes (`git commit -m 'Add new feature'`)
- Push to the branch (`git push origin feature-branch`)
- Open a pull request

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Technology Stack

Given the Microservice Architecture, our tech stack is designed for flexibility and performance. Below is an overview of the primary technologies we plan to use:

### Backend:
- **Nest.js**: As the backend framework, providing a robust and scalable server-side application.
- **GraphQL**: For API gateway and efficient microservice communication.
- **Docker**: Containerization to ensure consistency across different environments.
- **Prisma**: Database ORM for seamless data management.
- **AWS ECS**: Deployment using Amazon's Elastic Container Service, along with other AWS services for scalability and reliability.

### Frontend:
- **Next.js**: For building fast, SEO-friendly, and highly optimized web applications.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Getting Started

To get started with Zwiggy, follow these steps:

### Prerequisites:
- Node.js
- Docker
- AWS account (for deployment)
- Prisma (for database management)

### Installation:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/themihirmathur/Zwiggy.git
   cd Zwiggy
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up Docker:**
   Ensure Docker is installed and running on your machine. Build and run the Docker containers:
   ```bash
   docker-compose up --build
   ```

4. **Run Prisma Migrations:**
   ```bash
   npx prisma migrate dev
   ```

5. **Start the Application:**
   ```bash
   npm run start
   ```

### Deployment:

Deploy the application using AWS ECS:
- Set up your AWS account and configure ECS.
- Push Docker images to AWS ECR.
- Create ECS tasks and services to manage your containers.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Roadmap

This project is in its initial phase, and future updates will include:
- Advanced user authentication and authorization
- Real-time order tracking and notifications
- Enhanced restaurant management features
- Performance optimizations and security enhancements

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Acknowledgements

We appreciate the contributions from developers worldwide. Special thanks to all open-source projects and libraries that have made this project possible.

---

Feel free to contribute, suggest improvements, or raise issues. Together, we can build an exceptional food delivery platform!

For more details, contact [Mihir Mathur](mailto:themihirmathur@gmail.com).
