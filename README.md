# AICare
Aplicación en Android para el Modelo de Filtro para Sistemas Complejos.

## Descripción

Desarrollo en Android para la tesis "Filtro para sistemas complejos tipo caja negra sobre
dispositivos móviles" de la Maestría en Ciencias en Sistemas Computacionales
Móviles cursada en la Escuela Superior de Cómputo del Instituto Politécnico Nacional.
El manejo de la base de datos se realiza utilizando SQLite.
Para la representación gráfica se utiliza la libreria MPAndroidChart.
Los datos en serie de tiempo deben ser guardados en archivos de texto plano, un archivo por cada señal, en una carpeta llamada "CarpetaDePrueba" en el directorio raíz del dispositivo android.

## Funcionamiento

* Layout Principal - Permite navegar entre las diferentes opciones de la aplicación: Perfil, Señales, Registros y Análsiis.

![01](https://user-images.githubusercontent.com/58958653/71495258-ac180880-2812-11ea-88fd-467190ae17e6.png)

  - Perfil - Permite registrar algunos datos sobre el usuario de la aplicación.
  
  ![02](https://user-images.githubusercontent.com/58958653/71495453-80e1e900-2813-11ea-9732-509b527f4b3c.png)
  
  - Señales - Permite administrar las señales que serán utiliadas para el análisis del sistema.
    - Rangos - Permite administrar los distintos rangos de pertenencia de la señal de interés.
    - Función de membresía - Muestra la función de membresía de la señal elegida con base a la condiciones descritas en los rangos de pertenencia.
    
  ![03](https://user-images.githubusercontent.com/58958653/71495455-82abac80-2813-11ea-897f-7adf961cec3f.png) ![04](https://user-images.githubusercontent.com/58958653/71495457-85a69d00-2813-11ea-9e2b-972bf009c042.png) ![05](https://user-images.githubusercontent.com/58958653/71495460-8808f700-2813-11ea-8485-20804760b604.png)

  - Registros - Permite elegir una de las señales disponibles para mostrar dos gráficos, uno de los valores reales registrados para a señal elegida y uno más para mostrar la distribución de los valores según los rangos de pertenencia.
  
  ![06](https://user-images.githubusercontent.com/58958653/71495462-8a6b5100-2813-11ea-96fe-ddc56ea938f0.png) ![07](https://user-images.githubusercontent.com/58958653/71495465-8ccdab00-2813-11ea-9104-91d28f6ff804.png)

  - Opciones de análisis - Permite seleccionar una o varias de las señales registradas para mostrar los resultados gráficos del análisis tanto del filtro estocástico lineal como de la valoración difusa.
  
  ![08](https://user-images.githubusercontent.com/58958653/71495467-8f300500-2813-11ea-9fc0-d7270cf216bd.png) ![09](https://user-images.githubusercontent.com/58958653/71495469-91925f00-2813-11ea-9c41-ae9ca3544a2a.png) ![10](https://user-images.githubusercontent.com/58958653/71495470-935c2280-2813-11ea-8256-e0049fd73ae3.png)
  

Nota: para los valores aquí proporcionados, es conveniente utilizar la configuración de las señales de acuerdo al archivo "database_values.html", la cual se realiza desde la opción "Señales" del menú principal.
  
  
