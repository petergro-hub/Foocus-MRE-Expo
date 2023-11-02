# Foocus-MRE-Expo

First install the webui as specified in the original installation, then create a certificate with:
openssl req -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -sha256 -days 365 -nodes

