## maven-distribution-com.sphenon.components.engines.objectassembler

# Build [Object Assembler](http://xocp.org) Distribution from Sphenon components.

## Prerequisites

[Clone and build the Sphenon components](https://github.com/616c/maven-aggregator-com.sphenon).

## Cloning and building

`git clone https://github.com/616c/maven-distribution-com.sphenon.components.engines.objectassembler.git
mvn install`

After successful build, you find distribution archives in the target subfolder, named:

`objectassembler-#.#.#-bin.(tar.gz|tar.bz2|zip)`

## Running

under

`src/test/script/run.bash`

you'll find a little testscript that invokes the objectassembler with full classpath from this project here
and with an internally provided Object Construction Plan (OCP) that is contained in the JAR file.
It prints out the test results of reading this OCP.
Of course reading an OCP via command line does not make too much sense, but it demonstrates how to do it.
Many sample OCPs can found on [xocp.org](http://xocp.org).
