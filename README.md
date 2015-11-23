# mydropwizard-examples
This is the Dropwizard tutorial for my practice.
And the source code is refferenced below official HP.
http://www.dropwizard.io/0.9.1/docs/getting-started.html
#my environment
- OS: Mac OS X (10.11.1 Ei Capitan)
- Java: 1.8.0_60
- Dropwizard: 0.9.1
- maven: 3.3.3

#how to execute
```
$git clone https://github.com/otokunaga2/mydropwizard-examples
$cd mydropwizard-examples
$mvn package
$java -jar target/dropwizard-examples-1.0-SNAPSHOT.jar server hello-world.yml
```
Then access http://localhost:8080/hello-world.

You can confirm the JSON format response as below.
``` {"id":1,"content":"Hello, Stranger!"} ```
