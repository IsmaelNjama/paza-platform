# paza-platform

## How To Use

## Note
  Before proceeding, ensure you have Docker Engine installed and running on your system:
  Windows and WSL Users: Ensure Docker Desktop is installed and running

1. Clone the main repository

```bash
git clone https://github.com/IsmaelNjama/paza-platform.git
```

2. Navigate into the main directory

```bash
cd paza-platform
```

3. Create the necessary folders
   Inside the paza-platform directory, create the following folders:

```bash
mkdir paza-frontend paza-backend paza-storage
```

4. Clone the individual repositories

Backend:
Navigate to the paza-backend folder and clone the backend repository:

```bash
cd paza-backend
git clone https://github.com/IsmaelNjama/paza-backend.git .
```

Frontend:
Navigate to the paza-frontend folder and clone the frontend repository:

```bash
cd ../paza-frontend
git clone https://github.com/rebeccawaweru/paza-frontend.git .
```

Storage:
Navigate to the paza-storage folder and clone the storage repository:

```bash
cd ../paza-storage
git clone https://github.com/IsmaelNjama/paza-storage.git .
```

5. Set up your environment
   Each service requires environment variables to function correctly. Ensure you create and configure the .env files in each respective folder before running the services.

6. Run the services
   After setting up the repositories and configuring the environment, navigate back to the paza-platform directory and run the services using Docker Compose:

```bash
cd ../paza-platform
docker compose up
```

The above command will start all the services.

7. Stop the services
   Use the following command:

```bash
docker compose down
```
