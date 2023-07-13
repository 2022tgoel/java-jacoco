`mvn test` generates the JUnit xml in `target/surefire-reports/TEST-*.xml`

By default, surefire automatically includes all test classes whose name starts with Test, or ends with Test, Tests or TestCase.

`mvn verify -Dtest=[test name]` to generate code coverage info about a specific test in `target/site/jacoco/jacoco.xml`

`mvn clean verify` if you want to clear the cache of previous tests

For whatever reason, only works with latest versions of plugins and java version specified
