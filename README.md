# Redis Compose

This repository contains a Docker Compose configuration for running Redis.

## Prerequisites

Before running the Redis containers, make sure you have the following installed:

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/)

## Usage

1. Clone this repository:

    ```shell
    git clone https://github.com/your-username/redis-compose.git
    ```

2. Navigate to the cloned repository:

    ```shell
    cd redis-compose
    ```

3. Start the Redis containers:

    ```shell
    docker-compose up -d
    ```

    This command will start Redis in detached mode.

4. Verify that the Redis containers are running:

    ```shell
    docker-compose ps
    ```

    You should see the Redis containers listed with their status.

5. Connect to Redis:

    You can now connect to Redis using your preferred Redis client. The default Redis port is `6379`.

6. Stop the Redis containers:

    ```shell
    docker-compose down
    ```

    This command will stop and remove the Redis containers.

## Configuration

You can customize the Redis configuration by modifying the `redis.conf` file in the `config` directory.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
