[![Quarto Publish](https://github.com/vanHeemstraSystems/scene-management/actions/workflows/publish.yml/badge.svg)](https://github.com/vanHeemstraSystems/scene-management/actions/workflows/publish.yml)

scene-management
# Scene Management

Can be read as "Scene Management" at https://app.gitbook.com/s/Rs3XPuVclvoj92Exb9AA/

Can be browsed as "Scene Management" at https://vanheemstrasystems.github.io/scene-management/

Documentation of this repository is automatically done with Quarto using GitHub Actions as described at https://github.com/vanHeemstraSystems/quarto-to-github-pages/blob/main/300/300/README.md

Based on "How to Run PostgreSQL and pgAdmin Using Docker" at https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5

Based on "IFC.js - Building Information Modeling (BIM) toolkit for JavaScript" at https://ifcjs.github.io/info/

Use the file ```haus.ifc``` (in this repository) to upload to this demo environment at https://ifcjs.github.io/web-ifc-viewer/example/index for a first impression of what IFC.js is capable of.

![haus_demo](https://github.com/vanHeemstraSystems/scene-management/assets/1499433/b3bf2d33-8018-43ad-a193-094f9bc4770b)
hasu.ifc in web-ifc-viewer

Create yarn.lock file as follows:

```
$ cd containers/app/main
$ yarn install
```

Run as follows:

```
$ cd containers/app
$ docker-compose --file docker-compose.dev.yml --project-name scene-management-dev up --build -d
```
