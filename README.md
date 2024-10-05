# OWASP Juice Shop Installation Guide

OWASP Juice Shop is an intentionally insecure web application for security training, awareness demos, and CTFs. Follow the steps below to install and run Juice Shop using Docker Compose.

## Prerequisites

Before you begin, make sure you have the following installed on your system:

- [Git](https://git-scm.com/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Installation Steps

### 1. Clone the Repository

Start by cloning the Juice Shop repository to your local machine using the following command:

```bash
git clone https://github.com/nurlanchip/juiceshop.git
```

### 2. Start Juice Shop using Docker Compose

Navigate to the newly cloned directory and bring up the application using Docker Compose:

```bash
cd juiceshop
docker compose up -d
```

This command will pull the necessary Docker images and start the Juice Shop application in detached mode.

### 3. Access Juice Shop

Once the containers are running, open your web browser and go to:

```
http://<ip-address>:3000
```

Replace `<ip-address>` with your local machine's IP address or `localhost` if you're running Docker on your local machine.

## Stopping the Application

To stop the application, run the following command:

```bash
docker compose down
```

## Additional Resources

- [Official Juice Shop Documentation](https://owasp.org/www-project-juice-shop/)
- [OWASP Juice Shop GitHub Repository](https://github.com/juice-shop/juice-shop)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
