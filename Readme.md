# Demo Point Cloud

Create a docker of a [demo of a 3D Tiles Point Cloud dataset of Lyon](https://github.com/VCityTeam/UD-Demo-Vcity-Point-Cloud-Lyon-2018).  
<!-- _See the [online version](https://lods-lyon.vcityliris.data.alpha.grandlyon.com/)_. -->

The demo uses a [SimpleServer](https://github.com/VCityTeam/UD-SimpleServer), based on [ExpressJS](https://en.wikipedia.org/wiki/Express.js) web-server.

Clone the repo 

```bash
git clone https://github.com/VCityTeam/UD-Demo-Vcity-Point-Cloud-Lyon-2018-Docker.git
cd UD-Demo-Vcity-Point-Cloud-Lyon-2018-Docker
```

Build the docker image with

```bash
docker build -t vcity/demo-point-cloud-lyon .
```

and run the container with

```bash
docker run -p 8080:80/tcp -t vcity/demo-point-cloud-lyon
```

and open a web browser on URL `http://localhost:8080/`
