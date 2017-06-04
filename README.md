# hibernate
1.settings.xml:
 <localRepository>D:\work\repository</localRepository>
 
 <profiles>
    <profile>
      <id>dev</id>
    <repositories>   
      <repository>   
        <id> central</id>   
        <name> Maven Repository Switchboard</name>   
        <layout> default</layout>   
        <url>http://repo1.maven.org/maven2</url>   
      <snapshots>   
      <enabled> false</enabled>   
      </snapshots>   
      </repository>   
    </repositories>

	<pluginRepositories>
    <pluginRepository>   
      <id> central</id>   
        <name> Maven Repository Switchboard</name>   
        <layout> default</layout>   
        <url>http://repo1.maven.org/maven2</url>   
      <snapshots>   
      <enabled> false</enabled>   
      </snapshots>           
    </pluginRepository>   
  </pluginRepositories>
    </profile>
    </profiles>
    
    <activeProfiles>   
    <activeProfile>dev</activeProfile>   
  </activeProfiles>
