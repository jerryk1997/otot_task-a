# OTOT Assignment Task A

# Task A

TASK: Deploy a simple web server using Nginx running in a Docker container.
LEARNING OBJECTIVE: To understand how containerization works and what its advantages are.
MARKING SCHEME:

● Demonstrate ability to write simple Dockerfile (1 mark)

● Setup Nginx and run a reverse proxy (1 mark)

● Demonstrate ability to use Docker Hub registry to keep track of
images (1 mark)

# Running the Task A

Downloading and opening project folder:

1. Clone this repository by using `git clone https://github.com/jerryk1997/otot_task-a.git`.
2. Navigate to the assignment submission directory by typing in `cd otot_task-a` if in root directory containing this folder

There are 2 websites available for testing, follow the instructions below to run them:
1. Once in the project root directory, navigate to the first website directory by using input `cd webservice1`.
2. Run the command `docker-compose build` to build the container followed by `docker-compose up -d` to run it.
3. Repeat steps 1 and 2 for webservice2. Note the difference is only in step 1, where you replace `webservice1` with `webservice2`.
4. Navigate back to the project root directory before running `cd proxy` to navigate to the reverse proxy directory
5.Run the command `docker-compose build` to build the container for the reverse proxy followed by `docker-compose up -d` to run it.
6. You are now ready to access the website! To access website 1 type ` http://localhost/thisone` into the browser, 
and to access website 2, type ` http://localhost/thatone` into the browser.
7. To stop running all containers, type `docker stop [CONTAINER_NAME]` for each of the containers you created.
