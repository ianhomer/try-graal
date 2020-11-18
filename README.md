# Background

Try GraalVM

# Install

Download from https://www.oracle.com/technetwork/graalvm/downloads/index.html

    sudo mv graalvm-ee-19.0.0 /Library/Java/JavaVirtualMachines
    jenv add /Library/Java/JavaVirtualMachines/graalvm-ee-19.0.0/Contents/Home
    jenv global 1.8.0.212
    java -version

# Demos

Clone https://github.com/graalvm/graalvm-demos

    cd java-simple-stream-benchmark
    mvn install
    java -jar target/benchmarks.jar 

# Run Graal in open JDK

See https://openjdk.java.net/projects/graal/

    -XX:+UnlockExperimentalVMOptions -XX:+UseJVMCICompiler    

# thanks


* https://github.com/chrisseaton/graalvm-ten-things
* https://github.com/graalvm/graalvm-demos
* https://github.com/quarkusio/quarkus-quickstarts
* https://www.graalvm.org/docs/getting-started/
* https://github.com/oracle/graal
* https://quarkus.io/