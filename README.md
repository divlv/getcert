# Get Certificate
### Get certificate from remote HTTPS host and dump it to local file

As a result we'll have dumped certificate with all the existing certificates, installed on your Java system. 

Actually, this is standalone working version of *InstallCert* java code

**Commands**:

Build JAR: `mvn clean package`

Getting the certificate: `java -jar getcert.jar remote.https.host.com`

File `jssecacerts` will be created in the current directory.
