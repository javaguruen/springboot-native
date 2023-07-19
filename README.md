https://graalvm.github.io/native-build-tools/0.9.7.1/graalvm-setup.html

export export GRAALVM_HOME=/Library/Java/JavaVirtualMachines/graalvm-ce-java17-22.3.1/Contents/Home

$GRAALVM_HOME/bin/gu install native-image

mvn -Pnative -DskipTests package


https://spring.io/guides/topicals/spring-boot-docker/


