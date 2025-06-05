# Dockerizing a WordPress site

This project demonstrates how to set up a WordPress site using Docker and Docker Compose. It provides a complete development environment with a MySQL database, enabling easy deployment and management of the WordPress application.

## Features

- **Containerization**: Encapsulates the WordPress application and its dependencies within Docker containers.
- **Database Support**: Integrates MySQL as the database backend for data persistence and scalability.
- **Easy Setup**: Simplifies the installation process with a single `docker-compose.yml` file.
- **Customizable**: Easily configurable environment variables for database credentials and WordPress settings.
- **Volume Management**: Uses Docker volumes to persist data across container restarts.

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.
- [Docker Compose](https://docs.docker.com/compose/install/) installed.

### Installation

### 1. Clone the repository:

   ```
   git clone https://github.com/yourusername/dockerized-wordpress.git
   cd dockerized-wordpress
   ```

### 2. Start the containers:

```
docker-compose up
```

![Project6a](https://github.com/user-attachments/assets/9898f907-fefc-467f-be2c-bda395b9da3b)


Access your WordPress site at [http://localhost:8000](http://localhost:8000) (or your specified port).

![Project6](https://github.com/user-attachments/assets/e96e2a2c-fe3a-4891-9647-f57dbd7e2afe)
![Project6b](https://github.com/user-attachments/assets/db7f1ee9-0984-4c15-89f2-b8b28799e4b5)

### Stopping the Containers
To stop the running containers, use:

```
docker-compose down
```

### Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions.

### License
This project is licensed under the MIT License 

 

