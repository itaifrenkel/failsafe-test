#this works
mvn clean verify 

#this fails
mvn clean package && mvn failsafe:integration-test failsafe:verify
