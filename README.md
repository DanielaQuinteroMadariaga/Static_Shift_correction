# Integración multifísica para la corrección del desplazamiento estático en métodos eléctricos y disminución de la incertidumbre en los modelos del subsuelo

Este repositorio contiene los códigos en Python desarrollados para mi tesis de pregado, que tuvo como objetivo observar, cuantificar y corregir el desplazamiento estático de los datos SEV y MT, utilizando un enfoque multifísico, integrando los datos SEDT.

## Estructura

FASE 1. Contiene los notebooks para el modelamiento computacional de datos SEV, SEDT y MT, y el escalamiento de los datos para poder observar el desplazamiento estático. Asimismo, contiene los datos sintéticos generados a partir del modelamiento.

FASE 2. Contiene los notebooks para realizar la inversión de los datos SEV y MT teóricos y desplazados. Además, para obtener los gráficos de dispersión asociados a la incertidumbre en los modelos obtenidos por el desplazamiento de los datos, con respecto a los modelos teóricos.

FASE 3. Contiene los notebooks con la implementación de los flujos de trabajo propuestos para corregir los datos SEV y MT, tanto en datos sintéticos como en datos reales. Se encuentran también los datos reales utilizados para la implementación.

## Flujo de trabajo para los datos MT

![Flujo de trabajo para los datos MT](https://github.com/DanielaQuinteroMadariaga/Static_Shift_correction/blob/main/FlujodeTrabajoMT.svg)

## Flujo de trabajo para los datos SEV

![Flujo de trabajo para los datos SEV](https://github.com/DanielaQuinteroMadariaga/Static_Shift_correction/blob/main/FlujodeTrabajoSEV.svg)

## Atribución

Los autores le agradecen al Semillero de Investigación en Geofísica Aplicada y Computacional (SIGAC), de la Universidad Industrial de Santander por proporcionar los datos usados en este repositorio, los cuales están protegidos bajo una licencia de acceso libre y se encuentran publicados en la página web: https://sigacuis.github.io/Repositorio.html

El desarrollo de los códigos se realizó basándose en los tutoriales de de SimPEG sobre modelamiento e inversión de datos geofísicos, que está licenciado bajo la Licencia MIT. Copyright (c) 2013-2024 SimPEG Developers. (https://github.com/simpeg/simpeg/blob/main/LICENSE).

## Créditos

- **Daniela Quintero**  
  📧 yejoandajudi200305@gmail.com  
  🔗 [LinkedIn](https://www.linkedin.com/in/geodanielaquintero/)  

- **Paul Goyes**  
  📧 goyes.yesid@gmail.com  
  🔗 [LinkedIn](https://www.linkedin.com/in/paul-goyes)  

Este código se encuentra protegido bajo una licencia de libre acceso que tiene las siguientes condiciones:

- Se requiere la preservación de los avisos de derechos de autor y licencia
- Se prohibe el uso de estos códigos con fines lucrativos
- Los autores no se hacen responsables del uso de los códigos por parte de terceros
- En caso de modificaciones al código, deben especificarse en un apartado donde se cite la fuente original de este:https://github.com/DanielaQuinteroMadariaga/Static_Shift_correction
- No se permite la publicación de este código en otras plataformas bajo ninguna circunstancia sin consentimiento de los autores

Los autores prohiben eliminar, borrar o modificar este apartado.
