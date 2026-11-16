# Escáner de cartas

App web para iPhone y iPad que saca una foto sola cada vez que cae una carta nueva en una caja, y la guarda recortada y derecha.

**Abrir la app:** https://arturoboza.github.io/escaner-cartas/

## Cómo se usa

1. Fija el equipo sobre la caja, con la cámara trasera mirando hacia abajo y luz pareja.
2. Abre el enlace en Safari y permite el uso de la cámara.
3. Arrastra las esquinas del marco amarillo hasta cubrir la zona donde caen las cartas.
4. Con la caja vacía, toca **Iniciar** y tira las cartas de a una. La foto sale cuando la carta queda quieta.
5. En **Fotos** puedes revisarlas, borrarlas y exportarlas en un ZIP o guardarlas en la app Fotos.

Para tenerla como app: en Safari, toca Compartir y luego "Añadir a pantalla de inicio".

## Recorte automático

Cada foto se guarda solo con la carta, enderezada. Si la app no distingue bien la carta, guarda la foto completa y la marca "sin recorte" en la galería, así no se pierde ninguna.

Para que recorte mejor:

- Empieza con la caja vacía. La app la mira al tocar **Iniciar** y después reconoce lo que cambió.
- Usa un fondo que contraste con el borde de las cartas: oscuro para bordes claros, claro para bordes oscuros.
- Deja el equipo paralelo al fondo de la caja, sin inclinarlo.
- Usa cartas del mismo tamaño en cada tanda. La app aprende el tamaño con las primeras.

El recorte puede fallar cuando el borde de la carta se confunde con el fondo o con la carta de abajo. Conviene revisar las miniaturas antes de exportar.

Para guardar siempre la foto completa, apaga **Recortar y enderezar la carta** en Ajustes.

## Notas

- Las fotos se guardan solo en el equipo. No se suben a ningún servidor.
- La cámara solo funciona si la página se abre con https, como en el enlace de arriba.
- Todo el código está en `index.html`, sin dependencias externas.
