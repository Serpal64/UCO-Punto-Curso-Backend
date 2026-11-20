**En qué consiste la aplicación**

Aplicación de la Universidad de Córdoba para realizar viajes hacia las distintas facultades de Córdoba desde diferentes puntos de recogida asignados. Se busca que se compartan los gastos del viaje entre los pasajeros interesados sin que se reciba ningún beneficio, y estableciendo un límite de precio por kílometro establecido. La aplicación es sin ánimo de lucro. Permitirá a los conductores poner los horarios de salida, las plazas disponibles, el punto de salida y la hora. Asimismo, los pasajeros interesados pondrán su hora a la que quieren ser recogidos. La aplicación realizará un matching entre grupos para optimizar el número de viajes. Se lanzarán alertas o notificaciones que indiquen in situ cuándo se ha cancelado un viaje, o alguien que quiera pedir un transporte. Las alertas pueden ser instantáneas o de forma programada. 


**Módulos de la aplicación**

***Core domain***
Matching entre los conductores y pasajeros.

***Cores subdomain***

- Módulo de autenticación
- Módulo de pago
- Módulo de usuarios
- Módulo de viajes
- Módulo de puntos de recogida
  
**Restricciones**

- Hay una ley que indica el máximo que se puede cobrar por kilómetro. Aplicarla.
- Las facultades son las de Belmez (innegociable), Campus Rabanales, Derecho, Filosofía y Letras, Medicina y Psicología. Los puntos de recogida por barrio o plazas.
- Penalización a conductores si cancela el trayecto.
- Como Belmez está más alejada del centro de Córdoba, si un pasajero que está en Belmez tenía un trayecto reservado pero es cancelado, la Universidad proporcionará un Taxi a los pasajeros que se queden sin conductor, y lanzará un aviso por si alguien puede ofrecer el viaje.