# docker-build-logstash-forwarder

Packaging for logstash-forwarder is broken at the moment and building from source has some relatively recently dependencies so I threw together a container for it.

Building this image then running...

    sudo docker run build-logstash-forwarder -it --rm -v /home/ubuntu:/data

Would drop a freshly compiled `logstash-forwarder_0.4.0_amd64.deb` into /home/ubuntu. 
