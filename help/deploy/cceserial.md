---
title: Explicación de la caducidad del número de serie de Creative Cloud para empresas y Acrobat
description: Explicación de la experiencia de caducidad del número de serie para Creative Cloud para empresas y Acrobat
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# Explicación de la caducidad del número de serie de Creative Cloud para empresas y Acrobat

Históricamente, Adobe ha emitido números de serie con nuestras aplicaciones (es decir, Creative Suite, Creative Cloud para empresas, Acrobat XI, Acrobat DC) a los clientes con contratos de licencias de duración determinada para empresas (ETLA). Estos números de serie tienen una fecha de caducidad. Una vez que haya pasado la fecha de caducidad, el producto ya no funcionará, por lo que es importante planificar la migración antes de que caduquen los números de serie. Esta página describe los pasos necesarios para garantizar que los usuarios finales tengan acceso continuo a sus aplicaciones y servicios de Adobe.

## Comprobación de los números de serie para su fecha de caducidad

### Buscar los números de serie

Las licencias con número de serie asociadas a su acuerdo de ETLA están disponibles a través del [Sitio web de licencias de Adobe](https://licensing.adobe.com/) (LWS). Siga estas instrucciones para mostrar y descargar:

1. Inicie sesión en [Sitio web de licencias de Adobe](https://licensing.adobe.com/) (LWS) con su Adobe ID y contraseña.
1. Elija **Licencias > Recuperar números de serie**.
1. Introduzca su **ID de usuario final** o **ID de implementación**.
1. (Opcional) Seleccione un **Nombre del producto**, **Versión del producto** o **Plataforma** para filtrar los resultados.
1. Haga clic en Buscar.
1. Se muestran los números de serie y el nombre del producto.
1. (Opcional) Seleccione &quot;EXPORTAR A CSV&quot; para descargar la lista de números de serie.

![Buscar números de serie](assets/retrieveserialnumbers.png)

### Comprobar la fecha de caducidad

El [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) es una utilidad de línea de comandos para que los administradores de TI comprueben si los productos de Adobe de un equipo utilizan números de serie que han caducado o que están expirando. La herramienta mostrará información como el identificador de licencia de producto (LEID), el número de serie cifrado y la fecha de caducidad. Esta [página](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) contiene instrucciones sobre cómo descargar y utilizar la herramienta en equipos Mac o Windows.

## Explicación de la experiencia del usuario final antes y después de que caduque el número de serie

Tanto Acrobat como Creative Cloud para aplicaciones empresariales empezarán a mostrar mensajes (en las aplicaciones) a partir de los 60 días anteriores a la caducidad. Una vez caducado el número de serie, los productos dejan de funcionar y piden al usuario que tome medidas.

### Experiencia de Creative Cloud para empresas

La siguiente información describe la experiencia del usuario final. A continuación se muestra un breve vídeo, seguido de una revisión de la experiencia del usuario final.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Antes de la caducidad**

A partir de 60 días antes de que caduque el número de serie, todos los Creative Cloud de aplicaciones empresariales mostrarán al usuario final un cuadro de diálogo en el producto. Este mensaje aparecerá semanalmente, hasta 30 días antes de la caducidad, y aparecerá diariamente hasta la fecha de caducidad que indica *Su licencia caduca. Este producto de Adobe utiliza una licencia que caduca el 29 de noviembre de 2020. Póngase en contacto con su administrador para asegurarse de que continúe el acceso*.

![CCE antes del mensaje de caducidad](assets/cceexpiring.png)

**Después de la caducidad**

Una vez caducado el número de serie, los usuarios ya no tendrán acceso al Creative Cloud para aplicaciones empresariales. La primera vez que se inicie después de caducar, se mostrará al usuario un cuadro de diálogo que indicará *El número de serie introducido ha caducado. No se puede comprar la licencia de este producto. Póngase en contacto con Asistencia al cliente*.

![CCE después del mensaje de caducidad](assets/cceafterexpire.png)

Para todos los intentos posteriores de iniciar las aplicaciones, se solicitará al usuario final que **Inicie sesión ahora** seguido de la opción de crear su propio Adobe ID y acceder al modo de prueba. Sin embargo, cualquier nuevo Adobe ID creado por el usuario final no se asociará con las licencias de su organización y causará confusión adicional a los usuarios. Para evitar problemas comerciales o confusión innecesaria, migre a los usuarios a licencias de usuario designadas antes de que caduquen los números de serie.

![Cuadro de diálogo de inicio de sesión de CCE 1](assets/ccesignin1.png)

![Cuadro de diálogo Inicio de sesión de CCE 2](assets/ccesignin2.png)

### Experiencia de Acrobat

La siguiente información describe la experiencia del usuario final. A continuación se muestra un breve vídeo, seguido de una revisión de la experiencia del usuario final.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Antes de la caducidad**

A partir de 60 días antes de que caduque el número de serie, Acrobat muestra al usuario final un mensaje emergente en el producto. Esto aparecerá una vez a la semana hasta 7 días antes de la caducidad. A continuación, comenzará a aparecer a diario indicando *Su licencia de Adobe Acrobat caduca el 11/30/2020. Póngase en contacto con el administrador para continuar usando Acrobat sin interrupciones.*

![Mensaje de Acrobat caducando](assets/acrobatexpiring.png)

**Después de la caducidad**

Una vez caducado el número de serie, los usuarios ya no tendrán acceso a Acrobat. La primera vez que se inicie después de caducar, se mostrará al usuario un cuadro de diálogo que indicará *El número de serie introducido ha caducado. No se puede comprar la licencia de este producto. Póngase en contacto con Asistencia al cliente.*

![Acrobat después del mensaje de caducidad](assets/acrobatafterexpire.png)

En todos los intentos posteriores de iniciar Acrobat, se solicitará al usuario final que **Inicie sesión ahora** seguido de la opción de crear su propio Adobe ID y entrar en modo de prueba. Sin embargo, cualquier nuevo Adobe ID creado por el usuario final no se asociará con las licencias de su organización y causará confusión adicional a los usuarios.

![Cuadro de diálogo de inicio de sesión de Acrobat Sign 1](assets/acrobatsignin1.png)

![Cuadro de diálogo de inicio de sesión de Acrobat Sign 2](assets/acrobatsignin2.png)

## Póngase en contacto con nosotros si necesita ayuda

Si tiene alguna pregunta sobre el uso de la herramienta [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) o necesita ayuda para migrar de la implementación del número de serie a un usuario designado, tiene algunas opciones:
* Envíe un correo electrónico al equipo de incorporación de Adobe Enterprise: **entonb@adobe.com**
* Abra un ticket de soporte en [Admin Console](https://adminconsole.adobe.com/support)
* Póngase en contacto con el administrador de cuentas de Adobe o con el administrador de éxito del cliente
