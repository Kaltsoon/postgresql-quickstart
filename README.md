# 🐘 PostgreSQL Quickstart

This repository contains a [Docker](https://www.docker.com/) setup for [PostgreSQL](https://www.postgresql.org/) and [pgAdmin](https://www.pgadmin.org/).

## Getting started

1. Clone this repository by running the `git clone https://github.com/Kaltsoon/postgresql-quickstart.git` (requires [git](https://git-scm.com/)) or click the "Code" button in the GitHub repository page and choose "Download ZIP".
2. Open the directory in the command-line an run the `docker compose up` command. The setup takes a minute or two
3. Open pgAdmin by visiting <http://localhost:8888> in web browser. Log in using the email "user@provider.com" and password "password". You don't have to worry about poor choice of password, because the database won't be accessible outside your computer

You can shut down PostgreSQL and pgAdmin by typing <kbd>Ctrl</kbd> + <kbd>c</kbd> in the command-line window in which you ran the `docker compose up` command. Running the `docker compose up` command again, will restart the setup. No data will be lost if you shut down the setup.
