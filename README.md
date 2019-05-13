# burl

A simple script that makes 'openssl' and bash's '/dev/tcp' easier to use.
The default method is to try a HEAD request with openssl.  If the HEAD 
request failed, bash's '/dev/tcp' is used.  Otherwise, the request is repeated
with openssl.

# Usage

```
Usage:
    burl [options] <url>
    
Options:
    -O          Use openssl instead of default method

    -B          Use bash's /dev/tcp instead of default method

    -q, -s      Enable quiet mode
    
    -X, -m      Specify the request command to use (Ex: HEAD, GET, POST)
    
    -H          Pass custom header(s) to the server (may be used more than once)
```
