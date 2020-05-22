# Bash and random terminal commands cheatsheet

Openssl to encryp/decrypt things:

`openssl aes-256-cbc -md md5 -in secrets.yml.crypt -out secrets.yml -d -base64`

`openssl enc -md md5 -aes-256-cbc -in secrets.yml -out secrets.yml.crypt -e -base64`

Network things:

`host somedomain`
