# Módulo de Gestión Cartográfica

### 6.- Módulo de Gestión Cartográfica

![](../.gitbook/assets/image%20%28221%29.png)

**Módulo principal**

![](../.gitbook/assets/image%20%28173%29.png)

Descargar estructura de la cartografía \(example Parcela\). Si deseamos subir información, primero tenemos que descargar la estructura de la capa que se desea actualizar. Esta estructura contiene los campos ya establecidos en el estándar y que son necesarios para la subida de información.

 Una vez descargado agregue sus datos a dicha estructura revise los campos y complete si fuera necesario usando el ArcMap del ArcGis o un Software Open Gis como el QGIS para luego proceder a cargar dicha información. La lógica de la estructura propuesta es la de facilitar la carga rápida de la cartografía y que esta se vincule fácilmente con la base alfanumérica.

![](../.gitbook/assets/image%20%2893%29.png)

Nota:

 • El shape contiene un registro \(dato geométrico\) por defecto con datos de ejemplo para que el usuario tenga noción de que datos van en cada campo. 

• El Operador gis debe incorporar los nuevos datos de su proyecto al shape usado un software gis mencionado anteriormente. 

• Asegúrese que la información geométrica este geo referenciada en Geográficas WGS84 

• Finalmente comprima en formato zip. Revisar: Enlace al Diccionario de datos de las capas

Cargar datos a la Base de datos Cartográfica. 

1. Seleccionamos la cartografía a la que deseamos agregar los nuevos datos, para este caso seleccionamos “Parcel”

2. Buscamos y agregamos el shape trabajado con la estructura descargada del Sistema y los datos cargados.

3. El sistema tiene que indicar que la configuración está al 100% para poder cargar la información, caso contrario deberá verificar si hay algún campo que no cumple con el Estándar.

![](../.gitbook/assets/image%20%28210%29.png)

1. Click para cargar los datos de dicha cartografía.
2. Seleccionamos los datos correspondientes y presionamos en grabar.



![](../.gitbook/assets/image%20%286%29.png)

De esta manera la información ya estará cargada satisfactoriamente.

