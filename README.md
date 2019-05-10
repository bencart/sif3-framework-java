This has links to the version in sif3-framework-java.

Update that one then build this one.

This has different poms.

mvn versions:set -DnewVersion=0.12.0

mvn clean compile source:jar deploy
