# geode-hello-world
Geode example application

Apache Geode (incubating) provides a database-like consistency model, reliable transaction processing and a shared-nothing architecture to maintain very low latency performance with high concurrency processing. For more information about Geode, see http://geode.apache.org.

This project shows a simple HelloWorld client application using Geode.  The application connects to a Geode cluster and does basic put and get operations on the cache.

## Instructions

1. Download the Geode binary distribution from http://geode.apache.org/releases/.  Extract the archive and set `$GEODE_HOME` to the install location.

2. Build and install the geode-hello-world project using `./gradlew build install`.

3. Start the Geode cluster with `./build/install/geode-hello-world/bin/geode-ctl start`.

4. Run the HelloWord application by invoking `./gradlew run`.

5. Shutdown the Geode cluster with `./build/install/geode-hello-world/bin/geode-ctl stop`.

