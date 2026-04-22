# devops-ci-cd-pipeline
DevOps Web Scraper Assignment

This project demonstrates a multi-stage Docker build using Node.js and Python.

Build the Docker image:
docker build -t devops-scraper .

Run the container:
docker run -p 5000:5000 devops-scraper

To scrape a different URL:
docker build --build-arg SCRAPE_URL=https://www.python.org -t devops-scraper .

Open in browser:
http://localhost:5000
