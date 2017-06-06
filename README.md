StatsD + Graphite + Grafana 4 + Akkalytics Kamon Dashboards + Prism
---------------------------------------------

This image is based on a StatsD + Graphite + Grafana 4 image modifying nginx configuration as well as Grafana configuration to avoid CORS problem. Additional dashboards with graphs are included.


To run:

### Building the image yourself ###

cd docker-grafana-graphite
sudo docker build .
docker run -d -p 80:80 -p 8125:8125/udp -p 8126:8126 freshly_created_docker_image_id

### Now go explore! ###

We hope that you have a lot of fun with this image and that it serves it's
purpose of making your life easier. 
