# meta-bundle
This is a skeleton Gradle project that builds a Debian meta package that acts as an umbrella package for packages to be installed. Please see the gradle.properties for the properties that can be set to tailor the Debian package. The important one to note is the debDepends property which the meta package will depend upon during installation.
