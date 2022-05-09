# PHP-Email

apt update

apt install nginx php php-pear

pear install Auth_SASL 

pear install mail

pear install net_smtp

pear install mail_mime

## 允许远程访问 json/text 文件

    location ~* \.(json|txt)$ {
	add_header Access-Control-Allow-Origin *;
    }


