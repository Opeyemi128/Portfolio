## My Portfolio Website

    My portfolio website was developed to showcase my skills, experience and project works.

### Overview

This project demonstrates how to deploy a portfolio site using Docker and automate the deployment process with GitHub Actions. The application is containerized using Docker and deployed to Google Cloud Run.

### How the Dockerfile was built

- Base Image: I used a light web server image, nginx:alpine, to serve the static files for the portfolio site.

- Building the Image: The command docker build -t portfolio-site . packages the site’s files into a Docker image.

- Running the Container: The command docker run -p 8080:80 portfolio-site starts the container and makes the site available at localhost:8080.

### GitHub Actions Workflow Steps

The workflow automatically builds and deploys the portfolio site to GitHub Pages whenever changes are pushed to the main branch.

### Technologies Used

- Figma
- HTML
- SASS
- Bootstrap
- Git and Github
- Visual Studio Code
- Google Chrome

### Assets

[Design Link](https://www.figma.com/proto/upHoFp5qmkwPlrfCcXBu20/Portfolio?node-id=86%3A4&scaling=scale-down&page-id=0%3A1&starting-point-node-id=2%3A4)
[Github Link](https://github.com/Opeyemi128/Portfolio)
[Site Link](https://opeyemi128.github.io/Portfolio/)
