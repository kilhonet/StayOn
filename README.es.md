# StayOn

**Herramienta gratuita para Windows que mantiene la pantalla y el PC despiertos: basta con hacer clic en el gatito del escritorio.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión en coreano](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/stayon?lang=es)

![Pantalla de StayOn](images/stayon-ko.webp)

> La interfaz del programa no está traducida al español; se muestra en inglés. Los nombres de menú de abajo aparecen tal como se ven en pantalla.

## Descripción general

Seguro que le ha pasado: tiene una presentación abierta, una descarga larga en marcha o está leyendo un documento y, a los pocos minutos, la pantalla se apaga y el PC se duerme. En un PC de empresa, muchas veces ni siquiera se pueden cambiar los ajustes de energía.

StayOn coloca un pequeño gato de pixel art en una esquina del escritorio. **Haga clic en el gato dormido y se despierta**; mientras el gato está despierto, la pantalla no se apaga y el PC no entra en suspensión. Haga clic de nuevo y el gato vuelve a dormirse; todo regresa a la normalidad.

No toca en absoluto los ajustes de energía y suspensión de Windows. Solo tiene efecto mientras el programa se ejecuta y no deja rastro al cerrarlo o reiniciar. Un solo archivo, menos de 100 KB.

## Funciones principales

- **Un solo clic** — Haga clic en el gato para activar o desactivar la prevención de suspensión. El menú contextual también sirve.
- **Evita el apagado de pantalla, la suspensión y el bloqueo** — El salvapantallas, el apagado de pantalla, el modo de suspensión y el bloqueo automático no se activan. También evita que mensajerías como Teams le muestren como "Ausente".
- **Sin cambios en la configuración de Windows** — Las opciones de energía y las directivas de grupo se dejan intactas. No hacen falta permisos de administrador.
- **Un gato que va donde usted quiera** — Arrástrelo a donde prefiera; la posición se recuerda. No puede salirse de la pantalla.
- **Tamaño 100 % · 200 % · 400 %** — Elija el tamaño del gato según su monitor. Nítido incluso en pantallas de alta resolución (HiDPI).
- **Ejecutar al arrancar** — El gato aparece al iniciar Windows (versión con instalador).
- **Ligero y sencillo** — Reescrito en C: un ejecutable de 83 KB, sin asistente de instalación ni ventana de ajustes. Siempre en primer plano, pero nunca en la barra de tareas ni en la lista Alt+Tab.
- **7 idiomas** — Coreano · inglés · japonés · chino · ruso · italiano · francés. Sigue el idioma de Windows.

## Descarga / Instalación

