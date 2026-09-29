# ImageConverter

**Convertidor de imágenes gratuito para Windows: arrastre sus imágenes y conviértalas en JPG · PNG · GIF · WEBP · TIFF con un solo clic.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión en coreano](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/imageconverter?lang=es)

![Pantalla de ImageConverter](images/imageconverter-en.webp)

> La ventana del programa no está traducida al español; se muestra en inglés. Los nombres de botones de abajo aparecen tal como en pantalla. El menú contextual del Explorador sí aparece en español.

## Descripción general

Una foto HEIC del iPhone que no se abre en el PC, un montón de fotos que reducir para el blog, un PDF que necesita como una imagen por página: ImageConverter se encarga.

Arrastre archivos o carpetas a la ventana y pulse el botón **Convert to**. Eso es todo. El JPG se guarda más pequeño con MozJPEG y, si fija un tamaño, la imagen se ajusta a él conservando sus proporciones. También puede convertir directamente desde el Explorador de archivos con el botón derecho.

Los resultados se guardan siempre como **archivos nuevos**. ImageConverter nunca sobrescribe los originales ni ningún archivo existente.

## Funciones principales

- **Muchas a la vez** — Añada varios archivos o carpetas enteras (subcarpetas incluidas) y conviértalos de una vez.
- **5 formatos de salida** — JPG · PNG · GIF · WEBP · TIFF.
- **Amplia compatibilidad de entrada** — JPG, PNG, GIF, BMP, WEBP, TIFF, HEIC, AVIF, PSD, PDF, SVG, TGA, ICO y más.
- **JPG más pequeños** — MozJPEG guarda la misma calidad en menos bytes.
- **Cambio de tamaño proporcional** — Fije solo el ancho o el alto; el otro sigue la proporción.
- **PDF → imágenes** — Guarda cada página de un PDF de varias páginas como una imagen propia.
- **Reconoce archivos sin extensión** — El formato se lee del contenido del archivo, no de su nombre.
- **Originales protegidos** — Si el nombre ya existe, se guarda como `photo (1).jpg`.
- **Menú contextual del Explorador** — En Windows 10 y 11, incluido el menú predeterminado de Windows 11.
- **7 idiomas** — Coreano · inglés · japonés · chino · ruso · italiano · francés. Sigue el idioma de Windows.

## Descarga / Instalación

