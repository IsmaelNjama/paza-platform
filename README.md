How to Use
Follow these steps to set up the paza-platform services on your environment:

Clone the main repository
git clone https://github.com/IsmaelNjama/paza-platform.git

Navigate into the main directory
cd paza-platform

Create the necessary folders
Inside the paza-platform directory, create the following folders:

mkdir paza-frontend paza-backend paza-storage
Clone the individual repositories

Backend:
Navigate to the paza-backend folder and clone the backend repository:
cd paza-backend
git clone https://github.com/IsmaelNjama/paza-backend.git .

Frontend:
Navigate to the paza-frontend folder and clone the frontend repository:
cd ../paza-frontend
git clone https://github.com/rebeccawaweru/paza-frontend.git .

Storage:
Navigate to the paza-storage folder and clone the storage repository:
cd ../paza-storage
git clone https://github.com/IsmaelNjama/paza-storage.git .

Set up your environment
Each service requires environment variables to function correctly. Ensure you create and configure the .env files in each respective folder before running the services.

Run the services
After setting up the repositories and configuring the environment, navigate back to the paza-platform directory and run the services using Docker Compose:
cd ../paza-platform

docker compose up
The above command will start all the services.

Stop the services
To stop the running containers, use the following command:

docker-compose down
