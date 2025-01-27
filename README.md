# Urban.Lunch-Functional-Test-Android
## Aplicación Móvil Urban.Lunch

## Descripción del Proyecto

Este repositorio contiene el informe de pruebas y los casos de prueba realizados para la aplicación móvil **Urban.Lunch**. Urban.Lunch es una aplicación diseñada para facilitar la personalización de comidas de negocios a partir de diversos restaurantes en la ciudad. Los usuarios pueden combinar diferentes platillos en un solo pedido, eligiendo puntos de recogida convenientes.

El objetivo de estas pruebas es verificar que todas las funcionalidades clave de la aplicación funcionen como se espera en diversas condiciones. Las pruebas abarcaron las áreas más críticas de la aplicación, tales como la selección de puntos de recogida, la elección de platillos, la confirmación de pedidos, el seguimiento de pedidos y las notificaciones de error.

## Objetivo de las Pruebas

El objetivo de las pruebas fue asegurar que todas las funcionalidades de la aplicación cumplieran con los requisitos definidos, sin errores críticos. Las siguientes áreas fueron evaluadas durante las pruebas:

- Selección del punto de recogida
- Elección y manejo de platillos
- Confirmación del pedido
- Seguimiento del pedido
- Notificaciones de error

## Plan de Pruebas

- **Metodología**: Se realizaron pruebas manuales para evaluar el comportamiento de cada funcionalidad de acuerdo con los requisitos establecidos.
- **Entorno de Pruebas**: Las pruebas se llevaron a cabo en plataformas **iOS** y **Android**, utilizando la versión **1.0.0** de la aplicación.

## Resultados de las Pruebas

A continuación se detallan los resultados de las pruebas realizadas:

### 1. **Selección del Punto de Recogida**

- **Comportamiento esperado**: Los puntos de recogida deben ser visibles en el mapa y en la lista desplegable. El punto seleccionado debe destacarse en negro, y el botón "Siguiente" debe activarse solo después de que un punto de recogida sea seleccionado.
- **Resultado**: La funcionalidad cumple con los requisitos. El mapa y la lista desplegable funcionan correctamente, y el botón "Siguiente" se activa como se espera.

### 2. **Elección de Platillos**

- **Comportamiento esperado**: Los platillos deben poder seleccionarse y agregarse al pedido desde la lista. El botón "Siguiente" solo debe activarse si hay platillos en la lista de pedidos.
- **Resultado**: La funcionalidad cumple con los requisitos. La selección y eliminación de platillos funciona correctamente.

### 3. **Confirmación del Pedido**

- **Comportamiento esperado**: La pantalla debe mostrar un resumen del pedido con el punto de recogida, los platillos seleccionados, el importe total y el tiempo estimado de entrega. El botón "Pedir" debe activar la transición a la pantalla de seguimiento de pedidos.
- **Resultado**: La funcionalidad cumple con los requisitos. La confirmación del pedido se realiza correctamente y la transición a la pantalla de seguimiento se activa sin problemas.

### 4. **Seguimiento del Pedido**

- **Comportamiento esperado**: El mapa debe mostrar el progreso de la preparación y entrega del pedido. El temporizador debe reflejar el tiempo restante hasta la recogida.
- **Resultado**: La funcionalidad cumple con los requisitos. El seguimiento del pedido se muestra de manera clara y precisa.

### 5. **El Pedido ha sido Entregado**

- **Comportamiento esperado**: La pantalla debe mostrar una notificación de que el pedido está listo para recoger, y el botón "Recibí el pedido" debe llevar al usuario a la página de feedback.
- **Resultado**: La funcionalidad cumple con los requisitos. La transición al feedback se realiza sin inconvenientes.

### 6. **Notificaciones de Error**

- **Comportamiento esperado**: La aplicación debe mostrar mensajes de error apropiados si no se permiten accesos a la geolocalización o si se intenta hacer un pedido sin agregar platillos.
- **Resultado**: La funcionalidad cumple con los requisitos. Los mensajes de error se muestran correctamente cuando se presentan condiciones de error.

## Conclusiones

La aplicación **Urban.Lunch** cumple con todos los requisitos establecidos en las áreas evaluadas. No se encontraron defectos críticos en las funcionalidades clave. La aplicación está lista para el lanzamiento público, ya que cumple con las expectativas en cuanto a su funcionalidad y experiencia del usuario.

---

### Información Adicional

- **Estado del Informe**: Versión 1.0  
- **Fecha**: 13 de agosto de 2024  
- **Responsable**: Equipo de QA - Urban.Lunch

---

## ¿Cómo ejecutar las pruebas?

Para realizar pruebas de manera local, sigue estos pasos para configurar el entorno:

1. **Instala los requisitos**:
   - Android Studio
   - Postman

## Contacto

Si deseas contribuir a este proyecto, no dudes en enviar un pull request o abrir un issue para discutir mejoras. Todas las contribuciones son bienvenidas.

- **Email**: maurobecerra65@gmail.com
- **LinkedIn**: [[linkedin.com/in/jesusmauro](https://www.linkedin.com/in/maurobecerragalvan/))]
