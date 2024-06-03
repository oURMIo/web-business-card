# Web Business Card

The "web-business-card" project is a digital business card platform. This project uses Docker Compose for application containerization, Nginx as a web server and reverse proxy, and Certbot for automatic SSL certificate acquisition and renewal, ensuring the service is secure and scalable.

## Technologies

- **Docker Compose**: For managing multi-container Docker applications.
- **Nginx**: As a web server and reverse proxy.
- **Certbot**: For automatic SSL certificate acquisition and renewal.

## Prerequisites

- Docker and Docker Compose installed on your machine.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/oURMIo/web-business-card.git
   cd web-business-card
   ```

2. Run the application:

   ```sh
   docker-compose up -d
   ```

3. Access the application:

   Open your web browser and navigate to `https://your-domain.com`.

## Configuration

- **Nginx Configuration**: The Nginx configuration file is located at `./data/nginx/app.conf`.
- **Certbot Configuration**: Certbot configuration in script sh at `./init-letsencrypt.sh`

## Usage

1. **Starting the service**:

   ```sh
   docker-compose up -d
   ```

2. **Stopping the service**:

   ```sh
   docker-compose down
   ```

## Acknowledgments

Special thanks to the following resources that helped make this project possible:

- [Article Title](https://pentacent.medium.com/nginx-and-lets-encrypt-with-docker-in-less-than-5-minutes-b4b8a60d3a71)
- [YouTube Video Title](https://youtu.be/EypjMCRZOrY?si=T0AEfkmzu94IOo6-)
