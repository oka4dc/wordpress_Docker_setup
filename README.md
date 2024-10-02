# wordpress_Docker_setup

# WordPress with MySQL using Docker Compose

This project sets up a **WordPress** environment powered by **MySQL** using Docker and Docker Compose. The setup allows you to easily deploy WordPress with a persistent MySQL database and WordPress files.

## Project Structure

```bash
wordpress-mysql/
│
├── docker-compose.yml   # Docker Compose file that defines services
└── db_data/             # Directory to store MySQL data
└── wp_data/             # Directory to store WordPress data
docker-compose up # to start

docker-compose down # tostop