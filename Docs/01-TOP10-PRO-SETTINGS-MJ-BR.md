# 01 — Plan Maestro de Configuración TOP 10 Pro (MJ & BR) — Multi-Dispositivo

> **Desarrollador Líder:** Rogerr Carvajal ([@rogerrcarvajal](https://github.com/rogerrcarvajal)) — *Player ID:* `乂RC.elGon`  
> **Especialidad:** Arquitectura de Software con Modelos, Agentes Inteligentes y Optimización de Alto Rendimiento  
> **Fuentes:** 34 Capturas de `COD Mobile - Gallery` + Telemetría MCP YouTube (`youtube-fusion`)  

---

## 1. Benchmark del TOP 10 de Jugadores y Creadores (MCP YouTube)

| # | Creador / Pro Player | Especialidad | Vistas Analizadas | Principio Técnico Incorporado |
| :---: | :--- | :--- | :---: | :--- |
| **1** | **Ganyth** | Sniper 5-6 Dedos (iPad Pro M2 4th Gen) | 425,730 | FOV `80` + *Sync FOV (`SÍ`)* + Sensibilidad desvinculada de resolución para *flicks* de francotirador (HDR / Tundra / DLQ33). |
| **2** | **SantanaGlock** | Movilidad Extrema MJ & BR | 301,540 | *Posición de joystick virtual corregida (`SÍ`)*, *Pista de deslizamiento (`SÍ`)*, Aceleración controlada (`99-125`) y truco de *Esprintar Siempre* (`80`). |
| **3** | **iFerg** | Meta Ranked Slayer (iPad Pro) | 225,935 | Selección de clases de 0 retroceso con `Silenciador Monolítico` + `Láser Táctico OWC` para mantener sigilo y TTK en Leyenda. |
| **4** | **samiul gamer** | Sensibilidad Pro Tablet & Móvil | 121,091 | Diferenciación matemática entre sensibilidad en Tablet vs Teléfono y separación de valores para ARs (`115-123`) vs Snipers (`90-95`). |
| **5** | **NightYT** | 4-5 Finger Claw & Gunsmith | 112,627 | HUD limpio en esquinas superiores y minimapa con opacidad `75-80%` y escala `135%`. |
| **6** | **ALVI GAMING** | 4 Finger Handcam iPad | 103,001 | Disparo manual (*Cadera*) desactivando *Apunta y dispara con un toque* para ahorrar `80 ms` en cada enfrentamiento. |
| **7** | **Bobby Plays** | Analista Meta Competitivo | 92,219 | Balance de ventajas (*Chaqueta Flak / Peso Ligero* + *Dureza / Arrollador* + *Silencio Mortal*) según el rol en el mapa. |
| **8** | **dry** | Handcam iPad Pro M5 120FPS | 83,834 | Gráficos en **Media + Ultra (120 FPS)** para mantener el *frame-time* plano en `8.33 ms` sin *thermal throttling*. |
| **9** | **LittleB** | Ex-Pro Mundial (3x World Champ) | 76,357 | **Escala de vibración de cámara en `0`**, **Perspectiva de compañero `SÍ`**, **Dolby Atmos `SÍ`** y **Giro vertical de disparo en `125`**. |
| **10** | **Coscript - Mobile** | 6 Finger Claw iPad / Phone | 28,991 | Uso de **Velocidad Fija** y sensibilidad de **Disparo `+3` puntos superior a Cámara** para rastrear enemigos que hacen *slide-cancel*. |

---

## 2. Auditoría Completa de las 34 Capturas (`IMG_0254.PNG` – `IMG_0287.PNG`)

### 2.1. Ajustes Básicos y de Función (`IMG_0255` – `IMG_0273`)

| Captura | Ajuste en Español (UI Oficial) | Valor en Galería | Nuevo Valor MJ | Nuevo Valor BR | Justificación Competitiva |
| :---: | :--- | :---: | :---: | :---: | :--- |
| `IMG_0255` | Ayuda al apuntar | `SÍ` | **`SÍ`** | **`SÍ`** | Activa el cono magnético de seguimiento en corta y media distancia. |
| `IMG_0255` | Btn fuego rápido para rotación de cámara | `NO` | **`NO`** | **`NO`** | Evita que el dedo índice desvíe la mira al presionar el botón de disparo. |
| `IMG_0255` | Posición de visualización de joystick virtual corregida | `SÍ` | **`SÍ`** | **`SÍ`** | Impide que el joystick cambie de lugar y trabe tu movimiento lateral. |
| `IMG_0255` | Botón apuntar con la mira para rotación | `SÍ` | **`SÍ`** (4 dedos) / **`NO`** (5-6 dedos) | **`SÍ`** | Permite rotar cámara mientras abres la mira si apuntas con el pulgar. |
| `IMG_0255` | **Apunta y dispara con un toque** | `SÍ` ❌ | **`NO` (Cadera)** ✅ | **`NO` (Cadera)** ✅ | Usar botones separados de apuntar y disparar elimina el delay de `80 ms`. |
| `IMG_0256` | Cambio de arma rápido + Btn cambio 1 toque | `SÍ / SÍ` | **`SÍ / SÍ`** | **`SÍ / SÍ`** | Permite cambiar al cuchillo tras disparar el HDR para hacer *slide-cancel*. |
| `IMG_0256` | **Alcance de visión (1P) / CV (1ª persona)** | `75 / 75` | **`75 / 80`** ✅ | **`75 / 80 (1P) y 80 (3P)`** ✅ | Amplía la visión periférica en pantallas de 11" a 13" sin deformar bordes. |
| `IMG_0257` | Sincronizar CV para hacer zoom con la mira | `SÍ` | **`SÍ`** | **`SÍ`** | Reduce hasta un 40% el retroceso visual percibido al apuntar. |
| `IMG_0258` | **Pista de deslizamiento** | `NO` ❌ | **`SÍ`** ✅ | **`SÍ`** ✅ | Convierte el botón de agacharse en deslizar inmediatamente al mover el joystick. |
| `IMG_0258` | **Esprintar siempre (Sensibilidad)** | `SÍ (95)` | **`NO (Barra 80)`** o **`SÍ (82)`** | **`SÍ (100)`** | En MJ (Buscar y Destruir) permite caminar sin hacer ruido; en BR corre al instante. |
| `IMG_0259` | Habilitar táctica en mano izquierda | `SÍ` | **`SÍ`** | **`SÍ`** | Lanza granadas tácticas (conmoción/trofeo) sin soltar el arma principal. |
| `IMG_0260` | Curva del CV al apuntar con la mira | `NO` | **`NO`** | **`NO`** | Evita distorsión de zoom durante la animación de apuntado. |
| `IMG_0268` | Escala de retroceso / Rotación por retroceso (ADS) | `0 / 0` | **`0 / 0`** | **`0 / 0`** | Elimina la animación falsa de sacudida del cañón. |
| `IMG_0269` | **Escala de vibración de la cámara (ADS)** | `100` ❌ | **`0`** ✅ | **`0`** ✅ | **Corrección #1**: Elimina por completo el temblor de pantalla al disparar. |
| `IMG_0270` | **Perspectiva de compañero** | `NO` ❌ | **`SÍ`** ✅ | **`SÍ`** ✅ | Muestra la silueta de tus aliados a través de todas las paredes del mapa. |
| `IMG_0272` | **Minimapa (Escala / Opacidad / Ampliación)** | `137 / 50 / 50` | **`135 / 75 / 45`** ✅ | **`140 / 80 / 40`** ✅ | Aumenta la nitidez del radar y amplía el área visible de enemigos. |

---

### 2.2. Gráficos y Sonido Competitivo (`IMG_0274` – `IMG_0278`)

* **Calidad Gráfica**: **MEDIA** en MJ (elimina sombras densas, humo pesado y reflejos distractores) | **MEDIA o ALTA** en BR (en chips M1/M2/M4/M5/M6 para renderizar enemigos y vehículos a larga distancia).
* **Cuadros por Segundo (FPS)**: **ULTRA (120Hz)** con **Ajuste de frecuencia de actualización en `120 (SÍ)`**.
* **Efectos Gráficos Secundarios (`IMG_0275`)**: *Antialiasing, Sombras en tiempo real, Ragdoll, Superresolución, Sombreado de velocidad variable, SSAO y Vibración por explosión* todos en **`NO`**.
* **Calibración de Audio Pro (`IMG_0276` – `IMG_0277`)**:
  * **Volumen Principal**: `100`
  * **Volumen de Efectos**: Subir de `60` a **`100`** (pasos, deslizamientos, recargas y uso de placas).
  * **Volumen de la IU**: Bajar de `80` a **`30`** (evita que el sonido de medallas tape los pasos enemigos).
  * **Volumen de la Música**: Bajar de `35` a **`0`**.
  * **Volumen Ambiental**: Mantener en **`0 (NO)`**.
  * **Dolby Atmos**: Cambiar de `NO` a **`SÍ`**.

---

## 3. Matriz Universal de Sensibilidad (iPad Serie M, iPhone y Android)

| Parámetro | Tu Galería (`IMG_0279-0284`) | iPad Pro 11" (M1/M2/M4/M5) [1.0x] | iPad Pro 12.9"/13" [1.12x] | iPad Mini 8 (M6) / 8.3" [0.90x] | Teléfonos 120Hz (iPhone Pro / Android) [1.18x] |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Modo de Rotación** | `Acel. (190)` ❌ | **Vel. Fija** (o `Acel. 100`) | **Acel. Distancia (`100`)** | **Vel. Fija** | **Acel. Velocidad (`115`)** |
| **Vincular con resolución** | `SÍ` ❌ | **`NO`** | **`NO`** | **`NO`** | **`NO`** |
| **Cámara — Estándar (Dirección)** | `108` | **`125` (MJ) / `135` (BR)** | **`140` / `151`** | **`113` / `122`** | **`148` / `159`** |
| **Cámara — Apuntado (ADS)** | `120` | **`120` (MJ) / `122` (BR)** | **`134` / `137`** | **`108` / `110`** | **`142` / `144`** |
| **Cámara — Punto Rojo / Holo** | `123` | **`120` (MJ) / `122` (BR)** | **`134` / `137`** | **`108` / `110`** | **`142` / `144`** |
| **Cámara — Mira Táctica (1.5x)** | `120` | **`105` (MJ) / `108` (BR)** | **`118` / `121`** | **`95` / `97`** | **`124` / `127`** |
| **Cámara — Mira Precisión (HDR)** | `111` | **`95` (MJ) / `90` (BR)** | **`106` / `101`** | **`86` / `81`** | **`112` / `106`** |
| **Cámara — Mira X3 / X4** | `60 / 295` ❌ | **`75 / 70` (MJ)** | **`84 / 78`** | **`68 / 63`** | **`88 / 83`** |
| **Cámara — Giro Vertical** | `135` | **`115` (MJ) / `120` (BR)** | **`129` / `134`** | **`104` / `108`** | **`136` / `142`** |
| **Disparo — Estándar (Cadera)** | `300` ❌ | **`128` (MJ) / `135` (BR)** | **`143` / `151`** | **`115` / `122`** | **`151` / `159`** |
| **Disparo — Apuntado (ADS)** | `110` | **`123` (MJ) / `125` (BR)** | **`138` / `140`** | **`111` / `113`** | **`145` / `148`** |
| **Disparo — Punto Rojo / Holo** | `113` | **`123` (MJ) / `125` (BR)** | **`138` / `140`** | **`111` / `113`** | **`145` / `148`** |
| **Disparo — Mira Precisión (HDR)** | `115` | **`95` (MJ) / `90` (BR)** | **`106` / `101`** | **`86` / `81`** | **`112` / `106`** |
| **Disparo — Giro Vertical** | `85` ❌ | **`122` (MJ) / `125` (BR)** | **`137` / `140`** | **`110` / `113`** | **`144` / `148`** |
| **Giroscopio (Cám / Disp ADS)** | `30 / 30` | **`40 / 25`** | **`NO` (Por peso)** | **`75 / 55`** | **`95 / 75`** |
| **Giroscopio (Cám / Disp Sniper)** | `0 / 10` ❌ | **`22 / 18`** | **`NO`** | **`45 / 35`** | **`55 / 45`** |