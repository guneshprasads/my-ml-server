# Deploy Machine Learning Models with Django

This web service makes Machine Learning models available with REST API. It is different from most of the tutorials available on the internet:

- it keeps information about many ML models in the web service. There can be several ML models available at the same endpoint with different versions. What is more, there can be many endpoint addresses defined.
- it stores information about requests sent to the ML models, this can be used later for model testing and audit.
- it has tests for ML code and server code,
- it can run A/B tests between different versions of ML models.

## The code structure

In the `backend` directory there is Django application.

In the `docker` directory there are dockerfiles for running the service in the container.

To Run the application you want run the 
## python manage.py runserver

