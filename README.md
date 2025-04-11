# WhatsApp-Architecture
A distributed messaging system built using Akka, leveraging an actor-based architecture.

# How to start
open terminal:
mvn clean install

new server terminal:
mvn exec:java -Dexec.mainClass="chat.main.ServerMain"


new user terminal:
mvn exec:java -Dexec.mainClass="chat.main.UserMain"
