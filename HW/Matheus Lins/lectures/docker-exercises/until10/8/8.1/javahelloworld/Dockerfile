FROM java:8
COPY /Users/matheuslins1/Documents/Facul/Microservicos/if1004-DevOps/HW/Matheus Lins/lectures/docker-exercises/until10/8/8.1/javahelloworld/src
RUN javac -d bin src/HelloWorld.java
ENTRYPOINT ["java", "-cp", "bin", "HelloWorld"]
