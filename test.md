curl -sO http://35.91.43.243:8080/jnlpJars/agent.jar
java -jar agent.jar -url http://35.91.43.243:8080/ -secret cd51d24cd6a6c2e5da882b91ae767c61fbb3ba130449fc9a988d5ef7d376575a -name test -webSocket -workDir "/home/jenkins"
