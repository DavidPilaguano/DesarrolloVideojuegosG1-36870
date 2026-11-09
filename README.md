# El volante como dispositivo de entrada

**Taller PRACT-EXP · Desarrollo de Videojuegos · Unidad 2.1**  
**Dispositivo elegido:** volante para videojuegos de conducción.  
**Fecha de consulta de las fuentes:** 9 de noviembre de 2026.

## 1. Ficha del dispositivo

| Campo solicitado | Información |
| --- | --- |
| **Nombre** | Volante de videojuegos o *racing wheel*, habitualmente acompañado de pedales y botones. |
| **Año y fabricante** | **Antecedente de entretenimiento: 1941, Drive-Mobile, International Mutoscope Reel Company. Hito temprano del videojuego arcade: 1974, Gran Trak 10, Atari.** No existe un único fabricante de toda la categoría. [F1][F2] |
| **Tecnología de captura** | Sensores leen el giro y los pedales. Según el modelo se emplean encoders, potenciómetros o sensores magnéticos. Ejemplo documentado: el Thrustmaster T300RS mide mediante H.E.A.R.T., tecnología magnética sin contacto basada en efecto Hall, con resolución de hasta 16 bits. [F3][F4] |
| **Tipo de señal** | **Mixta:** ejes de control proporcional, equivalentes a entradas analógicas para el juego, y botones digitales. Los sensores convierten acciones físicas en datos; un volante conectado por USB transmite esos datos digitalmente. El tipo exacto de sensor depende del modelo. [F3][F4][F5] |
| **Datos que entrega** | Posición de dirección, nivel de acelerador/freno y, si existe, embrague; estados de botones, levas o cambio. No mide directamente la velocidad del automóvil virtual: el juego la calcula con sus reglas de física. [F4][F5] |
| **Dos videojuegos representativos** | **OutRun (SEGA, 1986)** y **Gran Turismo 5 Prologue (Polyphony Digital/Sony, 2007 en Japón y 2008 en Europa/Norteamérica)**. El primero consolidó la experiencia de conducción en arcade; el segundo tuvo un volante oficial diseñado junto con su desarrollador. [F6][F7] |
| **Fuentes** | Páginas del museo The Strong, manual original de Atari, SEGA, Logitech, Thrustmaster y Gran Turismo. Enlaces completos al final. |

> **Alcance histórico:** se estudia el volante como interfaz de juego, no la invención del volante del automóvil. Drive-Mobile es un antecedente electromecánico, no un videojuego. Gran Trak 10 es un hito de su incorporación al videojuego.

## 2. Historia: del mecanismo físico al simulador actual

| Año | Juego o dispositivo y fabricante | Qué cambió |
| --- | --- | --- |
| **1941** | **Drive-Mobile — International Mutoscope Reel Company** | El jugador giraba un volante para mover un pequeño automóvil sobre un tambor con una carretera pintada. El museo The Strong documenta su funcionamiento y lanzamiento. Era un juego electromecánico. [F1] |
| **1974** | **Gran Trak 10 — Atari** | Incorporó volante, cambio y pedales a un videojuego arcade de carreras. El manual original de 1974 describe el conjunto del volante; The Strong lo identifica como el primer videojuego arcade de carreras. [F2][F3] |
| **1986** | **OutRun — SEGA** | La conducción con volante y pedales se integró en una experiencia arcade de rutas, música y cabinas de conducción. SEGA fecha su estreno japonés en septiembre de 1986. [F6] |
| **2000–2001** | **GT Force — Logitech; Gran Turismo 3 — Polyphony Digital/Sony** | Logitech registra el anuncio de GT Force en 2000. Gran Turismo 3 llegó a PS2 en 2001, en el contexto de la expansión de los volantes domésticos con retroalimentación de fuerza. Se distinguen el año del anuncio del periférico y el del videojuego. [F8][F9] |
| **2006** | **G25 — Logitech** | El historial del fabricante registra un cambio de seis marchas y marcha atrás por presión. Este tipo de equipo acercó al hogar controles de conducción más completos. [F8] |
| **2008** | **Driving Force GT — Logitech y Polyphony Digital** | Logitech lo presentó como volante oficial de Gran Turismo, diseñado para Gran Turismo 5 Prologue en PS3. Permitía modificar parámetros como el reparto de frenada y el control de tracción desde el volante. [F7] |
| **2020** | **G923 — Logitech G** | Introdujo TRUEFORCE, un sistema que utiliza información del motor de física y del audio para producir efectos hápticos en títulos compatibles. [F10] |
| **2022** | **PRO Racing Wheel — Logitech G** | Su motor *direct drive* entrega hasta 11 N·m. El aro se acciona directamente desde el motor, en lugar de transmitir la fuerza mediante engranajes o correas. Es un ejemplo de esta tecnología, no su invención. [F11][F12] |
| **2026, actualidad consultada** | **Ecosistemas de Logitech, Thrustmaster, Fanatec y MOZA** | Conviven tecnologías y gamas diferentes. El manual actual de Gran Turismo 7 lista modelos compatibles. Polyphony Digital anunció a MOZA como socio de periféricos de la Gran Turismo World Series el 28 de julio de 2026. [F5][F13] |

