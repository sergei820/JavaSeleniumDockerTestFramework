To run the framework (troubles with path):

    /Users/sergeikamendrovskii/Documents/ProgramFiles/apache-maven-3.9.6/bin/mvn clean test

One test fails:

To make it pass set
"searchResultsCount": 0
in src/test/resources/test-data/vendor-portal/john.json
