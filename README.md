`mvn test` generates the JUnit xml in `target/surefire-reports/TEST-*.xml`

`mvn verify -Dtest=[test name]` to generate code coverage info about a specific test in `target/site/jacoco/jacoco.xml`

`mvn clean verify` if you want to clear the cache of previous tests