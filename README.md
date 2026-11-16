# Escáner de cartas

App web para iPhone y iPad que saca fotos solas de tus cartas y guarda cada carta recortada y derecha. Puedes tirarlas de a una en una caja, poner varias a la vez en una mesa o ir dando vuelta las páginas de una carpeta.

**Abrir la app:** https://arturoboza.github.io/escaner-cartas/

## Cómo se usa

1. Fija el equipo sobre la caja, la mesa o la carpeta, con la cámara trasera mirando hacia abajo y luz pareja.
2. Abre el enlace en Safari y permite el uso de la cámara.
3. Arrastra las esquinas del marco amarillo hasta cubrir la zona donde caen o pones las cartas (con una carpeta, la página).
4. Toca **Iniciar**. Con la caja o la mesa, empieza con ellas vacías. La foto sale cuando las cartas quedan quietas.
5. En **Fotos** puedes revisarlas, borrarlas y exportarlas en un ZIP o guardarlas en la app Fotos.

Para tenerla como app: en Safari, toca Compartir y luego "Añadir a pantalla de inicio".

## Modos

En **Ajustes**, en **Qué guarda cada foto**, puedes elegir:

- **Una carta, recortada y derecha.** Tiras las cartas de a una en una caja y cada foto guarda solo la carta nueva.
- **Varias cartas, cada una por separado.** Pones varias cartas en una mesa, una al lado de la otra, y cada carta se guarda como una foto aparte, en orden de lectura (por filas, de izquierda a derecha). Puedes ponerlas de a una o en tandas. Las que siguen en su lugar no se vuelven a guardar. El botón **Manual** guarda todas las que ve en ese momento.
- **Página de carpeta con bolsillos.** Eliges cuántas columnas y filas tiene la página (9, 12 o 16 bolsillos, o 4) y vas dando vuelta las páginas. Cada carta se guarda aparte, en orden de lectura. Si el borde de una carta no se distingue (por ejemplo, borde negro sobre página negra), se recorta el lugar de su bolsillo con un margen y la foto queda marcada "aproximada". Si la misma página sale dos veces, no se repite.
- **La foto completa, sin recortar.** Guarda la zona del marco amarillo tal como se ve.

Si la app no distingue bien una carta, guarda la foto completa y la marca "sin recorte" en la galería, así no se pierde ninguna.

## Para que recorte mejor

- Con la caja o la mesa, empieza con ellas vacías. La app las mira al tocar **Iniciar** y después reconoce lo que cambió.
- Usa un fondo que contraste con el borde de las cartas: oscuro para bordes claros, claro para bordes oscuros.
- Usa luz pareja, sin sombras marcadas ni reflejos en los plásticos.
- Deja el equipo paralelo a la caja, la mesa o la página, sin inclinarlo.
- Con una carpeta, saca una página por foto y haz que la página llene el marco.
- Usa cartas del mismo tamaño en cada tanda.
- Con varias cartas sueltas, no las encimes y deja un poco de espacio entre ellas.

El recorte puede fallar cuando el borde de la carta se confunde con el fondo, con la carta de abajo o con una carta vecina, o cuando la foto tiene mucho ángulo. Conviene revisar las miniaturas antes de exportar.

## Notas

- Las fotos se guardan solo en el equipo. No se suben a ningún servidor.
- La cámara solo funciona si la página se abre con https, como en el enlace de arriba.
- Todo el código está en `index.html`, sin dependencias externas.
