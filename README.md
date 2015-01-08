# docker-galaxy-stable-toolshed
galaxy stable with an empty dev toolshed enabled

typical use:

`docker run -d -p 8080:80 -p 9009:9009 -v /host/dir:/export smithcr/galaxy-stable-toolshed`
