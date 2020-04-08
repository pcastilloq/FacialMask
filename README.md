# FacialMask
[Español]

## Protector Facial Imprimible en 3D

En el repositorio se encuentran dos archivos STL.

* Mask_Oficio.stl: 

Corresponde al modelo de la visera para protector facial, obtenido desde este [link](https://foro.coronavirusmakers.org/).

Está diseñado para usarse junto a una mica transparente tamaño oficio. Adicionalmente debe amarrarse un elástico en la parte posterior.

* Mask_Oficio_mod.stl:

Es una version modificada del STL anterior, reduciendo la cantidad de material para una mayor cantidad de impresiones. Se esta trabajando en mejorar el archivo para mantener la rigidez, disminuyendo los tiempos de impresion y material utilizado.

Adicionalmente se encuentran diversos archivos .Gcode los cuales poseen los codigos para imprimir las viseras con boquillas de 0.6 mm y 0.8mm.  

Los codigos optimizan el tiempo de impresión, alcanzando aproximadamente 30 minutos por visera. 

* MaskOficio_08mm_22min.gcode:

Es el gcode para imprimir la versión Mask_Oficio.stl con una boquilla de 0.8 mm en un tiempo estimado de 28 minutos.

* MaskOficio_mod_08mm_19min.gcode:

Es el gcode para imprimir la versión Mask_Oficio_mod.stl con una boquilla de 0.8 mm en un tiempo estimado de 19 minutos.

* MaskOficio_06mm_32min.gcode:

Es el gcode para imprimir la versión Mask_Oficio.stl con una boquilla de 0.6 mm en un tiempo estimado de 32 minutos.

## Printer Settings:

>Es importantisimo **nivelar corrrectamente la cama de impresión** antes de imprimir la visera. Una mala nivelación resultaría en una mala impresión.

Definir la **Altura de Capa** cercano al 80% del diametro de la boquilla.   
|Diametro de Boquilla | Altura de Capa|
|---|---|
|0.4mm | 0.3 mm | 
|0.6 mm | 0.45 mm| 
|0.8 mm | 0.6 mm|

El **Grosor de Pared** (Wall Thickness) definanlo superior a 1.0 mm pero inferior a 2.0 mm. De esta forma todas las paredes de la visera seran consideras paredes por el slicer sin necesidad de depositar material como infill. 
|Diametro de Boquilla | Grosor de Pared |
|---|---|
|0.4mm | 1.2 mm | 
|0.6 mm | 1.8 mm| 
|0.8 mm | 1.6 mm|

**Relleno** o Infill: 0%.

**Temperaturas**. Para boquillas de gran diametro es recomendable aumentar la temperatura a al menos 220ºC. La temperatura de la cama se puede dejar en 50ºC.

|Diametro de Boquilla | Temperatura de Impresión |
|---|---|
|0.4mm | 200 ºC | 
|0.6 mm | 210 ºC| 
|0.8 mm | 220 ºC|

**Velocidad**. Respecto a la velocidad de impresión, actualmente con velocidad de 60 mm/s, 35 mm/s para las paredes y 20 mm/s en la primera capa he obtenido resultados satisfactorios.

**Sin Soportes ni Adhesión**. No son necesarios, solo consumen más material y más tiempo.

Con la configuración anterior debe poder imprimirse la visera en 1 hora con 10 minutos con una boquilla de 0.4 mm, 36 minutos con 0.6 mm, y 22 minutos con 0.8 mm
