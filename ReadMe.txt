Extracting response information with Jayway JsonPath library

Useful Links:
JsonPath online Evaluator: https://jsonpath.herokuapp.com/
GitHub Page: https://github.com/json-path/JsonPath

====================================================================

Extracting response information with JsonPath (RestAssured)

Useful Links
JsonSlurper Playground links :
https://www.tutorialspoint.com/execute_groovy_online.php

Inside the compiler, add the below code

import groovy.json.JsonSlurper 
 
class Example {
   static void main(String[] args) {
      def jsonSlurper = new JsonSlurper()
      def object = jsonSlurper.parseText('YOUR_JSON') 
      
      println(object);
   } 
}

JSON Viewer/Formatter:
http://jsonviewer.stack.hu/

Groovy library links
http://docs.groovy-lang.org/latest/html/groovy-jdk/java/util/Collection.html#findAll()
http://docs.groovy-lang.org/latest/html/groovy-jdk/java/util/Collection.html#find()
