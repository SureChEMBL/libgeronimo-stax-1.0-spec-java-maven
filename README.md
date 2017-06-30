# libgeronimo-stax-1.0-spec-java-maven Debian package

Official `libgeronimo-stax-1.0-spec-java` Debian package installs only `geronimo-stax-1.0-spec.jar` into `/usr/share/java`, but doesn't install it into `/usr/share/maven-repo`.

The current package simply depends on `libgeronimo-stax-1.0-spec-java` and creates necessary symlink and POM file in Debian local Maven repo, so that `org.apache.geronimo.specs:geronimo-stax-api_1.0_spec:1.0` is available from it.
