# ![logo](https://github.com/gvieiracurti/README/blob/master/coupons_small.png)  Bienvenido al proyecto Coupons - ASP

## Descripción y propósito del proyecto
*El proyecto surge para cubrir una necesidad común en el mundo del e-commerce, la creación, gestión y trazabilidad de cupones promocionales y descuentos. Dado un cupón que una compañía ofrezca el sistema deberá validar si el cupón es válido y si además cumple con las reglas para que sea aplicado.*

**Links de interés:**

* [Documentación del obligatorio1](https://docs.google.com/document/d/1cOuDXMSelOtryqN_ztV806ykPzcvW1ZFUhwiZdp29BQ/edit?usp=sharing "Documentación del obligatorio1")
* [Documentación del obligatorio2](https://docs.google.com/document/d/1NAoL-jdZOyfdDXSeSk9_S28GBZaZC5McI7oPo-OSoPk/edit?usp=sharing "Documentación del obligatorio2")

**Alcance del proyecto**
* RF1. Registro de usuario
* RF2. Autenticación de usuario
* RF3. Gestión de clave de aplicación
* RF4. Gestión de promociones
* RF5. Listado de promociones
* RF6. Baja de promocion
* RF7. Reporte de uso
* RF8. Evaluación de promoción
* RF9. Gestión de usuarios
* RF10. SDK de evaluación de promociones
* RF11. Límite de uso de cupón
* RF12. Expiración de promociones
* RF13. Agregar cupones a promoción
* RF14. Vencimiento de cupones
* RF15. Reporte demográfico de usuarios

Puede acceder al detalle de los requerimientos desde el siguiente [link](https://docs.google.com/document/d/1NAoL-jdZOyfdDXSeSk9_S28GBZaZC5McI7oPo-OSoPk/edit?usp=sharing "Letra de segundo obligatorio").

## Descripción de la solución

El ecosistema es un sistema SAAS con una arquitectura de microservicios formado por seis microservicios. Como servidor utilizamos Heroku por la facilidad de despliegue y recursos disponibles. 

**Ecosistema de coupons:**
![ecosistema](https://github.com/gvieiracurti/README/blob/master/coupons-asp.png)


| Microservicio | Lenguaje | Framework | URL
| --- | --- | --- | --- |
| coupons-asp | Ruby | RAILs | https://coupons-asp.herokuapp.com/ |
| evaluate | Ruby | Ruby | https://coupons-asp-evaluate.herokuapp.com/ |
| monitoring | JAVA | Spring Boot | https://coupons-asp-monitoring.herokuapp.com/ |
| promoReport | Ruby | Ruby | https://coupons-asp-promo-report.herokuapp.com/ |
| demographicReport | JAVA | Spring Boot | https://coupons-asp-demographic-report.herokuapp.com/ |


