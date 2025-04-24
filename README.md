# 2048 Docker Game

A clone of the popular 2048 game, containerized using Docker and deployed on AWS using Elastic Beanstalk.

##  Technologies Used

- HTML, CSS, JavaScript
- Docker
- Nginx
- AWS Elastic Beanstalk

##  Run Locally with Docker

```bash
docker build -t 2048-game .
docker run -d -p 80:80 2048-game
