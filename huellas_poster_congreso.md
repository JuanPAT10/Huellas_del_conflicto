# Póster del congreso: decisiones, geometría, figuras y códigos QR

Póster conjunto de los tres proyectos para el congreso de la Facultad de
Ingeniería, Tecnología y Ciencias Básicas de UNICAFAM. Lo presentan Juan Pablo
Aguirre Tíjaro y Anderson Jawarlan Vargas Ruiz. Armado el 12/11/2026 sobre la
plantilla institucional `Plantilla_Póster_2025-I.pptx`.

Archivo vigente: `Poster_Huellas_del_conflicto_v3.pptx`, con las tres figuras y
los tres códigos QR insertados. Este documento guarda todo lo necesario para
reconstruirlo o modificarlo sin tenerlo delante.

## Corrección del 12/11/2026 que conviene no perder

La primera versión del carril 2 se escribió con las cifras de
`claude/huellas_decisiones_y_hallazgos.md`, sección «Capa predictiva (KDD, 3
iteraciones)», que describe una iteración anterior y ya no corresponde al
cuaderno final de Analítica Predictiva. Decía que la pregunta era cuántos
registros habrá el año siguiente, que el panel eran 1.217 series de 1989 a 2024,
que la prueba era 2022–2024 con un error de 24,6 % y que el modelo no le ganaba
a la persistencia. Nada de eso es del proyecto entregado.

Lo que hace el cuaderno final: predice el incremento mensual del registro por
departamento, hecho victimizante y año de ocurrencia, es decir, cuánto crece el
registro de un corte administrativo al siguiente. Y sí les gana a las líneas
base. Al usar el registro de decisiones como fuente de cifras hay que comprobar
siempre contra el cuaderno vigente: ese documento acumula iteraciones
descartadas.

## Lo que impone la plantilla

- Lienzo de 70 × 90 cm. Encabezado institucional de 13,64 cm con los logos, la
  elipse decorativa y el bloque de título; no se toca.
- Dos columnas de 32 cm en x = 1,98 y x = 35,91, con calle de 1,93 cm. Alto útil
  de 15,20 a 86,80 cm, es decir, 71,6 cm.
- Tipografía: Poppins 37,89 pt en los títulos de sección y 24,63 pt en el cuerpo;
  Montserrat 54/33/30/21 pt en el bloque de título.
- Siete secciones fijas con un icono de 2,54 cm al final de cada barra.
- Regla de la guía: el título va con iniciales mayúsculas y preposiciones en
  minúscula. Contradice la norma de estilo oración del proyecto; para el título
  manda la plantilla y el resto del póster queda en estilo oración.
- Los dos textos en rojo ya están borrados.
- El azul institucional de la banda del encabezado es `#0064B0`. Está declarado
  en el XML de la diapositiva y es el color dominante del render. De ahí sale la
  paleta de la bibliografía y de la página pública del proyecto.

## Presupuesto de texto, que es la restricción real

A 24,63 pt en una columna de 32 cm caben del orden de 71 caracteres por línea y
1,04 cm por línea. Referencias, que la plantilla obliga a 16 pt, admite unas
nueve líneas: cuatro entradas APA, cinco si son cortas.

La primera versión tenía unas 700 palabras y cuatro anclajes visuales. La versión
vigente tiene unas 420 palabras y diez anclajes, porque se convirtió texto en
gráfico en vez de recortarlo: cifra grande y barra partida en la introducción,
esquema de tres carriles en objetivos, tabla de tres vías y diagrama de fases en
metodología, y una cifra protagonista a 46 pt en cada carril de resultados.

## Título y autoría

- Nombre: «Huellas del Conflicto», a 48 pt.
- Subtítulo: «Explicar, Pronosticar y Distinguir en el Registro Único de
  Víctimas», a 27 pt. Un verbo por entrega, en el orden de los carriles.
- Autores en el encabezado: Juan Pablo Aguirre Tíjaro · Anderson Jawarlan Vargas
  Ruiz. Decisión tomada: no se marca autoría por carril.
- El bloque de título de la plantilla ancla el texto abajo y lo empuja fuera de
  la banda azul; se eliminó y se reemplazó por un cuadro propio en L = 19,30,
  T = 2,20, W = 32,00, H = 11,20, que esquiva el logo del congreso (termina en
  18,77) y el de Unicafam (empieza en 52,35).

## Geometría, en centímetros

Columna izquierda, L = 1,98, W = 32,00:

| Bloque | Arriba | Alto |
|---|---|---|
| Introducción, barra | 15,20 | 2,65 |
| Introducción, contenido | 18,22 | 16,78 |
| Objetivos, barra | 35,60 | 2,65 |
| Objetivos, contenido | 38,60 | 13,10 |
| Metodología, barra | 52,30 | 2,65 |
| Metodología, contenido | 55,30 | 31,50 |

Dentro de introducción: párrafo de entrada; cifra 10.397.626 a 54 pt centrada en
T = 22,20; pie a 16 pt en 24,85; rótulo de la barra en 26,40; barra partida
52 / 48 en 27,50 con alto 1,70 (tramo azul 16,12, tramo claro 14,88); etiquetas
en 29,30; párrafo de cierre en 31,20.

Dentro de objetivos: objetivo general en el marcador; caja «Registro Único de
Víctimas» en L = 8,68, T = 41,90, W = 18,00, H = 2,30; conectores en 44,20 y
45,15; tres cajas de carril en T = 46,00, W = 9,80, H = 5,30, en x = 2,48, 12,78
y 23,08.

