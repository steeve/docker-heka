# docker-heka
Heka in a container, fork of http://github.com/ianneub/docker-heka

## How to use

You can mount your custom config.toml file to /app/config.toml, like this:

docker run -d -v /path/to/my/config.toml:/app/config.toml:ro steeve/heka
