# exchange-gateway-rest


# first install the exchange core (in mvn .m2 folder)
 mvn -Dmaven.javadoc.skip=true install


# enable postgres brew setup
brew install postgres
#create user to start running postgres
createuser postgres -s


#then use mvn spring to run the rest web api
mvn spring-boot:run
