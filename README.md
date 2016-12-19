docker-dd-trace-agent
=====

[![Docker Repository on Quay](https://quay.io/repository/wantedly/dd-trace-agent/status "Docker Repository on Quay")](https://quay.io/repository/wantedly/dd-trace-agent)

## Usage

```bash
$ docker pull quay.io/wantedly/dd-trace-agent
```

## Run

```bash
$ docker run --name dd-trace-agent -d -p 7777:7777 -e DD_API_KEY=my_api_key -e DD_BIND_HOST=0.0.0.0 quay.io/wantedly/dd-trace-agent:latest
```

## in Kubernetes

TBD

## Author

[wantedly](https://github.com/wantedly)

## License

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
