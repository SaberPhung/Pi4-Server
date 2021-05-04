Make your our server with Raspberri Pi 4 and nginx to host your own website
After booting OS on your Raspberri Pi and finished every set up step 
- sudo apt update
- sudo apt upgrade
- sudo apt install nginx
- systemctl status nginx (check nginx service)
- nano /etc/nginx/sites-available (see root folder of your website locate at /var/www/html)
- cd /var/www/html
- ls
- change ownership of index.nginx-debian.html
- ls -la
- sudo chown pi:pi .
- sudo rm index.nginx-debian.html (default file)
- create your html file here and open your Raspberri Pi address on browser
Enjoy your Raspberri Pi