Dentro de metodología: párrafo de fuente y reglas; tabla de tres vías en
L = 1,98, T = 61,30, W = 32,00, H = 19,00, con columnas de 4,60 / 6,20 / 6,20 /
8,20 / 6,80; rótulo de fases en 80,60 y cinco cajas en 81,90 de 5,60 × 2,60
separadas 6,35. Las filas de la tabla son, en orden, cabecera, Explicar,
Pronosticar y Distinguir: al editarla con python-pptx, Pronosticar es el índice
2 y no el 1.

Columna derecha, L = 35,91, W = 32,00:

| Bloque | Arriba | Alto |
|---|---|---|
| Resultados, barra | 15,20 | 2,65 |
| Carril 1 | 18,20 | 13,80 |
| Carril 2 | 32,40 | 13,80 |
| Carril 3 | 46,60 | 13,80 |
| Conclusiones, barra | 61,00 | 2,65 |
| Conclusiones, contenido | 64,00 | 12,50 |
| Referencias, barra | 77,10 | 2,65 |
| Referencias, contenido | 79,95 | 6,85, ancho 19,60 |
| Franja de códigos QR | 80,10 | 6,70, ancho 11,81 |

Dentro de cada carril, con T el inicio del carril: título en T + 0,15, alto 1,45;
tarjeta blanca de figura en L = 36,31, T + 1,75, W = 18,00, H = 11,15, con la
imagen centrada dentro y escalada a su proporción nativa; cifra grande a 46 pt en
L = 54,81, T + 1,90, W = 13,10; pie de la cifra en T + 4,25; prosa a 16 pt en
T + 6,60.

## Paleta

Tinta 292934. Azul de barras y cifras 3B4C5E, azul medio 4C5A6A. Carriles:
DDE3E9 con acento 3B4C5E para Explicar, E2E8E4 con acento 4A6655 para
Pronosticar, EFE6D9 con acento 7A5C36 para Distinguir. Gris de pies 5F5E5A,
fondo suave F5F5F2, borde C2CAD2, tarjeta de figura blanca con borde D8DEE4.

La bibliografía y la página pública del proyecto usan el azul institucional
0064B0 con 004C85 y 00365E. Si alguna vez se rehace el póster conviene llevarlo
también a esa escala, para que las tres piezas coincidan.

## Figuras insertadas

Las tres salen de las carpetas `Documentos/figuras` de cada proyecto, en PDF
rasterizado a 300 dpi para que impriman nítidas a 18 cm de ancho.

| Carril | Archivo | Proyecto | Tamaño en el póster |
|---|---|---|---|
| 1 · Explicar | `fig01_serie_nacional` | Regresiones lineales | 17,13 × 11,15 cm |
| 2 · Pronosticar | `fig09_intervalos_prueba` | Analítica Predictiva | 18,00 × 8,00 cm |
| 3 · Distinguir | `fig18_puntos_de_cambio` | Machine Learning | 18,00 × 6,45 cm |

Descartadas y por qué: `fig03_especificaciones`, de Regresiones, cuenta el carril
entero en dos paneles con el contrafactual y los dos Durbin-Watson, y es la más
informativa, pero se eligió `fig01_serie_nacional` por legibilidad a distancia y
por las anotaciones históricas. `fig24_curvas_clasificador`, de Machine Learning,
lleva tres paneles y una leyenda de seis modelos: a dos metros no se lee.

Las tres figuras se produjeron para una columna de 16,7 cm en LaTeX, así que su
tipografía interna es la del informe. A 18 cm en el póster se leen de cerca, no a
dos metros. Si se quisieran legibles a distancia habría que regenerarlas con
fuentes mayores, lo que obliga a reejecutar los cuadernos.

## Códigos QR

Tres cuadros de 3,35 cm en T = 81,90, en x = 56,55, 60,35 y 64,15, con rótulos
debajo en 85,45. Generados con corrección de errores M, borde de dos módulos y
módulos en negro puro, que es lo que más fiabilidad da en impresión. Decodificados
desde el PDF del póster a 300 dpi para comprobar que se leen.

| Rótulo | Destino |
|---|---|
| Bibliografía | https://juanpat10.github.io/Huellas_del_conflicto/bibliografia.html |
| Presentación | https://juanpat10.github.io/Huellas_del_conflicto/ |
| Repositorio | https://github.com/JuanPAT10/Huellas_del_conflicto |

Apuntan al repositorio público `JuanPAT10/Huellas_del_conflicto`, creado el
12/11/2026, que contiene solo la página de presentación y la bibliografía. El
código, los cuadernos y los informes irán a un repositorio privado aparte,
`huellas-del-conflicto-analisis`, mientras las entregas se evalúan y se define la
licencia.

Advertencia: renombrar el repositorio público rompe los tres códigos impresos.
Si hay que renombrarlo, hay que regenerar los códigos y reimprimir.

## Pendientes antes de imprimir

1. La fecha y los ordinales del congreso. La plantilla traía «Noviembre 13 de
   2024»; quedó «Noviembre de 2026» sin día, pendiente de confirmar con la
   facultad.
2. Las cuatro referencias puestas son provisionales; conviene reemplazarlas por
   las entradas exactas del `referencias.bib` del proyecto.
3. Comprobar que GitHub Pages esté publicado antes de imprimir, o los dos
   primeros códigos llevarán a un error.

## Decisión en suspenso

Se evaluó añadir un mapa coroplético de Colombia como ayuda visual adicional. Hay
datos para construirlo, pero no cabe sin sacrificar el diagrama de fases o una de
las tres figuras de resultados. Queda pendiente de decisión del autor.
