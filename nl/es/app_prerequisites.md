---

copyright:
 years: 2017

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# Requisitos previos
{: #prerequisites}
Última actualización: 18 de enero de 2018
{: .last-updated}


## Creación de una instancia de servicio de App Launch
{: #prerequisites_1}

1. En [IBM Cloud Catalog](https://console.ng.bluemix.net/catalog/), pulse **Móvil** > **App Launch**.
2. Indique un nombre de servicio.
3. Pulse **Crear**.
4. Elija conectar con otras apps existentes o dejarlo sin enlazar.


Puede elegir crear un servicio enlazado o no enlazado. Los servicios enlazados se conectan a otras apps de IBM Cloud, mientras que los servicios no enlazados son independientes y no están conectados a otras apps. De forma predeterminada, las apps del servicio App Launch no están enlazadas.

## Inicialización de la app
{: #prerequisites_app}

1. Pulse **Valores**.
1. Descargue una de los SDK, según su tipo de plataforma:
	- [iOS](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-applaunch)
	- [Android](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-android-applaunch)

2. Copie las claves de configuración para inicializar la App. Utilice el Secreto de App, el GUID de App y el Secreto de cliente para configurar su app y crear fidelizaciones.

![SDK y claves](images/engagement_settings.gif)

## Creación de una característica
{: #prerequisites_2}

El servicio de {{site.data.keyword.engage_short}} le permite crear y probar reacciones a características. 

Para crear una característica, realice los pasos siguientes:

![Detalles de característica](images/feature_creation_animated.gif)

1. En el panel de navegación, pulse **Características** > **Crear nueva característica** 

2. Actualice el formulario Crear nueva característica y métricas con un nombre de característica y una descripción apropiados. También puede definir las propiedades de la característica y añadir métricas para medir la repercusión de su fidelización. Pulse **Edición masiva** para añadir varias propiedades editando el JSON.

3. Pulse **Crear**. Aparecerá la nueva característica en el panel Características. 

4. Habilite la característica una vez desarrollada.

5. Para habilitar una característica para utilizarla como fidelización, pulse la Característica que ha creado.

6. En la ventana Detalles de característica, seleccione Actualizar el estado de la característica a **Listo**.

7. Pulse **Actualizar** estado.

8. Actualice la app para que se incluyan los códigos de característica y los atributos recién creados en la app de iOS o Android. 

9. La característica está lista para utilizar.

La ventana Detalles de característica tiene una opción para exportar la característica como un archivo JSON que puede ser utilizado en la aplicación cliente para cargar los valores predeterminados.


## Creación de un público
{: #prerequisites_2}

Para crear un público, realice los pasos siguientes:

![Crear público](images/create_audience_animated.gif)

1. Cree un atributo de público. 

	Pulse en **Público** > **Crear atributo**.

	Indique los siguientes valores:

	- **Nombre**: indique un nombre apropiado para el atributo.
	- **Descripción**: una breve descripción del atributo.
	- **Tipo**: seleccione el tipo de atributo.
	- **Valores permitidos**: indique los valores de atributo que desea utilizar.

    En función de lo que necesite, puede crear diversos atributos de público, como muestra la lista de la imagen siguiente.
	
	
2. Cree un público.

	a. Pulse **Crear público**.

	b. Indique un nombre y una descripción apropiados en la ventana Nuevo público.

	c. Seleccione un atributo y pulse **Añadir**.

    d. Seleccione las opciones necesarias de la lista de atributos.

	e. Pulse **Guardar**.
	
	Ahora podrá crear una fidelización.

<!-- You can now create an engagement using the [Feature Control](app_feature_toggle.html) option. -->
