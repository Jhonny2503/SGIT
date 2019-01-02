# Configurador de los componentes  / instrumentos

El módulo configurador de encuestas es una herramienta para que los usuarios diseñen y configuren preguntas y respuestas relacionadas con la vivienda, la tenencia, etc. Cada proyecto generado en el sistema puede tener una encuesta de acuerdo con las necesidades del proyecto, y los usuarios pueden agregar o modificar preguntas y respuestas según sea necesario. necesario.

Las siguientes imágenes explican cómo modificar una encuesta de proyecto, paso a paso

![Se seleccionara el icono de la imagen para acceder a configuraci&#xF3;n.](../.gitbook/assets/image%20%28216%29.png)

![Boton Add item para a&#xF1;adir una nueva pregunta en la encuesta.](../.gitbook/assets/image%20%2851%29.png)

![Estados de la pregunta en la Encuesta.](../.gitbook/assets/image%20%28124%29.png)

{% tabs %}
{% tab title="1er Estado" %}
Es la pregunta en la encuesta y ya a sido guardada con el **Save Survey Structure** la cual **no se puede eliminar ni cambiar su ID**, se puede identificar por su color de fondo verde.
{% endtab %}

{% tab title="2do Estado" %}
Es una nueva pregunta en la encuesta y ya a sido guardada con el **Save Question** la cual se puede editar y eliminar completamente , se puede identificar por su color de fondo blanco y su eliminar es un tacho de basura
{% endtab %}

{% tab title="3er Estado" %}
Es una nueva pregunta en la encuesta y **aun no ha sido guardado** la cual se puede editar y eliminar completamente , se puede identificar por su color de fondo blanco y su eliminar es una cruz
{% endtab %}
{% endtabs %}

![Campos disponibles para el ingreso de una pregunta en la Encuesta   ](../.gitbook/assets/image%20%28192%29.png)

{% tabs %}
{% tab title="N° item" %}
Este campo es **Autogenerado** pero se puede **cambiar** si el usuario cambiar el orden de las Encuestas.
{% endtab %}

{% tab title="Input Type" %}
En este campo se puede seleccionar el campo de las encuesta y dependiendo de este aparecerá  o no el campo de **Options**.
{% endtab %}

{% tab title="Question" %}
Es la Pregunta de la encuesta en ella puede ir cualquier carácter.
{% endtab %}

{% tab title="Column Width" %}
Es el Tamaño de **Question** este puede variar del **1 al 12**.
{% endtab %}

{% tab title="New Line After" %}
Se puede marcar para que la siguiente pregunta se coloque en la siguiente linea.
{% endtab %}

{% tab title="Visible" %}
Permite cambiar la visibilidad de la pregunta.
{% endtab %}

{% tab title="Options" %}
Este campo depende del campo **Input Type**, en este campo se puede agregar las  respuesta para la preguntas.
{% endtab %}

{% tab title="+" %}
Permite eliminar una pregunta de la **Encuesta**.
{% endtab %}
{% endtabs %}

![Opci&#xF3;n de Avanzado](../.gitbook/assets/image%20%28134%29.png)

![](../.gitbook/assets/image%20%28210%29.png)

{% tabs %}
{% tab title="Function Validate" %}
**Function Validate.-** En este campo se puede seleccionar 3 tipos de validaciones para el tipo de información que recibirá la respuesta en la encuesta, **si no se selecciona ninguna** se podrá responder con **letras y números**.

     **A\)Number Validation.-** Solo se podrá responder en la encuesta con **números**.

     **B\)String Validation.-** Solo se podrá responder en la encuesta con **letras**.

     **C\)Decimal Validation.-** Se podrá ingresar "**,**" , "**.**" y **números**.
{% endtab %}

{% tab title="Upper Case" %}
Convertirá todo el contenido en Mayúsculas.
{% endtab %}

{% tab title="Required" %}
Si se selecciona la pregunta tendrá que ser respondida **obligatoriamente** para poder terminar la encuesta.
{% endtab %}

{% tab title="Column Name" %}
En este campo solo **esta permitido letra, número y subguión**; no pueden ir símbolos o espacios entre otros.
{% endtab %}

{% tab title="Column Type" %}
Este campo es autogenerado a partir de lo ya seleccionado en **Input type**, este campo **se puede cambiar si se selecciona otro input type**.
{% endtab %}

{% tab title="Column Size" %}
El valor dentro de este campo definirá la cantidad de caracteres máximos puede recibir la respuesta en la encuesta.
{% endtab %}

{% tab title="Default Value" %}
Es el valor con el que aparecerá la respuesta al abrir una encuesta.
{% endtab %}
{% endtabs %}

![](../.gitbook/assets/image%20%2826%29.png)

### **Equivalent Question**

Para habilitar correctamente este campo se necesitara de un segundo campo con el **input type** en **search**, **el primer campo se autogenerara una ves que el segundo campo se llene**.

Una ves seleccionado se **habilitara los siguientes Campos** 

{% tabs %}
{% tab title="Table" %}
Se elegirá la tabla en donde se encuentre la información que el usuario busque.
{% endtab %}

{% tab title="Relation Field" %}
Se selecciona el campo en el cual se referenciará la información, **generalmente es un ID**.
{% endtab %}

{% tab title="Equivalent Field" %}
Se selecciona el campo del cual se obtendrá la información.
{% endtab %}

{% tab title="Question Dependent" %}
Es la pregunta de la que se obtendrá el campo referencial.
{% endtab %}
{% endtabs %}

![Una vez editada / agregada la pregunta en la encuesta se selecciona &quot;Save Questions&quot;](../.gitbook/assets/image%20%28172%29.png)

![Preview dar&#xE1; un vistazo a los cambios que el usuario realice.](../.gitbook/assets/image%20%2858%29.png)

![Preview con la nueva pregunta ingresada](../.gitbook/assets/image%20%28181%29.png)

{% hint style="danger" %}
**Advertencia:** El siguiente paso **no se puede Revertir**.
{% endhint %}

![](../.gitbook/assets/image%20%2865%29.png)

{% hint style="warning" %}
Una ves guardado con el **Save Survey Structure** se almacenara en la base de datos  y no se podrá eliminar.
{% endhint %}

