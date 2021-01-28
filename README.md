
# :notebook_with_decorative_cover: Dockerize  a Symfony 5 Project

## TP
- :heavy_check_mark: Create a Symfony project with 1 simple CRUD or Use an existing Symfony Project
- :heavy_check_mark: Create a development environment for the project
- :heavy_check_mark: Create a preprod environment for the project

## :red_circle: Obligations
- :octocat: Github Flow (PR mandatory)
- :open_book: Respect Github open source guidelines
- :wavy_dash: Comment each line of the Dockerfile or docker-compose files
- :100: Complete README  to initialize the project
- :lock: Use only official Docker Hub images and lock versions of your images
- :no_entry: Mandatory services :
	- Php
	- Composer
	- Database
	- Apache or Nginx
- :envelope_with_arrow: Push your image on Docker Hub or Github (follow the mandatory rules for each platform)

## :gift: Bonus:
- :sob: Add a command to launch your tests
- :see_no_evil: Create 3 tests for the CRUD
- :outbox_tray: Create a prod environment for the project
- :scream: Push your docker on a vps or on heroku 
- :muscle: Services :
	- Testing email service (MailHog)
	- Proxy (Traefik)
	- SSL certificat (Let's Encrypt) :warning: You need a domain name


# How to install this in my project?

* Download `symfony` folder and `docker-compose.yml` file and add them to your project
* Run `docker-compose up` command from your terminal. [(Install docker compose)](https://docs.docker.com/compose/install/)

