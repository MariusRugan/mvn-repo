# mvn-repo
basic divolte avro-schema outside mavencentral


# avro-schema (http://divolte.io) download 

mvn org.apache.maven.plugins:maven-dependency-plugin:2.8:copy \
  -Dartifact=io.divolte.examples:avro-schema:0.2-SNAPSHOT:jar: \
  -DrepoUrl=https://github.com/MariusRugan/mvn-repo \
  -DoutputDirectory=.