**Criterio de fechas:** se conserva el estreno japonés de OutRun que publica SEGA. Algunos listados de museos utilizan 1987 para sus máquinas; no se sustituye con esa fecha el estreno original de 1986. Para Gran Turismo 5 Prologue, 2008 corresponde a Europa y Norteamérica, como indica el anuncio de Logitech. [F6][F7]

## 3. Cómo capta la acción del jugador

### Dirección

El jugador gira el aro. Un sensor mide su posición o su desplazamiento y la electrónica lo convierte en un valor que el juego interpreta como dirección.

* **Potenciómetro:** cambia su resistencia al girar; la electrónica puede convertir la tensión resultante a un número.
* **Encoder óptico:** detecta pasos de giro mediante luz y un disco codificado. No debe confundirse con una cámara que sigue al jugador.
* **Sensor magnético de efecto Hall:** detecta cambios en un campo magnético sin rozamiento eléctrico entre las piezas de medida.

No todos los volantes usan las tres tecnologías. El manual de Gran Trak 10 muestra un conjunto de encoder de dirección. Como ejemplo moderno verificable, Thrustmaster especifica sensores Hall y hasta **65 536 valores** de resolución para T300RS. Una resolución declarada no garantiza por sí sola mayor habilidad ni un mejor resultado en todos los juegos. [F3][F4]

### Pedales, botones y conexión

Los pedales añaden valores de aceleración y frenado. Algunos conjuntos incluyen embrague y, en frenos modernos, una célula de carga que mide fuerza aplicada. Los botones y levas añaden acciones discretas. La disponibilidad de cada entrada depende del periférico y del soporte del juego. [F5][F12]

**Ejemplo conceptual de datos recibidos por un juego** —normalización ilustrativa, no protocolo universal de un fabricante—:

| Acción física | Dato que interpreta el juego | Clasificación funcional |
| --- | --- | --- |
| Girar el volante hasta cierto ángulo | Dirección entre izquierda y derecha, por ejemplo de −1 a +1 | Eje proporcional |
| Pisar parcialmente el acelerador | Intensidad, por ejemplo de 0 a 1 | Eje proporcional |
| Presionar el freno | Recorrido o fuerza, según el sensor y el modelo | Eje proporcional |
| Pulsar una leva | Pulsado o no pulsado | Digital |

**Respuesta para la clasificación de clase:** el volante moderno combina **entradas analógicas/proporcionales y digitales, captadas mediante sensores**. “Sensor” describe cómo se mide la acción; no obliga a que todas las señales eléctricas sean analógicas. Los datos viajan digitalizados al equipo.

### Force feedback: la información también vuelve al jugador

El *force feedback* o retroalimentación de fuerza hace que un motor aplique resistencia y fuerzas sobre el volante. Permite representar fenómenos calculados por el juego, como cambios de agarre o irregularidades de la pista.

