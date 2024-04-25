# Cabeceras HHTTP

## Content-Type:
 Esta cabecera indica al cliente y al servidor el tipo de medio del cuerpo del mensaje. Por ejemplo, "application/json" se utiliza para datos en formato JSON, "text/html" para HTML, "image/jpeg" para imágenes JPEG, etc. Es esencial para que el receptor del mensaje pueda interpretar correctamente el contenido.

## Content-Length:
Indica la longitud en bytes del cuerpo del mensaje. Permite al receptor del mensaje saber cuántos bytes debe esperar recibir, lo que es útil para la correcta interpretación del contenido y para la gestión de recursos.

## Cache-Control: 
 Esta cabecera especifica las directivas de almacenamiento en caché que deben seguirse tanto en el servidor como en el cliente. Puede indicar si el contenido puede ser almacenado en caché, si debe ser revalidado después de un cierto tiempo, si puede ser almacenado solo en cachés privadas, entre otras directivas.

## Date:
Indica la fecha y hora en que se originó el mensaje. Esta información es útil para la sincronización de tiempo y para el control de la frescura de los recursos en caché.

## User-Agent: 
 Proporciona información sobre el software que envía la solicitud. Es útil para que los servidores adapten las respuestas según el cliente que realiza la solicitud. Por ejemplo, un servidor puede enviar contenido optimizado para un navegador web específico.

## Accept:
Esta cabecera indica los tipos de contenido que el cliente está dispuesto a aceptar. Permite que el cliente comunique al servidor sus preferencias de contenido, lo que puede ser útil para la negociación de contenido.

## Authorization:
Proporciona credenciales para autenticar al usuario. Se utiliza para autenticar solicitudes HTTP y permite al servidor verificar si el usuario tiene permiso para acceder al recurso solicitado.

## Cookie:
 Contiene datos específicos del usuario, generalmente utilizados para mantener el estado de la sesión. Las cookies se utilizan para recordar información sobre el usuario entre diferentes solicitudes HTTP, como la autenticación y preferencias del usuario

## Set-Cookie: 
Esta cabecera es utilizada por el servidor para enviar una cookie al cliente. Permite al servidor establecer una cookie en el navegador del cliente, que luego será devuelta en las solicitudes futuras relacionadas con el mismo dominio.

## Location: 
Indica la URL a la que se debe redirigir el cliente. Se utiliza comúnmente en respuestas a solicitudes de redirección para indicar al cliente la nueva ubicación del recurso solicitado.