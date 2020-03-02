# spring-boot-flyway-integration

# Configure application.properties file
spring.flyway.url=jdbc:mysql://localhost:3306/test
spring.flyway.user=root # Mysql User Name
spring.flyway.password=root # Mysql Password

spring.flyway.locations=/db/scripts # If migration script location changed

create db migration script under resources/db/migration (Default location)
# V1_1__Create_tables.sql -- Naming convention V<Version>__<Script Name>.sql
