# Certbot-SSL
```
sudo add-apt-repository ppa:certbot/certbot
sudo apt-get update
sudo apt install certbot python3-certbot-nginx
sudo certbot --nginx -d yourdomain.com -d www.yourdomain.com

# Only valid for 90 days, test the renewal process with
certbot renew --dry-run
```

# Certbot generate certificate for subdomain
certbot -d domain name,subdomain.domain name,www.domain name --expand


Check certbot certificates list:
certbot certificates

Now visit https://yourdomain.com and you should see your Node app
