# PHISHING
Estudio de diversos escenarios y ejemplos de phishing.

Antes de empezar , conocimientos previos:


## Cabeceras y Contenido de un Correo Electrónico

<p align="justify">El <strong>Formato de Mensaje de Internet (IMF) es el estándar que define la estructura y el formato exacto de los mensajes de correo electrónico.</strong> Esto permite que todos los sistemas de correo existentes puedan comunicarse entre sí sin errores ni modificaciones en la presentación. Es por esto que puedes mandar un mensaje de una dirección de correo de Gmail a las Cuentas de Correo de Microsoft sin errores gráficos por ejemplo.</p>


### PARTES PRINCIPALES

- **El encabezado del correo electrónico** 
<p align="justify">Imagina que un correo electrónico es una carta. La cabecera sería como el sobre de esa carta. En ella, se encuentra toda la información que detalla el recorrido del mensaje desde el remitente hasta el destinatario. (Como pueden ser los Servidores que transmitieron el Correo).</p>

- **El cuerpo del correo electrónico**
<p align="justify">En este caso sería el contenido de la carta. La parte visible y principal del mensaje. Aquí encontraremos el contenido que se quiere transmitir al destinatario.</p>

### ESTRUCTURA DE LA CABECERA

- **De**: Indica la dirección de correo electrónico desde la cual se envió el mensaje. (Remitente).
- **Asunto**: Es una breve descripción del contenido deL mensaje.
- **Fecha:** Indica la fecha y hora en que se envió el mensaje.
- **Para:** Indica la dirección de correo electrónico del destinatario del mensaje.

### CAMPOS ESPECIALES DE LA CABECERA

- **Return-Path:** En este campo encontramos el correo electrónico o dirección a la cual se enviará una respuesta en caso de responder al mensaje del correo recibido.(También podemos encontrarlo como return to).
- **Domain Key y firmas DKIM (Domain Key Identified Mail )**: Ayuda a la identificación y autenticación de los correos.
- **ID del mensaje** : Cada mensaje de correo tiene un ID único e irrepetible formado por números y letras.
- **MIME-Versión:** Es un tipo de codificación que se hace necesaria para poder enviar todo tipo de archivos a través del SMTP (Simple Mail Transfer Protocol).

### ESTRUCTURA DEL CUERPO
<p align="justify">El <strong>cuerpo del correo electrónico</strong> puede estar formado simplemente por texto plano o poseer una estructura más compleja como puede ser el “formato” o lenguaje de marcado HTML. Este también puede incluir la opción de añadir archivos adjuntos.</p>
