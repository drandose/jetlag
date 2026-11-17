# Jetlag

Web de la agencia de viajes Jetlag. Proyecto en equipo del módulo de Desarrollo de interfaces, 2º de DAM.

La agencia es ficticia y generalista: paquetes de vuelo y hotel, destinos de varios continentes y ofertas.

## Tecnologías

- HTML
- CSS
- JavaScript

No se usan librerías ni frameworks. La web es solo la parte visual: no tiene servidor ni base de datos. Los formularios se validan con JavaScript y los datos no se guardan.

## Pantallas

| Pantalla | Responsable | Rama |
|---|---|---|
| Elementos comunes (cabecera, pie y estilos) | @drandose | `comun` |
| Inicio | @drandose | `inicio` |
| Nosotros | @drandose | `nosotros` |
| Explorar viajes | @Tonyjcob | `explorar-viajes` |
| Ficha de paquete | @Tonyjcob | `ficha-paquete` |
| Blog | @Tonyjcob | `blog` |
| Reserva | @sergiorodriguezm11-bit | `reserva` |
| Confirmación de reserva | @sergiorodriguezm11-bit | `confirmacion-reserva` |
| Contacto | @sergiorodriguezm11-bit | `contacto` |

El recorrido principal es: Inicio, Explorar viajes, Ficha de paquete, Reserva y Confirmación de reserva.

## Diseño

El diseño parte de un wireframe de Figma con 8 pantallas de escritorio de 1440 px de ancho.

La tipografía es Inter. Los colores están definidos una sola vez como variables de CSS:

| Nombre | Color |
|---|---|
| Principal | `#0B6E5A` |
| Acento | `#C9431A` |
| Oscuro | `#0A2E27` |
| Fondo alterno | `#F2F7F5` |
| Texto | `#1B2B27` |
| Texto secundario | `#5B6B66` |
| Bordes | `#D8E3DF` |
| Blanco | `#FFFFFF` |

## Estructura de archivos

Cada pantalla tiene su propio archivo HTML, con el mismo nombre que su rama:

| Pantalla | Archivo |
|---|---|
| Inicio | `index.html` |
| Nosotros | `nosotros.html` |
| Explorar viajes | `explorar-viajes.html` |
| Ficha de paquete | `ficha-paquete.html` |
| Blog | `blog.html` |
| Reserva | `reserva.html` |
| Confirmación de reserva | `confirmacion-reserva.html` |
| Contacto | `contacto.html` |

Carpetas:

- `css/`: `comun.css` con los estilos compartidos y un archivo por pantalla (`inicio.css`, `blog.css`...).
- `js/`: un archivo por pantalla que lo necesite.
- `img/`: las imágenes.

Todos los nombres van en minúsculas, sin tildes ni espacios.

## Cómo trabajamos

1. Nadie sube cambios directamente a `main`.
2. Cada pantalla se hace en su propia rama.
3. Al terminar se abre un pull request hacia `main`.
4. Otro miembro del equipo lo revisa y lo aprueba.
5. Con la aprobación, se une a `main`.

## Cómo ver la web

Descarga el repositorio y abre el archivo `index.html` en el navegador.
