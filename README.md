# Get Certificate
### Get certificate from remote HTTPS host and dump it to local file

As a result we'll have dumped certificate with all the existing certificates, installed on your Java system. 

Actually, this is standalone working version of *InstallCert* java code

**Commands**:

Build JAR: `mvn clean package`

Getting the certificate: `java -jar getcert.jar remote.https.host.com`

File `jssecacerts` will be created in the current directory.

And your next steps could be the following:
- Make a backup of your $JAVA_HOME/jre/lib/security/jssecacerts if any!
- Copy just generated jssecacerts file into $JAVA_HOME/jre/lib/security folder.

More information of the problem, solved with this tool can be found here: https://stackoverflow.com/questions/21076179/pkix-path-building-failed-and-unable-to-find-valid-certification-path-to-requ
    
