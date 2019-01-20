# Yaspeller image for Docker
<img align="right" width="200" src="https://raw.githubusercontent.com/hcodes/yaspeller/master/images/logo.png" />

[![GitHub](https://img.shields.io/github/license/gaiaz-iusipov/docker-yaspeller.svg)](https://github.com/gaiaz-iusipov/docker-yaspeller#license)

:whale: [Alpine](https://alpinelinux.org/) Linux based [Docker](https://www.docker.com/) for [Yaspeller](https://www.npmjs.com/package/yaspeller).

## Documentation

Checkout [Yaspeller GitHub page](https://github.com/hcodes/yaspeller).

## Usage

```bash
docker run --rm -it --mount type=bind,source=$PWD,target=/app gaiaz/yaspeller "*.md"
```

## License

[MIT](http://opensource.org/licenses/MIT) © [Gaiaz Iusipov](https://github.com/gaiaz-iusipov)
