# Anti-Loss

**Que tu reloj te avise antes de que olvides el celular.**

Anti-Loss es una app para Android que te avisa cuando te alejas de tu teléfono. Si lo dejas en la mesa de un café o en una tienda, tu reloj o pulsera vibra mientras te alejas y, si sigues caminando, el teléfono hace sonar una sirena con voz para que alguien cerca lo note.

> La idea nació cuando un familiar dejó el celular en la mesa de una cafetería, salió a caminar por el centro comercial y sólo se dio cuenta minutos después. Por suerte alguien lo devolvió. Anti-Loss busca que eso no vuelva a pasar.

## Qué hace

| | |
|---|---|
| ⌚ **Aviso en tu muñeca** | Cuando la señal entre el teléfono y el reloj se debilita, el reloj vibra con "¡Vuelve por tu celular!" varias veces seguidas. En las pruebas avisó entre 54 y 63 segundos antes de perder la conexión |
| 🔊 **Alarma en el teléfono** | Si la conexión se pierde, el teléfono suena con una sirena fuerte y una voz ("Se ha perdido la conexión con el reloj"), aunque esté en silencio, y muestra una pantalla roja |
| 🔁 **Se apaga sola** | Al volver junto al teléfono, la alarma se detiene sin tocar nada |
| 🧠 **Sin falsas alarmas** | Ignora los cortes breves de Bluetooth (menos de 10 s, configurable) |
| 🔋 **Siempre activa** | Sigue vigilando con la pantalla apagada y vuelve a arrancar sola al reiniciar el teléfono |
| 🔒 **Privada** | Sin internet, sin cuentas y sin anuncios. Nada sale de tu teléfono |

## Dispositivos probados

| Teléfono | Reloj / pulsera | Resultado |
|---|---|---|
| Xiaomi 11T (Android 14) | Redmi Watch 5 Active | ✅ Aviso en el reloj, alarma, reinicio |
| moto g84 5G (Android 15) | Mi Smart Band 6 | ✅ Aviso en la pulsera, alarma, reinicio |

Requisitos: Android 10 o superior y un reloj o pulsera que se mantenga conectado por Bluetooth a su app (por ejemplo, Mi Fitness). Otros modelos deberían funcionar, pero aún no están probados.

## Limitaciones

- **El reloj sólo puede vibrar mientras aún hay conexión.** Una vez que se corta, ya no le llega nada; en ese caso avisa únicamente el teléfono.
- **A veces la conexión cae de golpe** sin pasar por señal débil. Entonces no hay aviso previo en el reloj, sólo la alarma del teléfono.
- **El aviso en el reloj gasta batería del teléfono**: alrededor de un 10 % al día. Sin ese aviso, el consumo es casi nulo.
- **Necesita la app de tu reloj** (p. ej. Mi Fitness) con las notificaciones de Anti-Loss activadas.
- **Algunos fabricantes cierran apps en segundo plano** (sobre todo Xiaomi). La [guía de uso](GUIA_DE_USO.md) explica qué ajustes cambiar.
- Reduce mucho el riesgo de olvidar el teléfono, pero no lo garantiza.

## Cómo empezar

1. Instala Anti-Loss (Google Play: **próximamente**).
2. Sigue la [guía de uso](GUIA_DE_USO.md): son unos 5 minutos.

## Privacidad

Lee la [política de privacidad](POLITICA_DE_PRIVACIDAD.md). En resumen: la app no tiene acceso a internet y todo se queda en tu teléfono.

## Contacto

¿Dudas, ideas o un dispositivo que no funciona? Abre un [*issue*](../../issues).

---

Anti-Loss es un proyecto independiente, sin relación con Xiaomi, Motorola ni Google. "Mi Fitness", "Redmi" y "Mi Smart Band" son marcas de sus respectivos dueños.

© 2026 Andrés Quiñones. Todos los derechos reservados. Este repositorio sólo contiene documentación; el código fuente no es público.
