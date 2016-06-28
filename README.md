sample-servlet3.1


Here is a link for fast servlet3 maven project starting:
 https://github.com/maciejwalkowiak/servlet3-maven-archetype

Wlp plugin:
 https://github.com/WASdev/ci.maven/tree/f8d7f634b1a2ac6753ea7932b6da9347ce1ac073#liberty-maven-plugin

Setup project:
1. download wlp https://developer.ibm.com/wasdev/downloads/liberty-profile-beta/
2. put it to C:/Workspace/wlp

Start server:
    mvn clean package liberty:start-server -P local

Stop server:
    mvn liberty:stop-server -P local

