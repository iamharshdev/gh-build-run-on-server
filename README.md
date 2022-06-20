# gh-build-run-on-server

## NGINX SETUP
Move nginx.conf to /etc/nginx/sites-enabled
```bash
ln -s /etc/nginx/sites-enabled/nginx.conf /etc/nginx/sites-available/nginx.conf
nginx -t # to make sure our nginx conf is fine
sudo service nginx stop && sudo service nginx start && sudo service nginx status
```
