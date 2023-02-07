# kastokniv/rails_docker_production_template

## Description

This is the application template that I created for Rails 7 projects. I've assembled this template with best-practices, tweaks, documentation, and personal preferences, while still generally adhering to the "Rails way".

## Requirements

This template currently works with:

* Rails 7.0.x
* PostgreSQL
* Docker
* Tailwind CSS
* Bundler 2.x

## Installation

*Ruby on Rails*
[Ruby Setup Guide](https://www.ruby-lang.org/en/documentation/installation/).

*PostgreSQL*
[PostgreSQL installation Guide](https://www.postgresql.org/download/).

*Docker*
[Docker installation Guide](https://docs.docker.com/get-docker/).

*Tailwind CSS*
[Tailwind CSS installation Guide](https://tailwindcss.com/docs/guides/ruby-on-rails/).

*Bundler*
[Bundler installation Guide](https://bundler.io/).

For Ruby Version Manager [RVM](https://rvm.io/)

## Usage

This template assumes you will store your project in a remote git repository (e.g. GitHub) and that you will deploy to a production environment. This repository contains simple DB structure of a scaffold posts written with the command below.
```
rails g scaffold post title body:text
```

To clone this template Rails application enter the following command:

```
git clone https://github.com/kastokniv/aws_docker.git
```

## After cloning

Enter the following command in the terminal to dockerize the app and running:

```
docker-compose build && docker-compose up
```

## Result

You can check the site on your localhost
`localhost:3000`
