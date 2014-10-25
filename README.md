# swagger-liberty


This project shows how to explicitly use Apache Wink for the JAX-RS runtime and use Jackson as the JSON provider instead of the default providers in WAS Liberty.
More details can be found on my [blog](http://www.mycloudtips.com//2014/10/wink-jackson-liberty.html)

## Prerequisites

- Eclipse Luna
- [liberty profile in Eclipse] (https://developer.ibm.com/wasdev/downloads/liberty-profile-using-eclipse/)
- JDK 1.7
 
## Steps

- Import the project into Eclipse
- Create a new WebSphere ApplicationServer V8.5 Liberty profile
- Paste the server property file from deploy/server.xml to your Liberty profile
- Add the wink-jackson-liberty application to the server
- Start the server
- Open a browser to http://localhost:9080/liberty/
- (Optional) push application to your IBM Bluemix account
 