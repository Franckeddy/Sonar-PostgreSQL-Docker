# Dockerized
[<img src="https://lh3.googleusercontent.com/proxy/HX_ZxMHpJmKQ68-I-RpT8IlwoJXq196nNc7MCZRItCVBhopZLoxpmGwZc4TXGRyH1aB1bgBko4V_a-mlK3EixPaSgRWnkAvlyRVctYesS1PuiL2evtsADZw7vhb7kZNtec9BHm59Nvek" style="width: 50px">](https://www.sonarqube.org/)  **with**  [<img src="https://dbdb.io/media/logos/postgres-horizontal_4IEbUKW.png" style="width: 50px;">](https://www.postgresql.org/) 

-----
Prerequisites
-----
In order to follow my instructions you will need install:

* **Docker** — instructions for [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/), [Windows](https://docs.docker.com/docker-for-windows/install/) , [Mac](https://docs.docker.com/docker-for-mac/install/) (if you’re on Ubuntu, you’ll need also to [install Docker Compose separately](https://docs.docker.com/compose/install/)),
* **Maven** — [official installation guideline.](https://maven.apache.org/install.html)

-----
Structure of folder:
-----
```text
develop-env/
├─ docker-compose.yml
└── sonar/
   ├── Dockerfile
   └── sonar.properties
```

-----
Usage
-----
Run development environment
```bash
$ docker-compose up
```
or run in background
```bash
$ docker-compose up -d
```
To down environment
```bash
$ docker-compose down
```
-----
Access to Url's
------------------
http://localhost:9000.

-----
## Versioning
[<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/1200px-Octicons-mark-github.svg.png' width='30' />
](https://github.com/) - **Github**, Web-based version-control and collaboration platform for software developers.

-----
## Authors
* [**Franck GARCON**](https://github.com/Franckeddy)
