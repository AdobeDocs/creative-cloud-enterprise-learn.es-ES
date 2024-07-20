---
title: Información sobre la caducidad de los números de serie de Creative Cloud para empresas y Acrobat
description: Descripción de la experiencia de caducidad de números de serie para Creative Cloud para empresas y Acrobat
role: Admin
level: Beginner, Intermediate
feature: Deploy
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: c57212d39b2e613964bc15d2967a1958dc0c8c8e
workflow-type: tm+mt
source-wordcount: '840'
ht-degree: 1%

---

# Información sobre la caducidad de los números de serie de Creative Cloud para empresas y Acrobat

Históricamente, el Adobe proporcionaba números de serie con nuestras aplicaciones (es decir, Creative Suite, Creative Cloud para empresas, Acrobat XI, Acrobat DC) a los clientes mediante contratos de licencias de duración determinada para empresas (ETLA). Estos números de serie tienen una fecha de caducidad. Una vez transcurrida la fecha de caducidad, el producto dejará de funcionar, por lo que es importante planificar la migración antes de que caduquen los números de serie. Esta página describe los pasos necesarios para garantizar que los usuarios finales tengan acceso continuo a sus aplicaciones y servicios de Adobe.

## Comprobación de los números de serie para su fecha de caducidad

### Buscar los números de serie

Las licencias con número de serie asociadas a tu contrato de ETLA están disponibles en el [Sitio web de licencias de Adobe](https://licensing.adobe.com/) (LWS). Siga estas instrucciones para mostrar y descargar:

1. Inicie sesión en [Sitio web de licencias de Adobe](https://licensing.adobe.com/) (LWS) con su Adobe ID y contraseña.
1. Elija **Licencias > Recuperar números de serie**.
1. Indique su **ID de usuario final** o **ID de implementación**.
1. (Opcional) Seleccione un **nombre del producto**, una **versión del producto** o una **plataforma** para filtrar los resultados.
1. Haga clic en Buscar.
1. Se muestran los números de serie y el nombre del producto.
1. (Opcional) Seleccione EXPORTAR A CSV para descargar la lista de números de serie.

![Buscar los números de serie](assets/retrieveserialnumbers.png)

### Comprobar la fecha de caducidad

[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) es una utilidad de línea de comandos para administradores de TI que permite comprobar si los productos de Adobe de un equipo están usando números de serie que han caducado o van a caducar. La herramienta mostrará información como el identificador de licencia del producto (LEID), el número de serie cifrado y la fecha de caducidad. Esta [página](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) contiene instrucciones sobre cómo descargar y usar la herramienta en equipos Mac o Windows.

## Conocer la experiencia del usuario final antes y después de que caduque el número de serie

Tanto Acrobat como Creative Cloud para aplicaciones empresariales empezarán a mostrar mensajes (en las aplicaciones) 60 días antes del vencimiento. Una vez que caduca el número de serie, los productos dejan de funcionar y se solicita al usuario que realice una acción.

### Creative Cloud para la experiencia empresarial

La siguiente información describe la experiencia del usuario final. A continuación se muestra un breve vídeo seguido de una revisión de la experiencia del usuario final.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Antes del vencimiento**

A partir de 60 días antes de que caduque el número de serie, todas las aplicaciones de Creative Cloud para empresas muestran un cuadro de diálogo en el producto al usuario final. Este mensaje aparecerá semanalmente, hasta 30 días antes del vencimiento, y luego aparecerá diariamente hasta la fecha de vencimiento que indica *Su licencia está caducando. Este producto de Adobe está usando una licencia que caducará el 29 de noviembre de 2020. Póngase en contacto con su administrador para asegurarse de que se mantiene el acceso a*.

![CCE antes del mensaje de caducidad](assets/cceexpiring.png)

**Después del vencimiento**

Una vez que caduque el número de serie, los usuarios ya no tendrán acceso al Creative Cloud de las aplicaciones empresariales. La primera vez que se inicie después de caducar, se mostrará al usuario un cuadro de diálogo en el que se indica *El número de serie que has introducido ha caducado. No se puede adquirir la licencia de este producto. Póngase en contacto con Asistencia al cliente*.

![Mensaje de CCE después de la caducidad](assets/cceafterexpire.png)

En todos los intentos posteriores de iniciar las aplicaciones, se solicitará al usuario final que **Inicie sesión ahora** y, a continuación, se le dará la opción de crear su propio Adobe ID y entrar en el modo de prueba. Sin embargo, cualquier nuevo Adobe ID creado por el usuario final no se asociará a las licencias de su organización y causará confusión adicional a sus usuarios. Para evitar la interrupción de la actividad o confusión innecesaria, migre sus usuarios a licencias de usuario designadas antes de que caduquen sus números de serie.

![Diálogo de inicio de sesión en CCE 1](assets/ccesignin1.png)

![Diálogo de inicio de sesión en CCE 2](assets/ccesignin2.png)

### Experiencia Acrobat

La siguiente información describe la experiencia del usuario final. A continuación se muestra un breve vídeo seguido de una revisión de la experiencia del usuario final.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Antes del vencimiento**

A partir de los 60 días antes de que caduque el número de serie, Acrobat muestra un mensaje emergente del producto al usuario final. Esto aparecerá una vez a la semana hasta 7 días antes del vencimiento. A partir de ese momento, la licencia de Adobe Acrobat empezará a aparecer todos los días a partir del *11/30/2020. Póngase en contacto con el administrador para seguir usando Acrobat sin interrupciones.*

![Mensaje de caducidad de Acrobat](assets/acrobatexpiring.png)

**Después del vencimiento**

Una vez que caduque el número de serie, los usuarios ya no tendrán acceso a Acrobat. La primera vez que se inicie después de caducar, se mostrará al usuario un cuadro de diálogo en el que se indica *El número de serie que has introducido ha caducado. No se puede adquirir la licencia de este producto. Póngase en contacto con Asistencia al cliente.*

![Mensaje de Acrobat tras la caducidad](assets/acrobatafterexpire.png)

En todos los intentos posteriores de iniciar Acrobat, se solicitará al usuario final que **Inicie sesión ahora** y, a continuación, se le dará la opción de crear su propio Adobe ID y entrar en el modo de prueba. Sin embargo, cualquier nuevo Adobe ID creado por el usuario final no se asociará a las licencias de su organización y causará confusión adicional a sus usuarios.

![Acrobat Sign en el cuadro de diálogo 1](assets/acrobatsignin1.png)

![Acrobat Sign en el cuadro de diálogo 2](assets/acrobatsignin2.png)

## Contacte con nosotros si necesita ayuda

Si tienes alguna pregunta sobre el uso de la herramienta [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) o necesitas ayuda para migrar de la implementación del número de serie al usuario designado, tienes varias opciones:
* Enviar un correo electrónico al equipo de incorporación empresarial de Adobe: **entonb@adobe.com**
* Abra un ticket de asistencia en [Admin Console](https://adminconsole.adobe.com/support)
* Póngase en contacto con el equipo de cuentas de Adobe
