# Coche RC Impreso en 3D

He diseñado e impreso un coche en PLA. Este proyecto me ha permitido iniciarme en el mundo del CAD y la impresión 3D. Además, he tenido que resolver problemas relacionados con el funcionamiento y los mecanismos del coche. De momento, solo está listo el diseño; todavía me falta comprar algunas piezas, conectar la electrónica y programarlo para que funcione.

## Diseño y Funcionamiento

Para el diseño del prototipo, he seguido tres enfoques principales:

- **SUSPENSIÓN:**  
  Funciona mediante un mecanismo de 4 barras y un amortiguador encargado de absorber las vibraciones.

- **DIRECCIÓN:**  
  El coche tiene una dirección Ackerman modificada con un mecanismo de 4 barras para que pueda ser movida por el brazo del servo.

- **TRANSMISIÓN:**  
  El prototipo funciona con un solo motor que transmite la potencia a las ruedas traseras. El eje del motor está conectado a un engranaje Z11, que transmite la potencia a otro engranaje Z40 para reducir la velocidad de giro. Además, tiene incorporado un diferencial que le permite tomar curvas correctamente.

- **ESTRUCTURA:**  
  El diseño de la base, la posición de cada componente y los soportes aseguran un diseño modular y ajustable para futuros cambios.

## Piezas Utilizadas

- Motor brushless T21
- Variador para motor brushless
- Batería de 7,4 voltios (2S) LiPo/LiIon
- Emisor y receptor de radio (todavía no lo tengo; es posible que lo haga con Arduino)
- Ruedas
- Diferencial
- 2 ejes cardán
- Piñón Z11 M0.8
- 8 rodamientos
- Varilla roscada M3 y M4
- Tornillos y tuercas M3

## Instrucciones de Impresión

Descargar los archivos de la carpeta STL e imprimir directamente. Yo utilicé, en general, un relleno del 20%. Para piezas sometidas a mayor tensión, como los engranajes y la dirección, aumenté el relleno al 35%.

