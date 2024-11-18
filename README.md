# docker-setups

A collection of Docker Compose files for setting up various services and development environments with ease.

## How to Use

1. **Download the folder for the service you want to use (or copy the files)**  
   Each service setup is stored in its own folder. Navigate to the service you need and download or copy its contents.

2. **Copy the `.env.example` file to `.env`**  
   Inside the folder, duplicate the example environment file to `.env`:

   ```bash
   cp .env.example .env
   ```

3. **Configure environment variables**

   Open the .env file and update the required fields such as username, password, and other variables as per your setup.

4. **Build and start the containers**

   Run the following command to build and start the Docker containers:

   ```bash
   docker-compose up -d
   ```
