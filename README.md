# Backend Developer Assignment

The assignment is to develop a containerized application (with Docker) using PostGIS and Django that supports a registry of stores in an area (restaurants, fast foods, bakeries, etc.)

The store registration [3] needs privileges but everyone should view the list of stores [4].
There should be documentation about using the REST-API.

No Front-end is needed.

Please provide a git repository with the solution (e.g. github private repo)

Provide a REST-API that includes endpoints for:
1. User registration with at least the following fields
    * Username
    * Password
    * E-mail
1. User login
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
