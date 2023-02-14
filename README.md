
# Django Password Generator

A simple password generator made with Django and Bootstrap. The project has two apps, `core` and `generator`.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Python and pip installed. To install Django, run the following command:

`pip install django`

### Installing

Clone the repository:

`git clone` https://github.com/JpHuici/Password-Generator.git

Change into the project directory:

`cd django-password-generator`

Create a virtual environment:

`python -m venv myenv`

Activate the virtual environment:

`source myenv/bin/activate`

Install the required packages:

`pip install -r requirements.txt`

Apply the migrations:

`python manage.py migrate`

Create a superuser:

`python manage.py createsuperuser`

Start the development server:

`python manage.py runserver`

Now you can visit [http://localhost:8000](http://localhost:8000) to view the app.

## Usage

You can choose the length of the password and if you want to include uppercase letters, special characters and/or numbers.

## Deployment

You can deploy the project to a live system following the steps described in the Django documentation.

## Built With

* [Django](https://www.djangoproject.com/) - The web framework used
* [Bootstrap](https://getbootstrap.com/) - CSS framework

## Contributing

Please read [CONTRIBUTING.md](https://github.com/your-username/django-password-generator/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **JpHuici** - *Initial work* - [My GitHub profile](https://github.com/JpHuici)