| Tipo | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/imageconverter?lang=es) |
| Portable (ZIP) | [Descargar](https://down.kilho.net/imageconverter?lang=es&nosetup) |

Con el instalador, ImageConverter se abre en cuanto termina la instalación y se añaden la entrada del menú Inicio y el menú contextual del Explorador. Para la versión portable, descomprima el ZIP y ejecute `ImageConverter.exe`; mantenga la carpeta `vendor` junto al ejecutable. **El menú contextual del Explorador viene con el instalador.**

## Uso

### Primeros pasos

1. Inicie ImageConverter. **Home** muestra una lista de archivos vacía.
2. Arrastre a la lista las imágenes o carpetas que quiere convertir. Solo se añaden los archivos cuyo formato se reconoce; la columna **Type** muestra el formato de origen y **Status** muestra `Ready`.
3. En la casilla de tamaño, abajo a la izquierda, elija **Original**, **Width** o **Height**. Con Width o Height aparece al lado una casilla de tamaño (px).
4. Compruebe el formato de salida. El botón de abajo a la derecha lo indica, por ejemplo **Convert to JPG**. Para cambiarlo, haga **clic derecho** en el botón y elija JPG · PNG · GIF · WEBP · TIFF.
5. Pulse el botón. Aparece una barra de progreso y el estado de cada archivo pasa de `Convert` a `Success`.
6. Por defecto, los archivos convertidos se guardan en la **misma carpeta que el original**, con el mismo nombre y la nueva extensión.

### Distribución de la pantalla

**Home**

| Elemento | Qué hace |
|---|---|
| Lista de archivos | **FileName** · **Type** (formato de origen detectado) · **Status** (`Ready` / `Convert` / `Success` / `Fail`) |
| Clic derecho en la lista | **Delete** · **Delete All** |
| Elección de tamaño | **Original** · **Width** · **Height** |
| Casilla de tamaño | Elija un tamaño habitual de la lista o escriba un número (solo visible con Width o Height) |
| Botón **Convert to JPG** | Púlselo para empezar. Clic derecho para elegir el formato de salida |

**Config**

| Elemento | Qué hace |
|---|---|
| **Output Path** | **Original File Folder** o una carpeta elegida (por defecto `Escritorio\ImageConverter`). Cámbiela con el botón `…` |
| **Format** | JPG · PNG · GIF · WEBP · TIFF (el mismo ajuste que el menú del clic derecho del botón) |
| **Quality** | 40 a 100, 75 por defecto. Se aplica a los formatos con pérdida (JPG · WEBP) |

### Qué hacer cuando…

**Convertir fotos del iPhone (HEIC) a JPG**
Arrastre los archivos HEIC, o la carpeta que los contiene, a la lista, deje el formato en **JPG** y pulse. Las fotos se guardan **derechas** según la rotación registrada por el teléfono, así que no hace falta girar a mano las que salieron de lado.

**Ajustar el tamaño de fotos para un blog o una tienda en línea**
Elija **Width** en la casilla de tamaño y seleccione el ancho que quiera, por ejemplo `1280`. El alto sigue la proporción, así que nada se deforma. Para un valor que no esté en la lista, escriba el número (1 a 30000). Las fotos más estrechas que ese ancho también se llevan a él.

**Dar a todas las imágenes la misma altura, como miniaturas**
Elija **Height**: todos los resultados tienen la misma altura y cada ancho sigue su propia proporción. Útil para alinear en una fila fotos horizontales y verticales mezcladas.

**Reducir archivos para enviarlos por correo o mensajería**
Con **JPG**, MozJPEG guarda la misma calidad en un archivo más pequeño. Para reducir más, baje **Config → Quality** a unos 60 y reduzca también el tamaño con **Width**. Guardar en **WEBP** suele dar un archivo más pequeño que JPG.

**Conservar un fondo transparente**
Los PNG, SVG y otras imágenes con transparencia la conservan al guardarse en **PNG** o **WEBP**. JPG no admite transparencia, así que elija PNG o WEBP para logotipos e iconos.

**Exportar un logotipo SVG como PNG al tamaño necesario**
Añada el SVG, fije **Width** en algo como `512` y convierta a **PNG**. En lugar de ampliar una imagen pequeña, **la dibuja de nuevo a ese tamaño**, así que queda nítida aunque sea grande.

**Convertir un PDF en una imagen por página**
Añada un PDF y convierta: cada página se guarda en un archivo numerado — `document-001.jpg`, `document-002.jpg` … Con **Original**, las páginas salen al tamaño de pantalla; con **Width**, se dibujan nítidas a ese ancho. El fondo es blanco. El estado muestra `Success` cuando todas las páginas se han guardado.

**Pasar un GIF animado a WEBP**
Cuando el formato de salida es **GIF** o **WEBP**, se conservan todos los fotogramas de la animación. Convertir un GIF animado a WEBP mantiene el movimiento y reduce el tamaño. Al guardar en JPG · PNG · TIFF se guarda el primer fotograma.

**Guardar en WEBP sin perder calidad**
Suba **Quality** a **100** y el WEBP se guarda sin pérdida. Sirve para conservar una copia idéntica píxel a píxel y más pequeña que un PNG.

**Convertir todas las imágenes de una carpeta**
Arrastre una carpeta entera: se recorren todas sus subcarpetas y solo se añaden las imágenes. Los demás archivos, como documentos o vídeos, quedan fuera automáticamente, y el mismo archivo nunca se añade dos veces.

**Archivos sin extensión o con una equivocada**
ImageConverter lee el formato del **contenido del archivo**, no de su nombre. Los archivos sin extensión, o un `.jpg` que en realidad es un PNG, se reconocen correctamente, y el resultado recibe la extensión adecuada.

**Reunir los resultados en una sola carpeta**
En **Config → Output Path**, elija la opción de carpeta de abajo y todos los resultados irán allí. Por defecto es `Escritorio\ImageConverter`, y se crea al convertir si todavía no existe. Elija otra carpeta con el botón `…`. Para dejar los resultados junto a los originales, elija **Original File Folder**.

**Ya existe un archivo con el mismo nombre**
No se sobrescribe nada. Si existe `photo.jpg`, el resultado se guarda como `photo (1).jpg`, `photo (2).jpg`, etc. Aunque reduzca un JPG a JPG, el original queda intacto.

**Convertir directamente desde el Explorador de archivos**
Seleccione una o varias imágenes en el Explorador, clic derecho → **Conversión de imagen** → **Convertir a WebP**, **Convertir a PNG** o **Convertir a JPG**. Se abre una ventana con esos archivos; elija un tamaño y pulse el botón.
- Los resultados se guardan en la **misma carpeta que los originales**, y la ventana se cierra sola al terminar.
- Haga clic derecho en otros archivos y vuelva a convertir: cada uno abre su propia ventana, así que pueden ir a la vez.
- El menú aparece al seleccionar archivos JPG · PNG · GIF · BMP · WEBP · TIFF · HEIC · AVIF · PSD · PDF · SVG · TGA.

**Obtener las mismas fotos en varios formatos**
La lista se mantiene después de convertir. Haga clic derecho en el botón, cambie el formato y pulse de nuevo para obtener los mismos archivos en otro formato.

**Ordenar la lista**
Seleccione las filas que quiere quitar (`Ctrl` · `Shift` para varias), haga clic derecho en la lista y elija **Delete**. Para vaciarla, elija **Delete All**. Las filas solo se quitan de la lista; los archivos reales no se borran.

**Detener una conversión a medias**
Cierre la ventana y se le preguntará **Stop converting and quit?** Pulse **Sí**: termina el archivo en curso y luego se cierra. Los resultados ya guardados se quedan donde están.

## Configuración

Los cambios hechos en **Config** y la elección de tamaño en Home se recuerdan automáticamente para la próxima vez.

| Elemento | Valor por defecto |
|---|---|
| Format | JPG |
| Tamaño | Original (Width 640 / Height 540) |
| Quality | 75 |
| Output Path | Original File Folder (carpeta elegida por defecto: `Escritorio\ImageConverter`) |
| Idioma | Idioma de Windows (inglés si no es compatible) |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Todo lo necesario para convertir está incluido; no hay nada más que instalar. No requiere permisos de administrador para ejecutar el programa.
- La conexión a Internet solo se usa para los avisos de nueva versión. Todas las conversiones se hacen en su PC.

## Actualizaciones

ImageConverter **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; al pulsar **Sí** se abre la página de descarga y el programa se cierra. Las nuevas versiones se publican manualmente tras una verificación interna y se anuncian en la [página de ImageConverter](https://kilho.net/imageconverter). Consulte el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

**Historial de versiones**

| Versión | Fecha | Cambios |
|---|---|---|
| 2.0.0 | 2026-09-22 | Pantalla renovada, tamaños elegidos de una lista o escritos directamente, ajustes existentes conservados tras actualizar, conversión con clic derecho en el Explorador mejorada |
| 1.6.3 | 2026-09-03 | Conversión más rápida desde el menú contextual de Windows 11, instalación de actualizaciones mejorada, conversión de PDF más nítida y documentos grandes más estables, mejor reconocimiento de HEIC · AVIF, archivos vacíos descartados de la lista desde el principio |
| 1.6.2 | 2026-08-17 | Motor de conversión de PDF mejorado para más calidad, cierre seguro durante la conversión, mayor protección de los archivos existentes, mejor compatibilidad con nombres de archivo con caracteres especiales, lista de archivos más rápida |
| 1.6.1 | 2026-07-16 | Conversión de JPG y PDF de varias páginas más fiable, mejor reconocimiento de HEIC y otros formatos, menú contextual del Explorador y ajustes más cómodos |

## Licencia

ImageConverter es **freeware**. Puede usarlo gratis y sin restricciones en cualquier lugar — empresa, casa, organismos públicos, escuela — y redistribuirlo libremente.

## Enlaces

- Sitio web: <https://kilho.net/imageconverter>
- Foro: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
