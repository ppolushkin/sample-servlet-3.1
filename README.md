# sample-servlet3.1

## What is used:
* https://github.com/maciejwalkowiak/servlet3-maven-archetype
* https://github.com/WASdev/ci.maven/tree/f8d7f634b1a2ac6753ea7932b6da9347ce1ac073#liberty-maven-plugin

## Setup project:
* download wlp https://developer.ibm.com/wasdev/downloads/liberty-profile-beta/
* put it to C:/Workspace/wlp
* setup *WLP_PATH* in your environment variables

## Start server:
`mvn clean package liberty:start-server -P local`

## Stop server:
`mvn liberty:stop-server -P local`

