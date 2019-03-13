# Yaspeller image for Docker
<img align="right" width="200" src="https://raw.githubusercontent.com/hcodes/yaspeller/master/images/logo.png" />

[![GitHub](https://img.shields.io/github/license/gaiaz-iusipov/docker-yaspeller.svg)](https://github.com/gaiaz-iusipov/docker-yaspeller#license)
[![Docker Automated build](https://img.shields.io/docker/cloud/automated/gaiaz/yaspeller.svg)](https://cloud.docker.com/repository/docker/gaiaz/yaspeller)
[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/gaiaz/yaspeller.svg)](https://cloud.docker.com/repository/docker/gaiaz/yaspeller)
[![Docker Pulls](https://img.shields.io/docker/pulls/gaiaz/yaspeller.svg)](https://hub.docker.com/r/gaiaz/yaspeller/)

:whale: [Alpine](https://alpinelinux.org/) Linux based [Docker](https://www.docker.com/) Image for [Yaspeller](https://www.npmjs.com/package/yaspeller).

## Documentation

Checkout [Yaspeller GitHub page](https://github.com/hcodes/yaspeller).

## Usage

```bash
docker pull gaiaz/yaspeller
docker run --rm -it --mount type=bind,source=$PWD,target=/app gaiaz/yaspeller "*.md"
```

## License

[MIT](http://opensource.org/licenses/MIT) © [Gaiaz Iusipov](https://github.com/gaiaz-iusipov)
