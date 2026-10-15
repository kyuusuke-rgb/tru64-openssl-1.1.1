===================================================================
OpenSSL 1.1.1 for Tru64 UNIX (OSF/1 5.1b) - Binary Package

Target: alphaev56-dec-osf5.1b
===================================================================

1. DESCRIPTION
This package contains OpenSSL 1.1.1 built natively on Tru64 UNIX v5.1b.
It provides modern TLS 1.2 / TLS 1.3 support, enabling legacy 
Alpha hardware to securely connect to modern web services and GitHub.

2. CONTENTS
- /usr/local/ssl/bin/openssl
- /usr/local/ssl/include/openssl/*
- /usr/local/ssl/lib/libcrypto.a
- /usr/local/ssl/lib/libssl.a
- /usr/local/ssl/cert.pem

3. EXTRACT / RESTORE
Run the following commands as root to extract to /usr/local/ssl:

 cd /
 gzip -d -c /path/to/openssl-1.1.1-tru64-bin.tar.gz | tar xvf -

4. ENVIRONMENT SETUP (.profile or .bashrc)
Add the following lines to your user shell environment:

 export PATH=/usr/local/ssl/bin:$PATH
