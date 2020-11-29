# docker_files
DockerFile examples

Squid SSL interception

docker build -t squid:SSL -f squid_compile .
docker  run -d --rm --name squid_proxy squid:SSL



