web: java $JAVA_OPTS -jar target/*.war --spring.profiles.active=prod,heroku --server.port=$PORT --spring.security.user.password=${JHIPSTER_PASSWORD:-"password"} --eureka.password=${JHIPSTER_PASSWORD:-"password"} --jhipster.security.authentication.jwt.secret=${JHIPSTER_JWT_SECRET:-"my-secret-key-which-should-be-changed-in-production-and-be-base64-encoded"}
