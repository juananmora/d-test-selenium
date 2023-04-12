# d-test-selenium Documentation

Conjunto de pruebas automáticas que realizan la validacuión e2e de la funcionalidad del servicio cttione


# Selenium Grid

Docker images for the Selenium Grid Server
The project is made possible by volunteer contributors who have put in thousands of hours of their own time, and made the source code freely available under the Apache License 2.0.

These Docker images come with a handful of tags to simplify its usage, have a look at them in one of our releases.

To get notifications of new releases, add yourself as a "Releases only" watcher.

These images are published to the Docker Hub registry at Selenium Docker Hub.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```chrome
docker run -d -p 4444:4444 --shm-size="2g" selenium/standalone-chrome:4.8.2-20230325
```
```firefox
docker run -d -p 4444:4444 --shm-size="2g" selenium/standalone-firefox:4.8.2-20230325
```
```edge
docker run -d -p 4444:4444 --shm-size="2g" selenium/standalone-edge:4.8.2-20230325
```

## Usage

```bash
# Install Selenium Grid Mesh
docker-compose -f docker-compose-v3.yml up -d --scale chrome=2 --scale firefox=2 --scale edge=1

# test project execution
 mvn -s settings.xml clean package

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[ Apache License 2.0.](https://choosealicense.com/licenses/mit/)




