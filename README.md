# SWAPI
## The Star Wars API

## NO LONGER MAINTAINED!

If you rely on this project for your own tools - then please fork and spin up your own instance. It's a pretty simple project, and the Makefile will take you a long way.

If you are looking for an API to play with to learn about APIs, then I recommend [https://pokeapi.co](https://pokeapi.co).

-------------------------

## For running a local instance.
```bash
# create virtualenv, and activate it
virtualenv venv && source venv/bin/activate

# install files
make install

# create database and superuser
make build

# load fixtures
make load_data

# local server at localhost:8000
make serve
```
