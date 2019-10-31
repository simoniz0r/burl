# burl

A simple script that makes 'openssl' and bash's '/dev/tcp' easier to use.
The default method is openssl.

# Usage

```
Usage:
    burl [options] <url>
    
Options:
    -B          Use bash's /dev/tcp instead of openssl method

    -q, -s      Enable quiet mode
    
    -X, -m      Specify the request command to use (Ex: HEAD, GET, POST)
    
    -H          Pass custom header(s) to the server (may be used more than once)
```
