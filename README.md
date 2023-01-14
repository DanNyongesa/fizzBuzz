# FIZZBUZZ
This is a repository to help guide you create a CI/CD pipeline using azure devops

# Pre-requsites
1. Python >= 3.10
2. [Poetry](https://python-poetry.org/docs/) >= 1.2.2 `curl -sSL https://install.python-poetry.org | python3 -`
3. Docker

# Getting started
## Local Development
1. Clone the repository 
2. Change directory into the solutions root folder. 
3. Create a new virtual environment `poetry env use`
4. Install project dependancies `poetry install`

## Docker
1. Change directory into the projects root folder
2. Build a docker image `docker build -t fizzbuzz:latest .`
3. Run your docker image `docker run -p 8080:8080 fizzbuzz:latest`
4. Navigate to [http://localhost:8080](http://localhost:8080])`