**Es una salida háptica, no la tecnología que detecta el giro.** Un volante puede captar entradas aunque no disponga de force feedback. TRUEFORCE y direct drive tampoco son sinónimos: el primero es un sistema de efectos de Logitech; el segundo describe el accionamiento directo del aro mediante el motor. [F10][F11][F12]

## 4. Dos videojuegos reales y por qué fueron representativos

### OutRun — SEGA, 1986

* **Uso real:** el arcade se controla con volante, pedales y cambio de dos posiciones. La ficha histórica de SEGA documenta el juego y su fecha.
* **Qué ofrecía:** rutas que se bifurcan, escenarios de carretera y selección de música.
* **Por qué ayudó a popularizar esta experiencia:** convirtió la conducción en una actividad física reconocible dentro del salón recreativo. El volante formaba parte de la máquina y de la experiencia, sin que el jugador tuviera que comprar un accesorio.
* **Base del argumento:** SEGA lo presenta como un gran éxito de su historia de juegos de conducción. La explicación de su aporte a la popularización es una interpretación del diseño, no una cifra de ventas inventada. [F6]

### Gran Turismo 5 Prologue — Polyphony Digital/Sony, 2007–2008

* **Uso real:** Logitech anunció en febrero de 2008 el **Driving Force GT**, volante oficial de Gran Turismo diseñado para este título.
* **Qué ofrecía el conjunto:** force feedback y un selector de 24 posiciones para ajustar aspectos del automóvil durante la conducción.
* **Por qué ayudó a extender el volante doméstico:** acercó el control dedicado de conducción a PS3 con un producto desarrollado junto con Polyphony Digital. El vínculo entre hardware y videojuego está documentado por su fabricante.
* **Base del argumento:** la colaboración oficial demuestra su relevancia para el periférico. No se afirma que el juego inventara el volante ni que fuera el primero en usar force feedback. [F7]

**Continuidad actual:** Gran Turismo 7 mantiene soporte oficial para numerosos volantes, incluidos G29, G923, G PRO, T300RS y GT DD Pro/Extreme. Hay que comprobar el modelo, la plataforma y las funciones admitidas; compatibilidad no significa que todos ofrezcan los mismos efectos. [F5]

## 5. Guion para exponer en dos minutos

**0:00–0:25 · Presentación y origen**

Elegimos el volante porque transforma una acción cotidiana, girar, en una entrada para un videojuego. Su historia en el entretenimiento empieza antes de las pantallas: en 1941, Drive-Mobile usaba un volante para mover un pequeño automóvil sobre una carretera mecánica. En 1974, Atari incorporó volante, pedales y cambio al videojuego Gran Trak 10.

**0:25–0:55 · Evolución y juegos**

OutRun, de SEGA, llevó esta experiencia a los salones recreativos en 1986. Sus rutas y música hicieron que conducir fuera parte del atractivo. En casa, Gran Turismo 5 Prologue contó con el Driving Force GT, desarrollado por Logitech junto con Polyphony Digital. Estos dos casos muestran el paso del volante integrado en una máquina al periférico doméstico.

**0:55–1:30 · Tecnología y señal**

Un sensor mide el giro. Según el modelo puede ser un potenciómetro, un encoder o un sensor magnético. La dirección y los pedales producen valores proporcionales; los botones producen estados digitales. Por eso la clasificación funcional es mixta. USB transporta números digitales. El juego recibe entradas de conducción y calcula cómo se mueve el automóvil.

**1:30–2:00 · Actualidad y cierre**

El force feedback devuelve fuerzas a las manos, así que es una salida. Actualmente existen bases direct drive, como el Logitech PRO de 11 newton metro, y juegos como Gran Turismo 7 mantienen listas oficiales de compatibilidad. La idea que debemos recordar es que el sensor capta nuestras acciones y el motor puede devolver las sensaciones de la conducción.

## 6. Fuentes verificables

Todas las afirmaciones históricas y de producto remiten a las siguientes páginas. Los manuales conservan la autoría original aunque el archivo esté alojado en un repositorio histórico.

