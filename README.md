Recommended SSL/TLS Web server implementation.
===========

Last updated: Tuesday, March 11th, 2014 @ 07:30

This is a placeholder repository for the current recommended SSL/TLS setup for various Web servers.

The current recommended cipher suite string is:

```
ECDH+AESGCM:DH+AESGCM:ECDH+AES256:DH+AES256:ECDH+AES128:DH+AES:ECDH+3DES:DH+3DES:RSA+AESGCM:RSA+AES:RSA+3DES:!EXPORT:!DES40:!aNULL:!MD5:!DSS
```

Note that at this time the ciphers derived from this suite are FIPS-compliant.

Sources for current recommendation:

https://hynek.me/articles/hardening-your-web-servers-ssl-ciphers/

Contributors:

[@shrikeh](https://twitter.com/shrikeh)

## Todo ##

- Set up public test server to test against by SSL Labs.
