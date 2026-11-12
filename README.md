# Laboratorio TDD: carrito de compras

Requisitos: Node.js 20 o superior. No se instala ninguna dependencia.

```bash
npm test            # ejecuta las pruebas una vez
npm run test:watch  # vuelve a ejecutarlas cada vez que guardas
```

Sigue la guía del taller: primero la prueba (rojo), luego el código mínimo (verde) y por último la mejora (refactor).


## Reflexión

1. **¿En qué momento las pruebas te avisaron de que rompiste algo que ya funcionaba?**
   Cuando agregamos el envío del  Reto B.De repente fallaron pruebas que ya estaban bien, porque el total ya no era el mismo

2. **¿Cómo cambió tu forma de pensar el problema al escribir la prueba primero?**
   Nos obligo a tener claro que era lo que queriamos lograr antes de programarlo, asi que toco ir de pedazo en pedazo.

3. **Si mañana el IVA cambia al 16 %, ¿cuántas líneas tendrías que tocar y cómo sabrías que todo sigue bien?**
   noss tocaria tocar solo una línea, donde está el valor del IVA. Y correría las pruebas para ver si todo sigue funcionando.

4. **¿Qué parte del carrito te costaría más probar si no la hubieras diseñado con TDD?**
   Uno de los casos mas raros y especificos, diriamos que el caso del envío justo en 150.000. Sin pruebas se me habría pasado por alto.
