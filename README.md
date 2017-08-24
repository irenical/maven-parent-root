[![Build Status](https://travis-ci.org/irenical/maven-parent-root.svg?branch=master)](https://travis-ci.org/irenical/maven-parent-root)
# maven-parent-root
Root Maven project, inherited by Irenical.org maven projects

Boilerplate common to all Irenical's maven projects should go here

## Snapshot release:

```
mvn clean deploy -P release
```


## Public release:

```
sh release.sh
```

non-snapshot releases will be later on published to maven central (http://central.sonatype.org/pages/apache-maven.html)
