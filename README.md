hello-scala [![Build Status](https://travis-ci.org/mbe24/hello-scala.svg?branch=master)](https://travis-ci.org/mbe24/hello-scala)
===========

Scala example project
---------------------

To generate a scala example project use the follwing maven command,
which relies on an archetype.

```
mvn archetype:generate \
      -DarchetypeGroupId=org.scala-tools.archetypes \
      -DarchetypeArtifactId=scala-archetype-simple  \
      -DarchetypeVersion=1.3 \
      -DremoteRepositories=http://scala-tools.org/repo-releases \
      -DgroupId=org.beyene.hellworld \
      -DartifactId=helloworld \
      -Dversion=0.0.1-SNAPSHOT
```
