A maven based quickstarter project for java smart contract on AVM.

**Pre-requisites**

1) Java 11

2) aion4j-maven-plugin : 

You need to first build this maven plugin in your local environment. For build instructions, check the 
plugin's project page : https://github.com/satran004/aion4j-maven-plugin

**Build**

Note: Make sure you have properly set "aion4j.plugin.version" in pom.xml.

1. To create a lib folder with required avm jars bundled in the plugin. Alternatively, you can manually create a lib folder
with required avm jars.
```
$> ./mvnw initialize

or

$> ./mvnw aion4j:init
```

2. Build the dApp.jar file

```
$> ./mvnw clean install        
```

3. Deploy to embedded AVM instance
```
$> ./mvnw aion4j:deploy        
```

4. To clean target folder and storage folder
```
$> ./mvnw clean
```


