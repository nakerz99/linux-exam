## 1. How to  check the current load of server
    top
    #you may install "sudo apt  install htop" and run htop for better GUI
## 2. What is nginx -t and apachectl -S ?
    - nginx -t 
        is the command to check and test nginx configuration file status
    - apachectl -S   
        same with the comamnd of nginx -T that gives additionally dump configuration files to standard output 
## 3. Check current swap usage
there's alot of command how we can check swap usage but the common and easy to understand is
    a. top and htop, we can see swap usege upper corner of the output, (kib swap)
    b. swapon -s


## 4. Create a vhost config that will handle http and https traffic under apache - pls check the apache folder
    4.1 Lets say that the directory is /home/test/ as home directory
    4.2 SSL certs is under /etc/apache2/SSL/test/
    4.3 Steps on how to test if vhost is working
        4.3.1 saying that the apache conf is at /etc/apache2/sites-available/ & /etc/apache2/sites-enable/
     <strong>  we can use nginx -t or nginx -T to see what inside of conf file </strong>
## 5. Create a vhost config that will handle http and https traffic under apache -  pls check the nginx folder
    5.1 Lets say that the directory is /home/test/ as home directory
    5.2 SSL certs is under /etc/nginx/SSL/test/
    5.3 Steps on how to test if vhost is working
        5.3.1 saying that the apache conf is at /etc/nginx/sites-available/ & /etc/nginx/sites-enable/
        <strong>we can use nginx -t or nginx -T to see what inside of conf file</strong>
