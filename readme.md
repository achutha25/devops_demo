In this assignment, I created a Python project and containerized it using Docker. I then set up a GitHub Actions workflow to implement a CI/CD pipeline that automatically runs tests, builds a Docker image, and pushes it to Docker Hub. The workflow was split into two jobs: one for testing the code using pytest, and another for building and pushing the image if the tests pass. To securely authenticate with Docker Hub, I stored my Docker credentials as GitHub Secrets. I configured the Dockerfile, requirements.txt, and main.py to work with both the local environment and the Docker container. Finally, I verified the successful image push by checking my Docker Hub repository and documented the process with screenshots in the README.




## Docker Hub Repo Screenshots

![Docker Hub pushed image] (images/img1.png)
