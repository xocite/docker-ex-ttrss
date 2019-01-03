# docker-ex-ttrss
An example Docker configuration that will set up Tiny Tiny RSS Reader on port 8080 on localhost.

Clone the repository, create the database volume, and start the containers.

```
$ clone <repo_url>
$ cd docker-ex-ttrss
$ mkdir database_vol
$ docker-compose build
$ docker-compose up -d web
$ firefox -new-tab localhost:8080
```
