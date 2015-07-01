# It's a simple repository to made it easy to install the jtapi reference implementation from:

[http://download.oracle.com/otndocs/jcp/jtapi-1.4-fr3-spec-oth-JSpec/](http://download.oracle.com/otndocs/jcp/jtapi-1.4-fr3-spec-oth-JSpec/)

# Building and installing into the maven local repository:

- mvn package

- mvn install:install-file -Dfile=Gjtapi-1.8.jar -DgroupId -DartifactId=gjtapi -Dversion=1.8 -Dpackaging=jar 