## PHP Assumptions - Tool to detect assumptions
[![Docker Pulls](https://img.shields.io/docker/pulls/rvannauker/phpa.svg)](https://hub.docker.com/r/rvannauker/phpa/) [![Docker Stars](https://img.shields.io/docker/stars/rvannauker/phpa.svg)](https://hub.docker.com/r/rvannauker/phpa/) [![](https://images.microbadger.com/badges/image/rvannauker/phpa:latest.svg)](https://microbadger.com/images/rvannauker/phpa:latest) [![GitHub issues](https://img.shields.io/github/issues/RichVRed/docker-phpa.svg)](https://github.com/RichVRed/docker-phpa) [![license](https://img.shields.io/github/license/RichVRed/docker-phpa.svg)](https://tldrlegal.com/license/mit-license)

Docker container to install and run phpa

### Installation / Usage
1. Install the rvannauker/phpa container:
```bash
docker pull rvannauker/phpa
```
2. Run phpa through the phpa container:
```bash
sudo docker run --rm --volume $(pwd):/workspace --name="phpa" "rvannauker/phpa" {destination}
```

### Download the source:
To run, test and develop the PHPA Dockerfile itself, you must use the source directly:
1. Download the source:
```bash
git clone https://github.com/RichVRed/docker-phpa.git
```
2. Build the container:
```bash
sudo docker build --force-rm --tag "rvannauker/phpa" --file phpa.dockerfile .
```
3. Test running the container:
```bash
 $ docker run rvannauker/phpa --help
```