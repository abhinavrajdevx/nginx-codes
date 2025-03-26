Links files from available sites to enabled sites :
sudo ln -s /etc/nginx/sites-available/server.wxnai.com /etc/nginx/sites-enabled/

install ssl certificate from a domain connected to the server :
sudo certbot --nginx -d icpcanister.wxnai.com
