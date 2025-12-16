# Analisis_de_datos_Proyecto_Final
Proyecto final, análisis de datos con Power Bi con historia de datos, en el marco de la especialización Análisis de Datos del Informatorio.

###
* *Origen*: datos obtenidos desde el sitio Datos Abiertos de Buenos Aires. https://buenosaires.gob.ar/innovacionytransformaciondigital/datos-abiertos-de-buenos-aires

*   *Descripción*: Relevamiento de usos de suelo de la Ciudad Autónoma de Buenos Aires desde el año 2022 hasta el año 2024.
Se trata de un relevamiento observacional en el que se infieren los usos y las actividades de cada parcela de la
Ciudad a partir de los rasgos que el relevador identifica in situ durante el momento de la observación. Para ello, se
observan características tipológicas del edificio, su estado de conservación y la actividad que se está desarrollando
en el instante del relevamiento.
Los usos de cada edificio se registran con la calle y la altura observada en el relevamiento.

*   *Diccionario de atributos*:

    * SMP:Sección-manzana-parcela, es decir, la nomenclatura catastral.
    * BARRIO: Barrio donde se ubica el uso relevado.
    * TIPO1: Uso general de la parcela.
    * TIPO2: Uso específico de la parcela.
    * ESTADO: Describe la condición de funcionamiento del uso del suelo al momento del relevamiento. Puede clasificarse en:
      * Activo: cuando el uso relevado se encuentra en funcionamient efectivo, como un comercio abierto, una vivienda habitada o una industria en operación.
      * Inactivo: cuando el uso existe físicamente pero no está en funcionamiento al momento del relevamiento,como un local cerrado o una vivienda abandonada.
      * En el caso de usos como Lote, Espacios verdes, Obra en construcción, Vía pública y Barrio popular no seconsigna el estado, ya que no aplica la clasificación entre activo e inactivo.
    * PISOS: Cantidad de pisos del uso.
    * GP_Q: Cantidad de garages privados con los que cuenta el uso.
    * OBS: Comentario adicional que complementa la información registrada, permitiendo incluir aclaraciones o detalles relevantes no contemplados en otros campos del formulario. Este campo no es obligatorio.
    * CALLE: Nombre de la calle sobre la cual se encuentra el uso del suelo.
    * PUERTA: Número asignado a la entrada principal del inmueble. En caso de que el uso no cuente con numeración oficial, se registra el valor 0.
    * UNIFICADO: Indica si el uso relevado abarca una o más parcelas que, en la práctica, funcionan como un único terreno. En estos casos se asigna la palabra SI en este campo.
    * SMP_IDEM: Señala a qué parcela se encuentra unificado el terreno.
    * AÑO: Corresponde al año en que se realizó el relevamiento en ese barrio.
