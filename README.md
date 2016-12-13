# Let's encrypt Zimbra renew
This is a script to renew the lets encrypt certificates for a single zimbra server.


Usage:

1. Copy the script on your zimbra server
2. Make the file executable:
  ```
  chmod +x renew-zimbra-certs.sh
  ```
3. Update your zimbra certificates:
  ```
  ./renew-zimbra-certs.sh your.domain.tld
  ```

 
This script was build with this tutorial: https://wiki.zimbra.com/wiki/Installing_a_LetsEncrypt_SSL_Certificate 

Feel free to fork this repro. :-)
