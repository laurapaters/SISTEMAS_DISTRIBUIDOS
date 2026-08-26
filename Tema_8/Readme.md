Tema 8: Java y Spring Framework
=============================================

## Repositorios con código de apoyo

| Repositorio | Descripción | Otros
|-----------|--|--|
|⚙️ [Servidor de registro Eureka](https://github.com/UnirCs/back-end-eureka) | Ejemplo de servidor de registro Eureka, dentro del framework de Spring. Puedes usarlo como base para tus actividades. | [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/HM8cFB?referralCode=jesus-unir)
|⚙️ [Servidor perimetral Cloud Gateway](https://github.com/UnirCs/back-end-cloud-gateway) | Ejemplo de servidor perimetral (proxy inverso), dentro del framework de Spring. Puedes usarlo como base para tus actividades. | [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/OI2sbM?referralCode=jesus-unir)
|⚙️ [Servidor perimetral Cloud Gateway con traducción de peticiones](https://github.com/UnirCs/back-end-cloud-gateway-filters) | Ejemplo de servidor perimetral (proxy inverso), dentro del framework de Spring que contiene un filtro para traducir peticiones POST siguiendo el concepto de Anti Corruption Layer. Puedes usarlo como base para tus actividades. | [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/CWxqH0?referralCode=jesus-unir)
|⚙️ [Prototipo de Microservicio con Spring](https://github.com/UnirCs/back-end-spring-microservice-archetype) | Ejemplo de microservicio. Se incluye un un esqueleto y está listo para ser desplegado en Railway | [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/JvYvDw?referralCode=jesus-unir)
|⚙️ [Ecosistema de Microservicios en Spring](https://railway.app/template/f6CKpT?referralCode=jesus-unir) | Template de Railway para desplegar sin ningún tipo de configuración adicional un servidor de registro Eureka, un servidor perimetral Cloud Gateway y dos microservicios. | [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/f6CKpT?referralCode=jesus-unir)
|🍕 [Unir-Pizza: Microservicio catálogo](https://github.com/UnirCs/back-end-pizza-catalogue) | Aplicación de pedidos de pizza.Este microservicio conecta con un clúster de Elasticsearch que contiene información sobre pizzas e ingredientes. Sirve la información a través de una API REST. |
|🍕 [Unir-Pizza: Microservicio operador](https://github.com/UnirCs/back-end-pizza-orders) | Aplicación de pedidos de pizza.Este microservicio conecta con el microservicio catálogo para obtener información sin acceder directamente a esa base de información. Además, se encuentra conectado a una base de datos en memoria que registra los pedidos realizados. |
|👥 [Unir-Forum: Microservicio para implementar un foro - Parte Editora](https://github.com/UnirCs/back-end-forum-pub) | Este microservicio sirve para entender el patrón de sistemas distribuidos editor/suscriptor y la mensajería asíncrona entre microservicios. Parte editora (simula a un profesor). |
|👥 [Unir-Forum: Microservicio para implementar un foro - Parte Suscriptora](https://github.com/UnirCs/back-end-forum-sub) | Este microservicio sirve para entender el patrón de sistemas distribuidos editor/suscriptor y la mensajería asíncrona entre microservicios. Parte suscriptora (simula a los alumnos). |
|📦 [Unir-Stock: Microservicio catalogo/buscador con H2](https://github.com/UnirCs/back-end-inventory-products) | Este microservicio está conectado a una base de datos H2 y expone, a través de una API REST, una serie de productos del inventario de una tienda. |
|📦 [Unir-Stock: Microservicio operador](https://github.com/UnirCs/back-end-inventory-orders) | Este microservicio conecta con el microservicio catálogo para obtener información sin acceder directamente a esa base de información. Además, se encuentra conectado a una base de datos en memoria que registra los pedidos. |
|📦 [Unir-Stock: Microservicio catalogo/buscador con MySQL](https://github.com/UnirCs/back-end-inventory-products-mysql) | Este microservicio está conectado a una base de datos MySQL y expone, a través de una API REST, una serie de productos del inventario de una tienda. |

El objetivo de estos ejercicios es practicar la implementación de microservicios con Java y Spring. La dificultad de cada ejercicio se indica con una escala de 1 a 5 estrellas, donde 1 es el nivel más bajo y 5 el más alto.

## Ejercicio 1 (⭐⭐️): [**Implementación de Calculadora**](https://github.com/UnirCs/DWFS-GLOBAL/tree/master/Tema_8/Ejercicios/Calculadora)

Tiempo estimado: 3h. Requisitos:

- Primera sesión de clase del tema.

## Ejercicio 2 (⭐⭐): [**Documentación con Swagger y Open API**](https://github.com/UnirCs/DWFS-GLOBAL/tree/master/Tema_8/Ejercicios/Swagger)

Tiempo estimado: 1h. Requisitos:

- Primera sesión de clase del tema.
- Haber realizado el ejercicio 1.

## Ejercicio 3 (⭐): [**Precarga de datos con H2**](https://github.com/UnirCs/DWFS-GLOBAL/tree/master/Tema_8/Ejercicios/Precarga%20de%20datos%20en%20H2)

Tiempo estimado: 1h. Requisitos:

- Primera sesión de clase del tema.
- Haber realizado el ejercicio 1.
- Conceptos básicos de SQL.

## Ejercicio 4 (⭐⭐⭐)️: [**Modelo Editor/Suscriptor con ActiveMQ. Topics y colas**](https://github.com/UnirCs/DWFS-GLOBAL/tree/master/Tema_8/Ejercicios/EditorSuscriptor)

Tiempo estimado: 3h. Requisitos:

- Primera sesión de clase del tema.

## Ejercicio 5 (⭐⭐️⭐): [**Traducción de peticiones en Cloud Gateway**](https://github.com/UnirCs/DWFS-GLOBAL/tree/master/Tema_8/Ejercicios/Gateway%20ACL)

Tiempo estimado: 3h. Requisitos:

- Segunda sesión de clase del tema.
- Haber realizado el ejercicio 1.