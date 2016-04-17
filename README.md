# Synopsis
Short demo of Spring Boot's Data REST 

# Example
```bash
git clone https://github.com/ch6574/spring-data-rest.git
cd spring-data-rest

# Make a local certificate for SSL
keytool -genkey -alias tomcat -keyalg RSA -storepass qwerty -keystore keystore.rsa

# Build and run
mvn clean compile package
mvn spring-boot:run

# In a web browser visit the HAL browser (ignore the certificate warnings)
https:localhost:9000/
```
# Note
Check http://docs.spring.io/spring-data/rest/docs/current/reference/html/ for full documentation

# License
GPL v3.
