# Node.js Docker Workflow Documentation

This project includes a Docker setup for a Node.js application. The following documentation provides a visual guide through the series of tasks completed, with screenshots for each step.

## Workflow Steps and Screenshots

### Task 1: Create a Docker Image with Node.js Installed

- **[1.png](https://github.com/Amaanvahora/Exam-4034/blob/main/1.png)** - Shows the Dockerfile with Node.js specified as the base image.

### Task 2: Add a Tag to the Image

- **[3.png](https://github.com/Amaanvahora/Exam-4034/blob/main/3.png)** - Demonstrates the Docker image being built with the tag `docker-4034:v1.0`.

### 3: Run a Container Based on the Image

- **[Task 3](https://github.com/Amaanvahora/Exam-4034/blob/main/4.png)** - Illustrates the command to run the Docker container from the image, mounting the current directory as a volume.

### Task 4: Update the Dockerfile to Accept Volume

- **[5.png](https://github.com/Amaanvahora/Exam-4034/blob/main/5.png)** - Displays the updated Dockerfile with the `VOLUME` instruction.

### Task 5: List the Docker Volume

- **[6.png](https://github.com/Amaanvahora/Exam-4034/blob/main/6.png)** - Shows the output of `docker volume ls`, listing the volumes created.

### Task 6: Exec into the Container and Create a File in the Volume

- **[7.png](https://github.com/Amaanvahora/Exam-4034/blob/main/7.png)** - Provides evidence of exec-ing into the container and creating a file in the mounted volume.

### Task 7: Ensure File Persists in Volume

- **[8.png](https://github.com/Amaanvahora/Exam-4034/blob/main/8.png)** - Confirms that the file created in the volume persists even after the container is pulled down.

---

