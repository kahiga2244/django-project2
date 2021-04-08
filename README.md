# awards

# Description

This project allows users to post their projects for other users to rate according to design, usability and content

## Live Link

Click [View Site](https://awwwards-007.herokuapp.com/) to visit the site

## User Story

- A user can view posted projects and their details.
- A user can post a project to be rated/reviewed.
- A user can rate/ review other users' projects.
- Search for projects.
- View projects overall score.
- A user can view their profile page.

## Setup and Installation

To get the project .......

##### Cloning the repository:

```bash
https://github.com/default-007/awwwards.git
```

##### Navigate into the folder and install requirements

```bash
cd awwwards pip install -r requirements.txt
```

##### Install and activate Virtual

```bash
- python3 -m venv virtual - source virtual/bin/activate
```

##### Install Dependencies

```bash
pip install -r requirements.txt
```

##### Setup Database

SetUp your database User,Password, Host then make migrate

```bash
python manage.py makemigrations instagram
```

Now Migrate

```bash
python manage.py migrate
```

##### Run the application

```bash
python manage.py runserver
```

##### Testing the application

```bash
python manage.py test
```

Open the application on your browser `127.0.0.1:8000`.

### Api Endpoints

- https://awwwards-007.herokuapp.com/api/users/
- https://awwwards-007.herokuapp.com/api/profile/
- https://awwwards-007.herokuapp.com/api/posts/

## Technology used

- [Python3.6.9](https://www.python.org/)
- [Django 3.2.1](https://docs.djangoproject.com/en/3.2/)
- [Heroku](https://heroku.com)

## Known Bugs

- There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information

If you have any question or contributions, please email me at [kahigakamiru@gmail.com]

## License

- Copyright (c) 2021 **Joseph Kahiga**