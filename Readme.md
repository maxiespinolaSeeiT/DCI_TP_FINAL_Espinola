## Trabajo práctico final de la asignatura DCI ##
Este repositorio contiene el trabajo práctico final para la asignatura de Diseño de Circuitos Impresos de la carrera de posgrado de FIUBA.

* Autor: ESPINOLA MAXIMILIANO ARIEL
* Título corto del trabajo:  Cargador Batería Litio TP4056 USB-C Con Protección 1A
* Descripción: el trabajo consiste en el diseño de una placa de circuito impreso (PCB) para un cargador de baterías de ion-litio de una celda (1S), basado en el circuito integrado TP4056, con alimentación mediante conector USB-C y corriente de carga de hasta 1 A. El circuito implementará un sistema de carga en corriente constante y tensión constante (CC/CV), con tensión final de 4,2 V, e incorporará protección contra sobrecarga, sobredescarga y cortocircuitos mediante un circuito integrado de protección dedicado. El objetivo del trabajo es diseñar y verificar una PCB compacta y funcional que permita realizar la carga segura y controlada de baterías de litio.
* Cursada: DIC 2026


## Licencia de este trabajo ##
Este proyecto se distribuye bajo la licencia CERN Open Hardware Licence Version 2 – Strongly Reciprocal (CERN-OHL-S-2.0), una licencia de hardware abierto que permite utilizar, estudiar, modificar, fabricar y redistribuir el diseño de hardware, de acuerdo con sus términos y condiciones.

La licencia busca promover la colaboración, la transparencia y la reutilización de diseños electrónicos, garantizando que las modificaciones y los diseños derivados distribuidos mantengan las mismas libertades.

El texto completo de la licencia se incluye en el archivo LICENSE ubicado en el directorio raíz del repositorio.

Más información: https://www.oshwa.org/faq/

Texto oficial de la licencia: https://ohwr.org/cern_ohl_s_v2.txt

## Estructura del TP FINAL ##

* doc: Toda la información sobre el circuito, principalmente de autoría o procesamiento propio. Por ejemplo:
  * Notas de ingeniería propias.
  * Notas de aplicación propias.
  * Estudios previos, estado del arte, resumen de las investigaciones.
  * Notas con cálculos.
  * Dibujos adicionales.
  * Fotos de los prototipos.
  * Presupuestos, cotizaciones.
* info: Toda la iformación recolectada, principalmente de terceros, como por ejemplo:
  * Hojas de datos.
  * Notas de aplicación.
  * Info de productos comerciales.
  * Info en internet.
* pcb: Archivos de diseño esquemático y pcb.

Dependiendo la magnitud del proyecto, tendremos más o menos información en estos directorios. 
Revisar los README.md en cada directorio para conocer las pautas de cada uno para este TP.

NOTA: El alumno puede y debe borrar de este archivo todo lo que considere necesario, por ejemplo las aclaraciones del docente y esta misma nota.

## Obligatorios para el TP Final ##
* doc/propuesta/README.md (con textos y links, formato markdown, a imágenes que deben estar en el mismo repo. Las imágenes son las que se piden en las pautas de TP).
* info/*.pdf (Se piden solo las hojas de datos de los componentes relevantes como circuitos integrados, conectores particulares, módulos, etc. No es necesario poner hojas de pasivos, discretos comunes, conectores estándar.)
* pcb/* (Acá va el proyecto KiCad, modelos 3D, bibliotecas particulares y archivos generados como BOM, gerbers, etc.). EVITE subir al git archivos temporales de KiCad. Se recomienda usar un .gitignore adecuado.
* El alumnos es libre de agregar otras cosas, pero siempre tenga en cuenta que el repositorio es público. Evitar colocar información personal o documentación confidencial. 