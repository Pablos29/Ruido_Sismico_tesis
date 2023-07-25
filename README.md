# Análisis del ruido sísmico y su correlación con el confinamiento por COVID-19 en la ciudad de Querétaro, México. 
<img src="./img/detalle_onda_git.png" alt="Detalle de onda" style="height: 100%; width: 100%;" />


## Contenido
*Este repositorio contiene los Jupyter Notebooks utilizados en mi tesis, los cuales han sido fundamentales para el procesamiento de ruido sísmico y la obtención de las figuras necesarias. El objetivo principal de este estudio es analizar la relación entre la actividad antropogénica y las variaciones en el ruido sísmico durante el período de confinamiento por COVID-19 en la zona metropolitana sur de Querétaro, México.*

Se requiere:

- Python
- ObsPy (y sus dependencias)
- Pandas
- NumPy
- Matplotlib
- Google Colab

El repositorio consta de dos cuadernos de trabajo, dentro de [Cálculo de PPSD](Calculo_PPSD.ipynb) se tiene el cálculo de los PPSD y de los RMS sísmicos, para ser exportados en archvios .cvs. Y mediante diversas ténicas de análisis en el cuaderno de trabajo [Figuras](Figuras.ipynb) se lleva a cabo la vizualización de los RMS sísmicos, obteniendo figuras como:

- Espectrograma de potencia y desplazamiento normalizado
<img src="./img/Espectrograma_Desplazamiento_REBDD.png" alt="Espectrograma" style="height: 85%; width: 85%;" />

- RMS del desplazamiento sísmico con las fases del semáforo epidemiológico
<img src="./img/Des_RF6B5_total_(6.0-18.0)Hz.png" alt="RMS_total" style="height: 85%; width: 85%;" />

- También con una resolución de cada año de datos
<img src="./img/Des_RF6B5_2020_(6.0-18.0)Hz.png" alt="RMS_anhio" style="height: 85%; width: 85%;" />

- Diagramas de reloj para observar el comportamiento del nivel de ruido por hora y día de la semana
<div style="display: flex;">
  <img src="./img/Rsemana_R6BB7_antes_(6.0-18.0)Hz.png" alt="Reloj_antes" style="height: 45%; width: 45%; margin-right: 10px;" />
  <img src="./img/Rsemana_R6BB7_durante_(6.0-18.0)Hz.png" alt="Reloj_durante" style="height: 45%; width: 45%;" />
</div>

- La concatenación del ruido diario para el calculo de el ruido medio diario
<img src="./img/Rlunes_RF6B5_antes_(6.0-18.0)Hz.png" alt="lunes_concatenado" style="height: 45%; width: 45%;" />

  
## Instalación
Este proyecto no requiere una instalación específica, ya que los Jupyter Notebooks pueden ejecutarse en entornos locales o en servicios en la nube compatibles con Python como Google Colab.

## Contribución
Si deseas contribuir en este proyecto:
- Haz un fork de este repositorio y clónalo en tu cuenta de GitHub.
- Crea una nueva rama para tu contribución.
- Realiza tus modificaciones y mejoras.
- Asegúrate de incluir pruebas si es necesario.
- Envía un pull request para revisar tus cambios.

## Licencia 
Este proyecto esta bajo la Licencia de MIT. Consulta el archivo [LICENSE](LICENSE) para mas detalles.


## Contacto
Si tienes alguna pregunta o sugerencia relacionada con este proyecto, puedes contactarme a través de mi correo electrónico: juanpablosanchez110@gmail.com

