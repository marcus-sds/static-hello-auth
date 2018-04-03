# static-hello-auth

cf push static file with nginx auth

## how to use

  git clone https://github.com/marcus-sds/static-hello-auth
  
  cd static-hello-auth
  
  cf push static-hello-auth -m 64M

- nginx.conf is added

- .htpasswd is added

> To generate password, you can use [htpasswd-generator](http://www.htaccesstools.com/htpasswd-generator/)
