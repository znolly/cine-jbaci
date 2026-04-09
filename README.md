# cine-jbaci
Problema 14 en jBACI

Problema del cine: Se desea implantar una boletería de cine en la que dos piezas fundamentales serán el dispensador de entradas y el dispensador de palomitas de maíz. Cuando un cliente llegue a la boletería, deberá solicitar una entrada en el dispensador correspondiente y esperar a que se la entregue. Una vez que el cliente tenga la entrada, pedirá las palomitas de maíz y aguardará a que éstas sean dispensadas en función de su número de entrada. Finalmente, el cliente podrá ingresar a la sala de cine correspondiente. Se deben desarrollar tres funciones para simular el comportamiento sincronizado de clientes, dispensador de entradas y dispensador de palomitas de maíz, considerando que ambos dispensadores permanecerán a la espera mientras no haya peticiones por atender, que dos clientes no pueden acceder al mismo tiempo al dispensador de tickets y que la boletería inicialmente está vacía.

## Descripción
- cineSem.cm: Implementación con semáforos.
- cineMon.cm: Implementación con monitores.
- cineGraf.cm: Implementación con gráficos.

Notas: Es necesario ejecutarlo dentro de la carpeta de Examples de jBACI.
