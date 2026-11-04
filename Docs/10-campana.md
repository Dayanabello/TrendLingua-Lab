# Campaña de lanzamiento: DosiExacta

Equipo TrendLinguaLab · Proyecto Trend & Tech (Lean UX)

## 1. Propósito de la campaña

Esta campaña presenta nuestra solución a la Droguería Medical 1: un dispensador robótico con piezas impresas en 3D que cuenta y entrega una dosis exacta de pastillas al oprimir un botón. La campaña se dirige a la administradora de la droguería, quien decide si la solución se adopta en el punto de atención. Por eso el tono es **confiable y seguro**. Queremos que vea la solución como un apoyo serio para el auxiliar de farmacia, que reduce las demoras en la fila y los errores de conteo.

## 2. Nombre de la solución

Evaluamos tres propuestas con una escala de 1 a 5 (5 es la mejor valoración) según tres criterios: nombre corto, recordable y asociado al beneficio.

| Nombre | Corto | Recordable | Asociado al beneficio | Total |
|---|:---:|:---:|:---:|:---:|
| DosiExacta | 4 | 5 | 5 | **14** |
| PastiCuenta | 4 | 4 | 4 | 12 |
| DosiBox | 5 | 4 | 3 | 12 |

**Nombre recomendado: DosiExacta.** Une «dosis» y «exacta», que es la promesa central de la solución: entregar la cantidad precisa de pastillas, sin conteo manual frente al cliente. Es fácil de pronunciar y de recordar, y transmite precisión y confianza.

## 3. Eslóganes

1. Cada dosis exacta, con un solo botón. ✅ **(elegido)**
2. Precisión que se entrega sola.
3. Menos fila, más confianza.

Elegimos el primero porque resume en una frase el beneficio (dosis exacta) y la forma de uso (un solo botón). Tiene 36 caracteres y se lee bien en un sticker pequeño.

## 4. Identidad visual

### Paleta de colores

Elegimos tonos que transmiten confianza y salud. No usamos negro en ningún elemento de la marca.

| Color | HEX | Uso |
|---|---|---|
| Azul confianza | `#1F5FA8` | Color principal: símbolo, nombre y títulos |
| Verde salud | `#228B63` | Color de apoyo: eslogan y detalles del símbolo |
| Celeste claro | `#E8F3FA` | Fondos de piezas, stickers y presentaciones |

### Tipografía

**Poppins** (Google Fonts, gratuita y de uso libre). Sus formas redondeadas y claras dan una imagen cercana y profesional, y se lee bien en tamaños pequeños.

## 5. Logo

El logo combina un escudo, que representa la seguridad y la confianza, con una cápsula en su interior, que representa la dosis exacta de medicamento.
La cápsula en azul y verde une la precisión técnica del dispositivo con el cuidado de la salud.

![Logo](../assets/campana/logo.png)

## 6. Stickers de lanzamiento

Preparamos una hoja de **12 stickers de 5 × 5 cm**, organizados en 3 columnas y 4 filas. Cada sticker lleva el logo, el nombre **DosiExacta** y el eslogan *Cada dosis exacta, con un solo botón*, sobre fondo celeste claro. Los entregaremos a los asistentes al lanzamiento como recordatorio de la solución.

![Hoja de stickers](../assets/campana/hoja-stickers.png)

## Elementos FabLab

Para el lanzamiento de la solución **PastiCount** preparamos dos elementos físicos que refuerzan la identidad de la campaña y la hacen recordable: una hoja de stickers y un llavero impreso en 3D. Ambos usan el logo, el nombre y el eslogan de la campaña: **«Cuenta rápido, atiende mejor»**. Los necesitamos para el **5 de noviembre**.

### Elemento 1: hoja de stickers

**Para qué sirve en la campaña.** Los stickers se entregan a las personas que prueban el prototipo y se pegan en puntos visibles del lugar de la demostración. Recuerdan la marca y el mensaje central: contar pastillas más rápido y con menos errores para reducir las demoras en las filas.

| Característica | Detalle |
|---|---|
| Medidas de cada sticker | 50 × 50 mm |
| Medidas de la hoja | Tamaño carta, 216 × 279 mm |
| Distribución | 12 stickers por hoja (3 columnas × 4 filas), con 5 mm de separación y márgenes amplios para la impresora |
| Contenido | Logo, nombre PastiCount y eslogan |
| Material | Papel adhesivo tamaño carta |
| Espesor | Aprox. 0,1 mm |
| Cantidad | 1 hoja (12 stickers) |
| Servicio | Impresión 2D a color en papel adhesivo, con corte posterior |
| Archivo | hoja-stickers.pdf |
| Tiempo estimado | 30 minutos entre impresión y corte |

### Elemento 2: llavero impreso en 3D

**Para qué sirve en la campaña.** Es el obsequio que se queda con las personas después de la presentación. Lleva el ícono y el nombre de la solución en relieve, de modo que la marca esté presente en su vida diaria.

| Característica | Detalle |
|---|---|
| Medidas | 72 × 30 × 4,2 mm |
| Diseño | Placa rectangular de esquinas redondeadas, con agujero de 5 mm de diámetro para la argolla; ícono de caja de pastillas y nombre PastiCount en relieve |
| Material | PLA |
| Espesor | 4,2 mm en total: base de 3,0 mm y relieve de 1,2 mm |
| Color | Base morada y relieve blanco |
| Cantidad | 2 llaveros |
| Servicio | Impresión 3D (filamento PLA) |
| Archivo | llavero-3d.stl |
| Tiempo estimado | Aprox. 1 h 30 min por llavero, unas 3 horas en total |

### Pasos para modelar el llavero en Tinkercad y exportarlo en STL

1. Entramos a Tinkercad, creamos un diseño nuevo y lo nombramos «Llavero PastiCount».
2. Arrastramos una **Caja** al plano de trabajo y fijamos sus medidas en 72 mm de largo, 30 mm de ancho y 3 mm de alto. Esta es la base.
3. Para redondear las esquinas, usamos una **Caja** con la opción de radio (o cilindros en las esquinas agrupados con la base) y dejamos un radio de unos 4 mm.
4. Colocamos un **Cilindro** de 5 mm de diámetro y 3 mm de alto cerca de un extremo, lo convertimos en **Hueco** y lo agrupamos con la base para crear el agujero de la argolla.
5. Armamos el ícono de caja de pastillas con formas básicas: una cápsula hecha con una caja de esquinas redondeadas y una línea divisoria. Lo ubicamos en el lado opuesto al agujero y le damos 1,2 mm de altura sobre la base.
6. Añadimos el texto «PastiCount» con la forma **Texto**, de 1,2 mm de altura, al lado del ícono. Con la herramienta **Alinear** centramos todo.
7. Asignamos el color morado a la base y el color blanco al ícono y al texto. Verificamos que la altura total sea de 4,2 mm.
8. Revisamos que todas las piezas estén apoyadas sobre la base y que el agujero atraviese el llavero.
9. Seleccionamos todo, pulsamos **Exportar** y elegimos el formato **.STL**. Guardamos el archivo como `llavero-3d.stl` y lo enviamos al FabLab.

![Elementos FabLab](../assets/fablab/foto-final.jpg)

