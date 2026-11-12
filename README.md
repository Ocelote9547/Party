
# 🎉 N3MESIS PARTY

![version](https://img.shields.io/badge/version-1.8.3%2B19-10b981)
![flutter](https://img.shields.io/badge/Flutter-3.13%2B-02569B)
![dart](https://img.shields.io/badge/Dart-3.13%2B-0175C2)
![platform](https://img.shields.io/badge/platform-Android%20%7C%20iOS%20%7C%20Web-0ea5e9)
![tests](https://img.shields.io/badge/tests-99%2B%20passing-16a34a)

**La app para grupos que convierte cualquier reunión en una fiesta.**

N3mesis Party reúne juegos para grupos, cámara retro, creación inteligente de planes, avatares personalizables y diferentes herramientas de entretenimiento en una sola aplicación.

Diseñada principalmente en español, con funciones locales y sin anuncios.

---

## ✨ Características principales

## 🎮 Juegos para grupos

Más de 14 experiencias de entretenimiento para compartir con amigos y familiares.

| Juego | Descripción |
|---|---|
| **Tabú** | Describe palabras sin mencionar los términos prohibidos. Incluye tilt, cronómetro y puntuación. |
| **¿Quién soy?** | Adivina el personaje con el móvil colocado en la frente. |
| **Adivina** | Categorías amplias con 16 × 100 palabras. |
| **Impostor** | Descubre quién desconoce la palabra secreta. |
| **Bomba** | Desactiva la bomba antes de que termine el tiempo. |
| **Dibuja y adivina** | Dibuja en un canvas y permite que los demás adivinen. |
| **Verdad o reto** | Más de 190 cartas y 80 opciones picantes. |
| **Debate** | Más de 102 temas, incluyendo opciones profundas y picantes. |
| **Dos palabras** | Encuentra la conexión entre dos palabras. |
| **Es un 10** | Juego de cartas con frases y situaciones. |
| **Mímica** | Representa palabras que solamente puede ver el actor. |
| **Pueblo duerme** | Juego de roles ocultos con lobos, vidente, cupido y ladrón. |
| **Ensalada** | Adivina entre 80 platos diferentes. |
| **Yo nunca** | Diferentes variantes, incluyendo Yo tengo un amigo y modo equipos. |
| **APT coreano** | Retos basados en ritmo. |
| **Ángeles y demonios** | Sistema persistente con servicio dedicado. |

### 🎯 Controles inteligentes

- Detección de inclinación del dispositivo.
- Calibración del sensor.
- Filtrado EMA.
- Histéresis para mejorar la detección.
- Sensibilidad configurable: Suave, Normal y Firme.
- Alternativas mediante gestos, botones y flechas.
- Compatibilidad con W/S.
- Orientación automática.
- Restauración de la orientación al abandonar el juego.

---

## 📸 Cámara Retro KODAK

Una cámara integrada con procesamiento de imagen para conseguir una estética fotográfica retro.

### Características

- Filtro inspirado en Kodak Lightroom.
- Procesamiento HDR.
- Grano fotográfico real mediante isolate.
- Procesamiento sin bloquear la interfaz.
- Reescalado mediante IA ×2 y ×3 con interruptor de activación.
- Sello de fecha integrado en la fotografía.
- Selección forzada de la lente principal (ID `0`).
- Vista previa vertical 9:16 y 4:3.
- Resolución máxima con fallback automático.
- Guardado en `DCIM/PARTY`.
- Integración con MediaScanner para mostrar las fotografías en la galería.

---

## 🗺️ Creador Inteligente de Planes V2

Una herramienta diseñada para descubrir actividades y crear planes reales según tus preferencias y ubicación.

### Preguntas y personalización

- Preguntas a pantalla completa.
- Imágenes para facilitar las elecciones.
- Selectores visuales.
- Franja horaria: mañana, tarde o noche.
- Distancia máxima configurable entre 10 y 200 km según el transporte.

### Ubicación y descubrimiento

- GPS exacto o aproximado.
- Introducción manual de una localidad.
- Autocompletado de pueblos, barrios y ciudades.
- Integración con Nominatim y OpenStreetMap.
- Photon de Komoot.
- Wikipedia.
- Fuentes de noticias web.

### Rutas y actividades

- Rutas reales de senderismo.
- Rutas de bicicleta de montaña (BTT).
- Rutas de ciclismo.
- Distancia.
- Duración estimada.
- Desnivel.

### Costes y meteorología

- Estimación del coste de la actividad.
- Cálculo del transporte según distancia y medio.
- Estimación de comida según duración.
- Información meteorológica mediante Open-Meteo.
- Penalización de actividades exteriores cuando las condiciones meteorológicas no son favorables.
- Comprobación de horarios de apertura para filtrar establecimientos cerrados en la hora prevista.

### Sistema de recomendaciones

- Interfaz de tarjetas estilo Tinder.
- Deslizar para guardar o descartar.
- Historial persistente de planes guardados.
- Rotación de recomendaciones.
- Evita repetir planes ya vistos.

---

## 💰 Economía, avatares y tienda

Party incorpora un sistema de progresión y personalización.

### Juegos

- 13 juegos desbloqueados gratuitamente.
- 5 juegos premium: Bomba, Alienígena, Secretos, Máscara y Quién es más.

### Monedas

- 100 monedas iniciales.
- +10 monedas por partida completada.

### Tienda

- Catálogo de cosméticos.
- Personalización de avatares.
- Avatar dorado por 150 monedas.

### Avatares

- 12 avatares vectoriales.
- 14 espacios personalizados.
- 2 avatares dorados exclusivos.
- Editor de elementos visuales.
- Ajuste de posición y escala de cara, sombrero, gafas y máscara.
- Personalización de fondos.
- Fotografías generadas mediante IA.

### Códigos de creador

- Códigos de 12 caracteres.
- Bóveda maestra.
- Desbloqueo de juegos.
- Desbloqueo de cosméticos y temas.
- Gestión de monedas.
- Desbloqueo del avatar dorado.

---

## 🔊 Sonido y vibración

Sistema de audio y respuesta háptica integrado en Party.

- Tonos generados y mantenidos en memoria.
- Tick de 1200 Hz.
- Acorde de éxito.
- Tono descendente de error.
- Ambientes según categoría.
- Transiciones de audio suaves.
- Fade-in de 800 ms.
- Fade-out de 500 ms.
- Volumen ambiental entre el 8 % y el 15 %.
- Reanudación de audio tras la primera interacción cuando el navegador lo requiere.
- RouteObserver para controlar cambios de pantalla.
- Pausa al pasar a segundo plano.
- Ticks de cuenta atrás en 60, 30, 15, 10 y 0.
- Controles independientes para música, sonidos y vibración.

---

## 🎨 Identidad visual — Tema Volcán B

Party utiliza una identidad visual basada en tonos volcánicos y naranjas intensos.

### Paleta principal

| Elemento | Color |
|---|---|
| Naranja principal | `#FF3D00` |
| Fondo oscuro | `#1A0A0A` |
| Fondo claro | `#FFF3E0` |

### Sistema visual

- PartyColors dinámicos.
- themeNotifier para gestionar el tema.
- Modo claro y oscuro.
- Material 3.
- Google Fonts.
- AnimatedPartyBackground.
- Transición visual de blanco y negro a color durante los juegos.
- RepaintBoundary para optimizar el repintado del fondo.

---

## 🔒 Seguridad y privacidad

Party está diseñada para mantener una experiencia sencilla y evitar dependencias innecesarias.

### Permisos utilizados

- Cámara.
- Ubicación.
- Almacenamiento.
- Acceso a medios.

### Privacidad

- Sin anuncios.
- Sin tracking publicitario.
- Sin API keys de pago.
- Preferencias y datos locales mediante SharedPreferences.
- Gestión de rutas de almacenamiento mediante path_provider.
- Sistema de códigos de un solo uso por usuario mediante `redeemed_codes`.

Algunas funciones, como la ubicación, la meteorología y las fuentes de información externas, necesitan conexión a Internet.

---

## 📋 Ficha técnica

| | |
|---|---|
| **Aplicación** | N3mesis Party |
| **Versión** | 1.8.3+19 |
| **Package** | `com.n3mesis.party` |
| **Framework** | Flutter 3.13+ |
| **Lenguaje** | Dart 3.13+ |
| **Plataformas** | Android, iOS y Web |
| **Tests** | 99+ tests verdes |
| **Análisis** | `flutter analyze` — No issues found |
| **Build** | APK debug y release verificados |

### Dependencias principales

- sensors_plus
- path_provider
- audioplayers
- vibration
- camera
- permission_handler
- image
- google_fonts
- geolocator
- geocoding
- http
- swipable_stack

---

## 🧪 Calidad y pruebas

El proyecto cuenta con pruebas para diferentes componentes y funcionalidades.

- Más de 99 tests superados.
- Pruebas de errores (`repro_errors`).
- Pruebas del creador de planes.
- Pruebas de widgets.
- Análisis estático sin incidencias.
- Builds APK de debug y release verificados.

---

## 🚀 Estado del proyecto

**En fase de estabilización.**

El desarrollo funcional de Party está avanzado. Actualmente, el objetivo es revisar los sistemas existentes, corregir errores y estabilizar especialmente el sistema de planes y su funcionamiento.

Las futuras actualizaciones se centrarán en mejorar la fiabilidad y preparar una versión estable.

---

## 📱 Distribución

Party se distribuye mediante paquetes APK a través de los canales de N3mesis Studio.

🌐 Web oficial: https://ocelote9547.github.io/party/

---

## 📋 Información para tiendas

| | |
|---|---|
| **Título corto** | PARTY — Juegos y Planes para Grupos |
| **Descripción corta** | Juegos de fiesta, creador de planes reales y cámara retro. Todo en español. |
| **Categoría propuesta** | Entretenimiento / Social |
| **Idioma principal** | Español |
| **Clasificación propuesta** | Pendiente de evaluación oficial |

---

## 🌐 N3mesis Studio

Party forma parte del ecosistema de aplicaciones de N3mesis Studio.

🌐 Web oficial: https://ocelote9547.github.io/

---

© 2026 Ocelote9547 — Todos los derechos reservados.
