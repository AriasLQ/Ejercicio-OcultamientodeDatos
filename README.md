### Resolución de Preguntas Teóricas

*   **Pgta 1. ¿Desde dónde es posible acceder a la variable `time`?**

    Desde la clase `TodaysDate` y desde cualquier clase dentro del mismo paquete (acceso por defecto o *package-private*).
*   **Pgta 2. ¿Quiénes pueden acceder al atributo `day`?**

    Cualquier clase, sin importar el paquete en el que se encuentre, ya que tiene el modificador `public`.
*   **Pgta 3. ¿Qué atributos de las clases tienen el método de acceso más restrictivo?**

    El atributo `month`. Tiene el modificador `private`, lo que limita su acceso exclusivamente al interior de la propia clase `TodaysDate`.
*   **Pgta 4. ¿Desde dónde se puede acceder al atributo `year`?**

    Desde el mismo paquete y desde las subclases de `TodaysDate` en cualquier paquete, debido a que utiliza el modificador `protected`.