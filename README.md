# infrastructure
how to bump set spike your app

## digital ocean
 - [chowning](http://www.cyberciti.biz/faq/how-to-use-chmod-and-chown-command/)
 - [getting bundle to work with a non-root user](https://www.digitalocean.com/community/questions/problem-with-bundle-install-rails-on-ubuntu)
 - [clearing cache](https://www.digitalocean.com/community/questions/clear-cache-on-ruby-on-rails-on-ubuntu-nginx-unicorn)

 ```bash
 service unicorn restart
 service nginx restart
 ```
 
 
 - check if service is listening on a port:
 ```bash
 sudo netstat -plutn | grep :80
 ```
 
