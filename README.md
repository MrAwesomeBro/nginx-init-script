# Init script for Nginx

### Usage

Kill all running processes from nginx:

    sudo kill `cat /usr/local/nginx/logs/nginx.pid`

Then clone the script to your server:

    git clone https://github.com/MrAwesomeBro/nginx-init-script.git

After that give it the needed rights and move it to */etc/init.d*:

    chmod +x nginx-init-script
    mv nginx-init-script nginx
    mv nginx /etc/init.d

Right now you can use the following syntax to start, stop or restart nginx:

    /etc/init.d/nginx start


