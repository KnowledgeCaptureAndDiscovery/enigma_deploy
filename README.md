
# DISK deployment

There the following components:

## Enigma components

#### How to update?

Run the script `update.sh`

This script backups the old versions 

```
ssh skc.isi.edu -l deploy -p 19888
cd enigma

#download the wars
$ wget https://github.com/KnowledgeCaptureAndDiscovery/DISK/releases/download/1.1.2/disk-project-client-1.1.2.war
$ wget https://github.com/KnowledgeCaptureAndDiscovery/DISK/releases/download/1.1.2/disk-project-client-1.1.2.war
$ bash update.sh disk-project-server-1.1.2.war disk-project-client-1.1.2.war
```

### DISK server

https://enigma-disk.wings.isi.edu/disk-server/vocabulary

 - Server: skc (via proxy from ontosoft)
 - Directory: `/opt/disk/server`
 - Configuration catalina:  `/usr/share/tomcat/conf/Catalina/localhost/disk-server.xml`



### wings server

https://enigma-disk.wings.isi.edu/wings-portal/users/admin/test/workflows

 - Server: skc (via proxy from ontosoft)
 - Server: ontosoft
 - Directory: `/opt/disk/server`
 - Configuration catalina:  `/usr/share/tomcat/conf/Catalina/localhost/wings-server.xml`


### DISK client

http://skc.isi.edu/disk-portal/
- Directory:  /var/www/html/disk-portal/


