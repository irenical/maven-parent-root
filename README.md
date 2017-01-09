[![Build Status](https://travis-ci.org/irenical/maven-parent-root.svg?branch=master)](https://travis-ci.org/irenical/maven-parent-root)
# maven-parent-root
Root Maven project, inherited by Irenical.org maven projects

Boilerplate common to all irenical's maven projects should go here

Release instructions:

1. mvn release:prepare
2. mvn -P release clean deploy

non-snapshot releases will be later on published to maven central (http://central.sonatype.org/pages/apache-maven.html)
