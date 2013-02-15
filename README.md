maven_repo
==========

## Maven Repository

This is my github maven repository. Starting from now I will deploy here. 
To use it this is the repository configuration for snapshots and releases:

```xml
<repositories>
     <repository>
         <id>wumpz-snapshots</id>
         <snapshots>
             <enabled>true</enabled>
         </snapshots>
         <url>https://raw.github.com/wumpz/maven_repo/master/snapshots</url>
     </repository>
     <repository>
         <id>wumpz-releases</id>
         <snapshots>
             <enabled>false</enabled>
         </snapshots>
         <url>https://raw.github.com/wumpz/maven_repo/master/releases</url>
     </repository>
</repositories>
```
