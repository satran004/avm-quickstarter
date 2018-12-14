A maven based quickstarter project for java smart contract on AVM.

**Pre-requisites**

1) Java 11

2) aion4j-maven-plugin : 

You need to first build this maven plugin in your local environment. For build instructions, check the 
plugin's project page : https://github.com/satran004/aion4j-maven-plugin


**Build**
1. To install avm.jar to the local .m2 folder
```
$> mvnw initialize
```

2. Build the dApp.jar file

```
$> mvnw clean install        
```

3. Deploy to embedded AVM instance
```
$> mvnw aion4j:avm-deploy        
```



