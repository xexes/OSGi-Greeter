# OSGi-Greeter
A demonstration of OSGI modules, using apache felix

## To Build 
      
      mvn -f Greeter/pom.xml install 
     
      mvn -f EnglishDict/pom.xml package 
     
      mvn -f FrenchDict/pom.xml package 
      
      
## Download an osgi distribution
felix from: http://felix.apache.org/downloads.cgi#framework
At the time of writing the felix framework version was 5.4.0

## Deploy
copy the jars from each target folder in to bundle directory of the felix framework

Then run felix from the frameworks root directory
    
    java -jar bin/felix.jar