* **[F1]** Hillary Ellis, The Strong National Museum of Play. *Rolling Out the First Driving Game*, 3 de marzo de 2017. Historia y mecanismo de Drive-Mobile. [Consultar](https://www.museumofplay.org/blog/rolling-out-the-first-driving-game/).
* **[F2]** The Strong. *Raceway Arcade*. Identifica Drive-Mobile (1941) y Gran Trak 10 (1974), con sus fabricantes. [Consultar](https://www.museumofplay.org/exhibit/raceway-arcade/).
* **[F3]** Atari, Inc. *Gran Trak 10: Operating and Maintenance Manual*, 1974. Fuente primaria archivada: volante y encoder, pedales y cambio. [PDF original digitalizado](https://arcarc.xmission.com/PDF_Arcade_Atari_Kee/Gran_Trak_10/Gran_Trak_10_Operating_and_Maintenance_Manual.pdf).
* **[F4]** Thrustmaster. *T300RS*. H.E.A.R.T., efecto Hall, resolución de 16 bits y mecanismo de doble correa. [Ficha oficial](https://www.thrustmaster.com/products/t300rs/).
* **[F5]** Polyphony Digital. *Gran Turismo 7 Online Manual: Steering Wheel Controllers*. Compatibilidad y uso de cambio/embrague. [Manual oficial](https://www.gran-turismo.com/gb/gt7/manual/controller/02).
* **[F6]** SEGA. *OutRun*, archivo histórico de arcades. Estreno 1986/09, jugabilidad e importancia del juego. [Ficha oficial](https://www.sega.jp/history/arcade/product/9321/).
* **[F7]** Logitech. *Logitech Unveils Official Wheel of Gran Turismo for PlayStation 3*, 20 de febrero de 2008. [Comunicado oficial](https://news.logitech.com/press-releases/news-details/2008/Logitech-Unveils-Official-Wheel-of-Gran-TurismoTM-for-PLAYSTATIONR3/default.aspx).
* **[F8]** Logitech. *Logitech Milestones*, julio de 2011. GT Force en 2000 y G25 en 2006. [Cronología oficial, PDF](https://www.logitech.com/assets/41042/logitech-milestones-july-2011.pdf).
* **[F9]** Polyphony Digital. *Gran Turismo 3*. Fecha norteamericana: 10 de julio de 2001. [Ficha oficial](https://www.gran-turismo.com/us/products/gt3/).
* **[F10]** Logitech. *Logitech G Delivers Ultra Realistic Racing With TRUEFORCE Racing Wheel for PC and Xbox One*, 5 de agosto de 2020. [Comunicado oficial](https://ir.logitech.com/news/news-details/2020/Logitech-G-Delivers-Ultra-Realistic-Racing-With-TRUEFORCE-Racing-Wheel-for-PC-and-Xbox-One/default.aspx).
* **[F11]** Logitech. *Logitech G Launches Professional-Grade PRO Racing Wheel and Pedals*, 21 de septiembre de 2022. Lanzamiento y motor direct drive de 11 N·m. [Comunicado oficial](https://ir.logitech.com/news/news-details/2022/Logitech-G-Launches-Professional-Grade-PRO-Racing-Wheel-and-Pedals/default.aspx).
* **[F12]** Logitech G. *Best Sim Racing Setup for Every Budget*. Diferencia entre G923, RS50 y PRO; ejemplos de sensores y pedales. [Guía del fabricante](https://www.logitechg.com/en-us/discover/learn/best-sim-racing-setup).
* **[F13]** Polyphony Digital. *MOZA Racing Becomes an Official Partner of the Gran Turismo World Series*, 28 de julio de 2026. [Anuncio oficial](https://www.gran-turismo.com/us/news/00_5281770.html).

## 8. Imágenes y créditos

Las imágenes proceden de internet y se incluyen para ilustración académica, con crédito a sus titulares. No se presentan como imágenes propias ni como material de dominio público. La procedencia concreta de cada archivo se registra en `imagenes/CREDITOS.md`.

![Volante moderno Logitech G PRO](imagenes/volante-pro.png)

*Logitech G PRO Racing Wheel. Imagen de producto de Logitech G.*
```[cite: 2]