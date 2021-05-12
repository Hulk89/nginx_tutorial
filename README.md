## install
`brew install nginx`

## run
` openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout localhost.key -out localhost.crt
Generating a 2048 bit RSA private key`

`nginx -c <absolute path of nginx_tutorial repository>/nginx.conf`