| Tipo | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/stayon?lang=es) |
| Portable (ZIP) | [Descargar](https://down.kilho.net/stayon?lang=es&nosetup) |

Con el instalador, el gato aparece en cuanto termina la instalación. Para la versión portable, descomprima el ZIP y ejecute `StayOn.exe`.

Diferencia entre las dos versiones: **Run at boot** solo se puede activar en la versión con instalador (en la portable, la opción del menú aparece atenuada).

## Uso

### Primeros pasos

1. Inicie StayOn. Un **gato dormido** aparece en la parte inferior derecha de la pantalla, justo encima de la barra de tareas.
2. **Haga clic** en el gato. Se estira y se despierta; a partir de ahora la pantalla no se apaga y el PC no se suspende.
3. Haga su trabajo. El gato permanece en pantalla mientras está despierto.
4. Cuando termine, **vuelva a hacer clic en el gato**. Se duerme de nuevo y los ajustes de suspensión vuelven a la normalidad.

Al iniciar el programa, el gato **siempre empieza dormido**. Aunque lo dejara despierto ayer, no se activará solo en el siguiente inicio, para que la pantalla nunca se mantenga encendida sin que usted lo quiera.

### Distribución de la pantalla

No hay ventana ni pantalla de ajustes: solo el gato y su **menú contextual** (clic derecho).

| Menú | Qué hace |
|---|---|
| **Run** / **Stop** | Activar/desactivar la prevención de suspensión; igual que hacer clic en el gato |
| **Size** › 100% · 200% · 400% | Tamaño del gato. 200 % por defecto |
| **Run at boot** (marcado) | Inicio automático con Windows (versión con instalador) |
| **Crafted by Kilho** | Abrir la página web |
| **Exit** | Salir del programa; la prevención de suspensión también se desactiva |

- **Gato dormido** = prevención desactivada, **gato despierto** = prevención activada. No hace falta otro indicador: el gato lo dice.
- **Arrastrar para mover** — Mantenga pulsado el gato y arrástrelo. Un movimiento mínimo cuenta como clic.

### Qué hacer cuando…

**Mantener la pantalla encendida durante una presentación o reunión**
Haga clic una vez en el gato para despertarlo antes de abrir las diapositivas. Al terminar, haga clic de nuevo. No hace falta tocar los ajustes de energía del proyector ni del PC de la sala.

**Dejar una descarga o tarea larga en marcha mientras se ausenta**
Despierte al gato y el PC no se suspenderá mientras no está, así la tarea continúa. Duerma al gato al volver. No tiene nada que ver con apagar el PC: apáguelo usted mismo cuando termine la tarea.

**Teams · Slack me pone "Ausente" todo el rato**
Si solo lee o escucha una reunión sin mover el ratón, las mensajerías le marcan como ausente. Con el gato despierto no ocurre.

**No puedo cambiar los ajustes de energía en el PC de la empresa**
StayOn no cambia la configuración de Windows ni usa permisos de administrador. Incluso en un PC con el tiempo de apagado de pantalla fijado por directiva de grupo, la pantalla se mantiene mientras el gato está despierto.

**El gato me estorba**
- **Arrástrelo** a donde quiera. La posición se recuerda.
- Clic derecho → **Size** → **100%** y apenas se nota.
- El gato no se puede sacar de la pantalla; se detiene en el borde del monitor.

**El gato es demasiado pequeño (monitor 4K, etc.)**
Clic derecho → **Size** → **400%**. Se multiplica por la escala de Windows, así que queda nítido en cualquier resolución.

**Que el gato aparezca cada vez que se enciende el PC**
En la versión con instalador, clic derecho → marque **Run at boot**. Desde el siguiente arranque, el gato aparece dormido tras iniciar sesión. En la portable esta opción está bloqueada: use la versión con instalador.

**No veo el gato**
- Si ya se está ejecutando, iniciarlo por segunda vez no hace nada (solo un gato a la vez). Mire en las esquinas de la pantalla y en los otros monitores.
- Si cambió la configuración de monitores y la posición guardada quedó fuera de la pantalla, vuelve automáticamente a la posición por defecto (parte inferior derecha del monitor principal).

**Cerrar StayOn por completo**
Clic derecho → **Exit**. Si el gato estaba despierto, la prevención de suspensión se desactiva con él. Si solo duerme al gato, el programa sigue abierto y podrá despertarlo de inmediato la próxima vez.

**Comprobar que la prevención de suspensión funciona**
Si el gato está despierto, funciona. Para asegurarse, espere a que pase el tiempo de apagado de pantalla de Configuración de Windows → Sistema → Energía y compruebe que la pantalla sigue encendida.

**Usar la misma posición y tamaño en otro PC**
Los ajustes se guardan en su cuenta de usuario y se conservan al actualizar. En un PC nuevo, mueva el gato una vez y elija un tamaño; a partir de ahí se recuerda.

## Configuración

No hay ventana de ajustes; todo se cambia desde el menú contextual y se guarda al instante.

| Elemento | Por defecto |
|---|---|
| Size | 200% |
| Posición del gato | Parte inferior derecha del monitor principal (sobre la barra de tareas) |
| Run at boot | Desactivado |
| Estado de la prevención de suspensión | No se guarda; siempre empieza dormido |

El idioma de la interfaz sigue el idioma de Windows (coreano · inglés · japonés · chino · ruso · italiano · francés; en otro caso, inglés).

## Requisitos

- Windows 10 o Windows 11 (32 y 64 bits)
- No requiere permisos de administrador ni runtime adicional.
- La conexión a Internet solo se usa para comprobar avisos de nueva versión. Funciona sin conexión.

## Actualizaciones

StayOn **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; al pulsar **Yes** se abre la página de descarga y el programa se cierra. Las nuevas versiones se publican manualmente tras una verificación interna y se anuncian en la [página de StayOn](https://kilho.net/stayon). Consulte el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

**Historial de versiones**

| Versión | Fecha | Cambios |
|---|---|---|
| 2.0.0 | 2026-09-21 | Renovación completa con una estructura más ligera y estable (reescrito en C); mejor prevención del apagado de pantalla, la suspensión y el estado "Ausente" de Teams; tamaño 100 / 200 / 400 %; posición y tamaño guardados automáticamente, mejor colocación en varios monitores |
| 1.0.2 | 2024-11-25 | Corregidos errores de Direct2D en algunos PC; mayor nitidez HiDPI |
| 1.0.1 | 2024-11-16 | Añadidos italiano, francés y ruso |
| 1.0.0 | 2024-11-03 | Mejora de los avisos de actualización; compatibilidad multilingüe |

## Licencia

StayOn es **freeware**. Puede usarlo gratis y sin restricciones en cualquier lugar — empresa, casa, organismos públicos, escuela — y redistribuirlo libremente.

## Enlaces

- Sitio web: <https://kilho.net/stayon>
- Foro: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
