# cryptography
illustrating cryptography with secure https in express application.

Go to bin folder and type :
1.openssl genrsa 1024 > private.key
2.openssl req -new -key private.key -out cert.csr
3.openssl x509 -req -in cert.csr -signkey private.key -out certificate.pem
