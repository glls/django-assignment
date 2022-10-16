# Backend Developer Assignment

## Requirements

The assignment is to develop a containerized application using [Docker](https://www.docker.com/) and [Django](https://www.djangoproject.com/) that supports a list of **sensor stations** in an area. For data storage you should use [PostGIS](https://postgis.net/). Data will be served with 'Django Rest Framework' or a similar REST-API framework.

## User rights

There two type of users, an admin and a station owner.
The station registration [3] needs privileges but everyone should view the list of stations [4] without login or registration.

There should be documentation about using the REST-API, Open-API style like [Swagger](https://editor.swagger.io/) is preferred.

No Front-end is needed.

Please provide a Git repository with the solution (e.g. Github/Gitlab private repo)
and an accompanying online demo website.

## Endpoint definitions

Provide a REST-API that includes endpoints for:
1. User registration with at least the following fields:
    * Username
    * Password
    * E-mail
1. User login with an enterprise ready authentication method (e.g. JWT)
1. Store creation, with the following fields:
    * name
    * category
    * description
    * lat/lon coordinates
    * contact information
    * open hours
1. A list of shops with the following capabilities:
    * Filtering by category
    * Pagination
    * Search by name
    * Display shops that are open now
    * Nearest shops to a location


>The use of industry mature libraries/frameworks is preferred.
>The usage of open-source libraries is required.

