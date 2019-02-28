### Java-certificate-check
This simple app test if certificate is correctly installed in keystore

In this repo is 2 version for java 7 and java 8.
```
Usage: SSLPoke <host> <port>
```
## App for version 7
```
wget https://github.com/hermanekt/Java-certificate-check/raw/master/java7/SSLPoke.class
```
```
java SSLPoke www.google.cz 443
```
HOST:java7 tomashermanek$ java SSLPoke www.google.cz 443
**Successfully connected**
## App for version 8
```
wget https://github.com/hermanekt/Java-certificate-check/raw/master/java8/SSLPoke.class
```
```
java SSLPoke www.google.cz 443
```
HOST:java8 tomashermanek$ **java SSLPoke www.google.cz 443**
**Successfully connected**
## You can define your truststore
```
java -Djavax.net.ssl.trustStore=/etc/pki/truststore SSLPoke www.google.cz 443
```
