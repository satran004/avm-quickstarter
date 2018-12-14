A maven based quickstarter project for java based smart contract for AVM.

**Pre-requisites**

1) Java 11

2) aion4j-maven-plugin : 

You need to first build this maven plugin in your local environment. For build instructions, check the 
plugin's project page :

https://github.com/satran004/aion4j-maven-plugin


**Build**

$> mvnw initialize          (To install avm.jar to the local .m2 folder)

$> mvnw clean install       (Build the dApp.jar file)

$> mvnw aion4j:avm-deploy   (Deploy to embedded AVM instance)
 



