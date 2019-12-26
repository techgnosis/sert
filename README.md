`sert` is a wrapper around the only `openssl` functionality I use

* Looking at a local PEM-encoded certificate in a file
* Looking at a local PEM-encoded certificate as a string from STDIN
* Looking at the certificate of a URL

And it works like you would expect

```
sert mycert.pem
sert reddit.com
pbpaste | sert
```