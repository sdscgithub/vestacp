# Let's encrypt notes

## Install ACME certbot and generate certs

```
sudo apt-get install python-certbot-apache
sudo certbot --apache -d  caas.sdsc.edu

```

IMPORTANT NOTES:
 - Congratulations! Your certificate and chain have been saved at:
   /etc/letsencrypt/live/caas.sdsc.edu/fullchain.pem
   Your key file has been saved at:
   /etc/letsencrypt/live/caas.sdsc.edu/privkey.pem
   Your cert will expire on 2018-12-06. To obtain a new or tweaked
   version of this certificate in the future, simply run certbot again
   with the "certonly" option. To non-interactively renew *all* of
   your certificates, run "certbot renew"

