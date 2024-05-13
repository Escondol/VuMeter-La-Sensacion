<div align="center">
  <h1 align="center">Vu Meter La Sensación</h1>
  <img src="https://github.com/Escondol/VuMeter-La-Sensacion/assets/86692164/5f61a3b6-ce13-4c3a-9c71-53234667689b">
</div>

## Descripción del proyecto
El Vúmetro es un dispositivo indicador comúnmente encontrado en equipos de audio, diseñado para visualizar el nivel de señal en unidades de volumen. En este proyecto particular, se ha implementado un Vúmetro utilizando tiras LED que representan visualmente el nivel de señal de audio mediante colores: azul, verde y rojo, correspondientes a distintos niveles de intensidad.

La construcción de este Vúmetro se basa en el funcionamiento de los amplificadores operacionales (OPAMPs) operando en modo comparador, junto con su capacidad de amplificación al estar configurados en el modo no inversor. Esta configuración permite detectar y amplificar las señales de audio, generando niveles de voltaje que son utilizados para activar las distintas secciones de la tira LED, proporcionando así una representación visual clara del nivel de señal.

Mediante la combinación de componentes electrónicos y el diseño adecuado de circuitos, este Vúmetro ofrece una forma efectiva y precisa de monitorear el nivel de señal de audio, lo que lo hace útil en una variedad de aplicaciones relacionadas con el sonido y la música.

## Diseño
La alimentación de este Vúmetro es dual, utilizando un OPAMP para gestionar la ganancia de la señal de entrada, lo cual ha demostrado ser efectivo. Para la entrada de audio, se emplea un conector jack macho de 3.5mm, permitiendo el paso de ambas señales (izquierda y derecha) hacia un potenciómetro doble para controlar el volumen de la música. Posteriormente, las señales pasan por resistencias para ser unificadas y luego ingresan al OPAMP en modo no inversor para su amplificación, con la opción de ajustar la ganancia mediante un potenciómetro. Luego, se introducen en un OPAMP en modo seguidor para preservar la señal de posibles daños por carga. Finalmente, se rectifica la señal y se compara mediante OPAMPs en modo comparador, junto con divisores de voltaje formados por varias resistencias. 

En la salida, se utiliza un conector jack hembra de audio, posibilitando la conexión mediante un cable jack macho-macho al amplificador o radio estéreo deseado.

## Técnologías Utilizadas

## Creditos y Contactos
- Contreras, Dojanni E.
- Segura, Gabrir
