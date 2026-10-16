===================================================================
OpenSSL 1.1.1 for Tru64 UNIX (OSF/1 5.1b) - Built Tree Package
Target: alphaev56-dec-osf5.1b
===================================================================

1. DESCRIPTION
This package contains OpenSSL 1.1.1 built natively on Tru64 UNIX v5.1b.
(Contains source tree with compiled binaries and static libraries)

2. RESTORE PROCEDURE
Run the following commands as root to deploy binaries and libraries:

 # cd /
 # gzip -dc /path/to/openssl-1.1.1-tru64-built.tar.gz | /sbin/tar xvf -
 # cp -p /openssl-1.1.1/apps/openssl /usr/local/bin/openssl
 # cp -p /openssl-1.1.1/libcrypto.a /usr/local/lib/
 # cp -p /openssl-1.1.1/libssl.a /usr/local/lib/
 # rm -rf /openssl-1.1.1

3. VERIFICATION
 # /usr/local/bin/openssl version
