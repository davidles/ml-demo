## VIEWPORT 

Es la parte visible del navegador en la que se puede ver el contenido de nuestra página sin hacer scroll

## Medidas relativas
Una medida depende de su contexto
Una medida varía y se adapta en función del contexto
Dependiendo de qué medida elijamos será relativa a:
- el contenedor padre
- el tamaño de la fuente del sitio ( html )
- el tamaño de la fuente del padre
- el tamaño del viewport

## Medidas absolutas

La  medida no depende de su contexto.

-------------------------------------------------------------

### Porcentaje
Siempre estará en función del elemento padre

### EMS
Siempre relativo al font-size del elemento actual o padre

### REMS
Siempre relativo al font-size del elemento root (raíz) < html > = 16px

### Viewport
vw: relativo al ancho total del viewport

vh: relativo al alto total

50vw será equivalente al 50% del ancho de viewport

### Media Queries
Conjunto de reglas CSS para cambiar estilos en función del dispositivo

La mayoría de los estilos estará por fuera ( pensando mobile first )

Dentro de cada media querie solo lo que se necesita ajustar para ese breakpoint

(min-width) desde este ancho hacia arriba -> mobile first

(max-width) desde este ancho hacia abajo  -> desktop first

Ejemplo
@media ( min-width: 460px)
