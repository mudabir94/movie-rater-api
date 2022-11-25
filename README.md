# Project Description 

- The goal of this project was to built Django application backend api. 
- To deploy django project using docker and build a ci/cd pipeline with github and dockerhub.

# Framework 
The application uses 
- Mysqlite as a database.
- PostgreSQL can also be used, the code for it is commented.
- Serializers 
- Data Validations in Models. 
- REST API framework (djangorestframework)

# Run application locally
- Pull the package docker-movie-api and run the image. 
- Create a virtual env and install the required packages from the requirements.txt file.
- To start the application type "python manage.py runserver" 
- The application will run on localhost:8000 

# Virtual Env Creation, Activation and Package Installation Commands. 
- python -m venv environment_name
- env_name\Scripts\activate
- pip install -r requirements.txt

# Connection with Front-End 
To run the application with the help of front-end you can pull the git repository from 
- [movie-rate-react](https://github.com/mudabir94/movie-rater-react) 
