# SuperMarketBillingSystem
Batch code:GIC_AMJ21_FS_JAVA_1
Submitted by:
Ramya V              -51960376
Arifunneesa shaik    -51989386
Karamala Jeeva       -51962131
Somasekar R          -51960371
Nihal Basha          -51958137
Aditya S             -PL0621094
Vinayteja            -51989389


DATABASE CONNECTIONS PROPERTIES:

server.port= 3456
server.session.timeout=60         
# session timeout in second 
server.session.cookie.max-age=60 
# Maximum age of the session cookie in seconds. also add if server.session.timeout not working
spring.mvc.view.prefix=/WEB-INF/jsp/
spring.mvc.view.suffix=.jsp
# Oracle settings
spring.datasource.url=jdbc:oracle:thin:@localhost:1521:xe
spring.datasource.username=SYSTEM
spring.datasource.password=SYSTEM

spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
spring.data.rest.basePath=/login/admin
