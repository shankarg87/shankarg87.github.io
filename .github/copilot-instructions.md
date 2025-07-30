# Summary of the repository

This repository contains code for a personal website that will be hosted in Github Pages.

# Building the website and viewing locally

```bash
docker run -it --rm -v "$PWD":/usr/src/app -p 4000:4000 starefossen/github-pages
```

Then open your browser and go to `http://localhost:4000`.
