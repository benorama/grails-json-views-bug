Grails Json Views Bug
=====================

# Running the app locally

* Run `grails run-app`
* Go to `http://localhost:8080/bar/index`

It returns **Hello world from a GSP!**

* Go to `http://localhost:8080/bar/index.json`

It returns **{"message":{"hello":"world"}}**

# Running the app in tomcat

* Run `gradle assemble`
* Deploy the war to Tomcat
* Go to `http://localhost:8080/bar/index`

It returns **Hello world from a GSP!**

* Go to `http://localhost:8080/bar/index.json`

It returns **{}** as if the index.json was not found.