# nginx reverse proxy vhost template

[![forthebadge](https://forthebadge.com/images/badges/certified-snoop-lion.svg)](https://forthebadge.com)

This is an easy to use nginx reverse proxy vhost template, mainly used by myself. If you want to use it replace example.com with your dowmain and change the certificate paths. Also make sure to generate the diffie helman parameters.

 For advanced authentification you will need to make yourself familiar with creating a root Certificate Authority and issuing client certificates.
 
 Features:
 - http2
 - cipher suites picked for maximum paranoia
 - disabled TLSv1/1.1 (enabled by default on most configurations)
 - Authentification stuff if needed (Basic http authentification and client certificates)
