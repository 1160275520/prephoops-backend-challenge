# PrepHoops Backend Challenge

## Overview

This exercise will have the candidate build a simple API which will generate JSON data used to populate the nav of the PrepHoops Frontend Challenge.

## Deliverables

-   A forked version of this repo with an attached MySQL database file with the database structure and contents so we are able to recreate your system on our local environments

## Guidelines

-   Laravel is the preferred framework, but if you'd like to use another PHP framework, go for it.
-   Auth is not required as this will be a public endpoint

## Version

0.1.0

## Get Started

```
git clone https://github.com/JeanHules/prephoops-backend-challenge.git
cd prephoops-backend-challenge
composer install
php artisan key:generate
php artisan serve
```

### Requested Endpoints

Create an endpoint that replicates the data found in the nav.json file at the root of this project.

-   **localhost:8000/nav**
