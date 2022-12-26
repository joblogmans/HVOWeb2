# HVO Web 2

This project was inspired by the fact that our previous server died and it was a terrible experience to try to get a local development build on my machine. I decided I would try to build a new version from scratch using Docker.

## Development

Make sure you have Docker desktop installed. Copy this repository and run `sudo docker compose up` in this folder. This should start the development server at `http://0.0.0.0:8000/`. You can now start developing.

## Production

TODO

## Open to-do's

### Development:

1. Figure out a way to use VSCode development containers for this so everybody has the exact same development environment.
2. Figure out how to make production ready containers to deploy.
3. Add Docker Secrets for the database (?)

### Content/features:

1. Add login page
2. Add signup page for dinner (cook, expected time, signup deadline, guests)
3. Add general overview page with table with who cooks for the entire week
4. Add statistics of who cooked for how many etc. (figure out good way to balance this)
5. Add wie-betaalt-wat feature for house purchases
6. Add boodschappen list (?)