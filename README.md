Simple servlet 3.0 application


Here is a link for fast servlet3 maven project starting:
 https://github.com/maciejwalkowiak/servlet3-maven-archetype

Wlp plugin:
 https://github.com/WASdev/ci.maven/tree/f8d7f634b1a2ac6753ea7932b6da9347ce1ac073#liberty-maven-plugin

Setup project:
 download wlp https://developer.ibm.com/wasdev/downloads/liberty-profile-beta/
 put it to C:/Workspace/wlp

Start server:
 mvn package liberty:start-server -P local

Stop server:
 mvn liberty:stop-server -P local

