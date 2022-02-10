1- module "my-custom-galleon-pack" is to create the feature pack
2- module "provision" is to provision wildfly distribution 
3- to build run mvn clean install in root folder
4- check ..\root\provision\target\provision-1.0-SNAPSHOT\modules\system\layers\base\com\h2database\h2\main
4-1 you can see module.xml still in template form
4-2 I can't find h2-1.4.200.jar although it was added to pom.xml as dependency
4-3 the inital h2-14.197.jar was delete becuase task.xml deleted it , otherise it will be there

 
