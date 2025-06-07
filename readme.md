Test:
sudo systemctl reload nginx
curl localhost/skiing
curl localhost/surfing
curl localhost/cycling
curl localhost/walking
curl localhost/cgi-bin/test1
curl localhost/cgi-bin/test2
Calls are made to nginx listening on port 80 and forwarded to port 8080 on apache.
Obviously nginx and httpd could be located on different servers.
The above URLs will also work from a browser