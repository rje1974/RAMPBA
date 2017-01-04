# RAMPBA
## Red de Apoyo Metereológica Provincia Buenos Aires

El proyecto RAMPBA Tiene como objetivo generar herramientas, que mediante el uso de la información generada por estaciones meteorologistas económicas, puedan realizar aportes a las comunidades donde se encuentran. También nos proponemos que el uso y la personalización de estas estaciones y su software sean lo mas sencillo posible.

Para nos proponemos los siguientes proyectos:

1. **Proyecto documentación. (EN DESARROLLO)**
Manual de instalación y armado de estaciones, para las estaciones económicas (http://www.foshk.com/) que se venden en mercadolibre (costo 1799 pesos). http://articulo.mercadolibre.com.ar/MLA-609076060-estacion-meteorologica-inalambrica-usb-pc-wh-1080-1081-JM. Manual de instalación y armado de servidor ubuntu + weewx. Con las correspondientes configuraciones para windguru, weatherunderground y openweathermap. Para colaborar ingrese en el link a continuación.
> https://github.com/rje1974/Documentacion_WS1080-81

2. **Proyecto Alerta Meteorológica. (TERMINADO)**
Generar un script para alertas para determinada temperatura por correo electrónico.
> https://github.com/rje1974/alerta_temperatura

3. **Proyecto Alerta Agroquímicas. (EN PROCESO)**
Generar un script que permita alertar a los usuarios cuando no están dadas las condiciones para las aplicaciones de agroquímicas, tomando como referencia los valores dados por "el manual de buenas practicas"-

4. **Proyecto Alerta Pico de Precipitaciones Repentino. (EN PROCESO)**
Generar un script que permita una alerta por correo electrónico cuando los milímetros acumulados de lluvia superen un valor en un espacio de tiempo predeterminado.

5. **Proyecto Alerta Pico de precipitaciones acumulada nocturno. (EN PROCESO)**
Generar un script que permita una alerta por correo electrónico cuando los milímetros acumulados de lluvia superen un valor en un espacio de tiempo predeterminado durante la noche.

6. **Skin y Interfaz. (EN DESARROLLO)**
Generar una interfaz amigable que permita guardar las distintas configuraciones de alerta. Skin Argenta. Traducción al español de una de las skins sumando nuestras imágenes de radar climatológico.
https://github.com/rje1974/Skin-Weewx-Argentina

7. **Canal  BOT Whastapp. (SIN COMENZAR)**
 Configurar script que permita el agregado del servicio de whasapp como canal al sistema de alertas.

8. **Plugin Emergencias Provincia de Buenos Aires. (POSPUESTO)**
Generar un Plugin para que el sistema aporte sus datos a los servidores del sistema de alertas de la provincia de buenos aires. El mismo requiere credenciales de acceso a los servidores de las entidades, que no se encontraron disponibles durante el evento.


Observaciones. 4/12/16 09:01 La central que estamos usando como "conejito" esta funcionando en Trenque Lauquen y se puede ver la información que esta generando mediante el acceso a weatherunderground ( https://www.wunderground.com/personal-weather-station/dashboard?ID=IBUENOSA511) y windguru (https://www.windguru.cz/station/768). Aqui se puede ver una imagen del servidor ( https://i.imgsafe.org/2de65508cf.png ) Las centrales que estamos usando no están homologadas por el servicio meteorológico y eso limita el uso de los datos por los actores públicos; pero eso no es limitante para que el proyecto sea utilizado por colectivos ciudadanos o modelos matemáticos.
