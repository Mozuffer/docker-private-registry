to connect from mac OS  with boot2docker Machine to deliver files use the bellow command
docker-machine ssh Mooz sudo cp ~/registry/certs/docker-reg.uae.crt /var/lib/boot2docker/
create directory called /etc/docker/certs.d/docker-reg.uae and moved the ca certificate bellow that directory
