[![Build Status](https://travis-ci.org/lanl-ansi/micot-general-fragility.svg?branch=master)](https://travis-ci.org/lanl-ansi/micot-general-fragility)

[![codecov](https://codecov.io/gh/lanl-ansi/micot-general-fragility/branch/master/graph/badge.svg)](https://codecov.io/gh/lanl-ansi/micot-general-fragility)

# micot-general-fragility

# Installation

## Maven Installation

MICOT is distributed as Maven project. To install MICOT as Maven project, follow these steps

1. Download [Apache Maven](https://maven.apache.org/download.cgi) and unzip the package into a location of your choice.
2. Update your PATH variable to point at the bin directory where the "mvn" executable is located
3. Download and install [Java 1.8 JDK (or later)](http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html).
4. [Update](https://docs.oracle.com/cd/E19182-01/820-7851/inst_cli_jdk_javahome_t/) JAVA_HOME to point at directory of your Java installation.
5. Install a git tool
6. Download the repository using the following command ```git clone https://github.com/lanl-ansi/micot-general-fragility.git```
7. Build and package the code using the command ```mvn -Dmaven.test.skip=true package``` from the top level directory of the git repository

