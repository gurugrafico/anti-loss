# Guía de uso de Anti-Loss

## 1. Antes de empezar

- Tu reloj o pulsera debe estar **conectado a su app** (por ejemplo, Mi Fitness) y sincronizando.
- Ten el reloj puesto en la muñeca: muchas apps sólo reenvían avisos cuando lo llevas.

## 2. Primera configuración (unos 5 minutos)

1. Abre Anti-Loss y pulsa **Conceder permisos** (Dispositivos cercanos y Notificaciones).
2. En **Reloj vigilado**, tu reloj aparece solo si está conectado. Si no, pulsa **Elegir reloj emparejado** y búscalo en la lista (puede aparecer como "sin emparejar (BLE)").
3. Pulsa **Iniciar vigilancia**. Verás una notificación fija: "ANTI-LOSS vigilando el reloj".
4. Si el Panel lo pide, pulsa **Permitir pantalla completa** y **Permitir mostrar sobre otras apps**. Así verás la pantalla roja de alarma aunque estés usando otra app.
5. Pulsa **Probar alarma** para escuchar cómo suena y pulsa **DETENER ALARMA**.

## 3. Activar el aviso en el reloj

1. En Anti-Loss → **Alertas** → activa **"Avisar al reloj al alejarme"**.
2. En la app de tu reloj, activa las notificaciones de Anti-Loss. En Mi Fitness: tu dispositivo → **Notificaciones de aplicaciones** → **Anti-Loss**.
3. Vuelve a Anti-Loss → Alertas → **Probar aviso en el reloj**. Tu reloj debe vibrar con "¡Vuelve por tu celular!".

Si no vibra, revisa que las notificaciones de la app del reloj estén activadas y que no esté en modo No molestar.

## 4. Ajustar a tu reloj (si avisa muy tarde o muy pronto)

- **Pulseras y relojes Bluetooth LE** (como la Mi Smart Band 6): suelen funcionar con los valores por defecto.
- **Relojes con Bluetooth Clásico** (como el Redmi Watch 5 Active): ve a **Calibración**, deja el teléfono quieto y mide a la distancia a la que quieras el primer aviso. Usa el valor medido como umbral de "señal débil".
- En **Alertas** puedes cambiar cada cuántos segundos se repite el aviso y cuánto esperar antes de que suene la alarma.

## 5. Ajustes del teléfono para que no se cierre

### Xiaomi, Redmi y POCO (MIUI / HyperOS)

Son los más estrictos. Haz todos estos pasos:

1. Ajustes → Aplicaciones → Administrar aplicaciones → Anti-Loss → **Inicio automático: activado**.
2. En la misma pantalla → **Ahorro de batería → Sin restricciones**.
3. Abre Recientes, mantén pulsada la tarjeta de Anti-Loss y toca el **candado**. Así "Limpiar todo" no la cierra.
4. Otros permisos: activa **"Mostrar en pantalla de bloqueo"** y **"Abrir ventanas nuevas mientras se ejecuta en segundo plano"**.

### Motorola

No hace falta nada más: Anti-Loss vuelve a arrancar sola tras reiniciar.

### Otras marcas

Busca en los ajustes de la app opciones como "Inicio automático", "Ejecución en segundo plano" o "Batería sin restricciones" y actívalas.

## 6. Cosas que conviene saber

- **Tras reiniciar el teléfono**, la vigilancia empieza cuando lo desbloqueas por primera vez.
- **Si apagas el Bluetooth del teléfono**, Anti-Loss se pausa sin hacer sonar la alarma y continúa al encenderlo.
- **Con "No molestar" activado**, Android puede silenciar la alarma si no permites las alarmas en ese modo.
- **Historial**: en la pestaña Historial ves cuándo se alejó, se desconectó o volvió el reloj.

## 7. Problemas frecuentes

| Problema | Solución |
|---|---|
| El reloj no aparece | Abre la app del reloj para que se conecte y vuelve a Anti-Loss |
| La alarma no sonó tras un tiempo con la pantalla apagada | Revisa los ajustes del punto 5 |
| El reloj no vibra al alejarme | Comprueba el punto 3 y que "Avisar al reloj al alejarme" esté activado |
| Sale una notificación flotante en vez de la pantalla roja | Permite "Mostrar sobre otras apps" desde el Panel |
| Suena cuando el reloj sigue cerca | Sube "Esperar antes de alarmar" en Alertas (por ejemplo, a 15 s) |
