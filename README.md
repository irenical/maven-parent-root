[![Build Status](https://travis-ci.org/irenical/maven-parent-root.svg?branch=master)](https://travis-ci.org/irenical/maven-parent-root)
# maven-parent-root
Root Maven project, inherited by Irenical.org maven projects

Boilerplate common to all irenical's maven projects should go here

##Release instructions:

### Using the maven release plugin

1. mvn release:clean
2. mvn release:prepare
3. mvn release:perform

### Using the maven deploy

1. Bump the version of the pom to a release version (ex: 1.0.0) 
2. mvn -P release clean deploy
3. Update the pom version to the next SNAPSHOT version ( ex: 1.0.1-SNAPSHOT)

non-snapshot releases will be later on published to maven central (http://central.sonatype.org/pages/apache-maven.html)
