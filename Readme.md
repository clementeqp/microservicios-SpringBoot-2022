## Microservicios con Spring Boot.
---

* Creacion de microservicios con Spring Boot, conceptos básicos.
* Comunicación a traves de restTemplate y  Feign Client.
* Persistencia con Spring Data JPA y MyBatis.
* Creación del servidor de configuración usando Git, con Spring Cloud Config Server.(config-srv)
* Registro y localización de microservicios con Eureka Server.(eureka-srv)
* Multiples instancias.
* Enrutamiento con Gateway. Balanceo de carga con Load Balanced. (gateway-srv)
* Tolerancia a fallos con Resilience4j, patrón Circuit-Breaker. (userController).
* Implementación de Zipkin y Sleuth para realizar tracing. [Descargar jar](https://search.maven.org/remote_content?g=io.zipkin&a=zipkin-server&v=LATEST&c=exec)
* Spring Security con Json Web Token. (auth-srv)

---

Puedes descargar el proyecto en cada paso eligiendo la rama correspondiente.

    1 Descargar o clonar los proyectos. 
    2 Descargar las dependencias de cada uno. 
    3 Arrancar config-srv. (8081)
    4 Arrancar eureka-srv. (8761)
    5 Arrancar los microservicios.
    6 Arrancar gateway-srv. (8082).
    7 Zipkin (9411) Ejecutar el jar al principio. (java -jar zipkin-server-2.23.19-exec.jar)