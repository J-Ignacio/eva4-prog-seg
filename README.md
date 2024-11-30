# eva4-prog-seg
1. ¿Qué son los Encabezados HTTP? (2 puntos)

Respuesta: Los encabezados HTTP son datos que se envían entre un navegador y un servidor web al solicitar una página, facilitando la comunicación y coordinación entre ambos.
2. ¿A qué se asemejan los encabezados HTTP en la analogía de la "casa"? (2 puntos)

Respuesta:
3. ¿Qué tipo de información se envía a los servidores web cuando se realiza un proceso de registro o inicio de sesión? (3 puntos)

Respuesta: Cuando un usuario se registra o inicia sesión, se envían datos de autenticación al servidor web. Este servidor es responsable de almacenar y proporcionar el contenido de un sitio web al navegador del usuario, utilizando el protocolo HTTP, que define las normas para la comunicación entre el cliente y el servidor. Los registros de acceso son archivos que guardan información sobre las solicitudes de archivos realizadas desde un sistema, incluyendo detalles sobre la autenticación del usuario, quién hizo la solicitud, cuándo se realizó, y otros datos relacionados.
4. ¿Qué son los "Response Headers"? (3 puntos)

Respuesta: Los encabezados de respuesta HTTP, o Response Headers, son piezas de información que se intercambian entre un navegador y un sitio web durante una solicitud o respuesta HTTP. Estos encabezados proporcionan detalles adicionales sobre la respuesta, como: la ubicación de la respuesta, el servidor que la emite, el origen del contenido, la versión del protocolo y el código de estado.
5. ¿Cuál es la importancia de los "Response Headers"? (3 puntos)

Respuesta: Los encabezados de respuesta son cruciales porque ofrecen información extra sobre cómo un servidor responde a una solicitud realizada por un cliente.
6. ¿Qué es la "pestaña Network" en las herramientas para desarrolladores? (2 puntos)

Respuesta: La "pestaña Network" en las herramientas de desarrollo de la mayoría de los navegadores permite registrar la actividad de comunicación entre el navegador y el servidor.
7. ¿Cuál es el principal objetivo de los Encabezados HTTP en términos de seguridad? (3 puntos)

Respuesta: Su operación es igual a la de otros procesos. El usuario envía una solicitud al servidor mediante su navegador, y ambos intercambian un conjunto de encabezados. Sin embargo, en este caso, los encabezados incluyen información específica sobre aspectos de seguridad. Aunque su principal objetivo es proteger la comunicación, también abordan cuestiones relacionadas con la privacidad.
8. ¿Qué tipos de Encabezados HTTP existen para proteger la información? (3 puntos)

Respuesta: Los encabezados de seguridad HTTP son un tipo de encabezado HTTP que se utilizan para proteger la información de un sitio web y de sus usuarios. Algunos ejemplos de cabeceras de seguridad HTTP son:
-Strict-Transport-Security (HSTS): Obliga a los navegadores a usar conexiones HTTPS seguras.
-Content-Security-Policy (CSP): Controla los recursos que se pueden cargar en una página web.
-X-Content-Type-Options: Previene ataques que explotan la interpretación del contenido.
-X-Frame-Options: Evita que un sitio web sea embebido en un iframe, protegiéndolo de ataques de clickjacking.
9. ¿Qué es la encriptación y cómo se relaciona con los Encabezados HTTP en la seguridad web? (3 puntos)

Respuesta: La encriptación es una medida de seguridad que resguarda los datos del usuario contra accesos no autorizados o ciberataques. Los encabezados HTTP actúan como una capa de protección, permitiendo que los servidores limiten las solicitudes provenientes de otros dominios.
10. ¿Cuál es el nombre de la página web oficial de Mozilla con documentación sobre Encabezados HTTP? (1 punto)

Respuesta: MDN Web Docs
11. ¿Cuáles son algunos ejemplos de Encabezados HTTP utilizados para la autenticación? (3 puntos)

Respuesta: Algunos ejemplos de encabezados HTTP utilizados para la autenticación son:
-Authorization: Contiene los datos de autenticación, como los utilizados para iniciar sesión. Un ejemplo de este encabezado es "Basic WjbU7D25zTAlV2tZ7==". 
-WWW-Authenticate: Es un encabezado de autenticación. 
-Proxy-Authenticate: Es un encabezado de autenticación. 
12. ¿Qué son las cookies y qué función cumplen? (3 puntos)

Respuesta: Las cookies son pequeños archivos de texto que los sitios web envían al navegador cuando los visitas. Estas permiten que los sitios web retengan información sobre tu visita, facilitando el regreso a los mismos y haciéndolos más personalizados y útiles.
13. ¿Cuales son los 2 tipos de Encabezados HTTP se utilizan para la protección de contenido web? (3 puntos)

Respuesta: Los encabezados de seguridad HTTP son cruciales para proteger el contenido web y los datos de los usuarios. Dos de las cabeceras de seguridad HTTP más importantes son:
-Strict-Transport-Security (HSTS): Obliga a los navegadores a usar conexiones HTTPS seguras.
-Content-Security-Policy (CSP): Controla los recursos que pueden ser cargados en la página web. 
14. ¿Qué función cumple el Content Security Policy (CSP)? (3 puntos)

Respuesta: La Política de Seguridad de Contenido (CSP) es una función de seguridad que ayuda a prevenir y mitigar ataques en sitios web, como: Ataques de secuencias de comandos entre sitios (XSS), Inyección de datos, Robo de datos, Desfiguración del sitio, Distribución de malware.
15. ¿Qué es el "XSS" y cómo se relaciona con los Encabezados HTTP? (4 puntos)

Respuesta: XSS (Cross-Site Scripting) es una vulnerabilidad en aplicaciones web que permite a los atacantes insertar scripts maliciosos en páginas vistas por otros usuarios. Estos scripts pueden robar datos sensibles, como cookies o credenciales, o ejecutar acciones no autorizadas en nombre del usuario afectado.

Los encabezados HTTP ayudan a prevenir XSS al establecer medidas de seguridad. Algunos de los encabezados más importantes son:

-Content-Security-Policy (CSP): Este encabezado permite a los administradores de sitios web especificar qué fuentes de contenido son seguras (como scripts, imágenes o estilos), evitando que se ejecuten scripts maliciosos, incluso si están presentes en la página.

-X-XSS-Protection: Este encabezado activa la protección contra ataques XSS en ciertos navegadores, aunque muchos navegadores actuales prefieren usar CSP. Cuando se habilita, busca bloquear intentos de XSS básicos.

-Strict-Transport-Security (HSTS): Aunque no se enfoca directamente en XSS, HSTS obliga a que las conexiones se realicen mediante HTTPS, lo que ayuda a prevenir ataques que podrían facilitar la inserción de scripts maliciosos a través de conexiones no seguras.
16. (*) ¿Qué encabezado ayuda al rendimiento de una página web? (3 puntos)

Respuesta:
17. ¿Cómo se identifican los Encabezados HTTP antes del 2012? (2 puntos)

Respuesta:
18. (*) ¿Qué es SEO en el contexto de la web? (2 puntos)

Respuesta: SEO es la abreviatura de Search Engine Optimization (optimización para motores de búsqueda) y se refiere a un conjunto de técnicas y estrategias que se implementan en un sitio web para mejorar su posicionamiento en los buscadores. 
19. ¿Cuál es el atajo del teclado (shortcut) para acceder al inspector de elementos en el navegador? (1 punto)

Respuesta: El atajo de teclado para acceder al inspector de elementos en el navegador es Ctrl + Shift + I en Windows o Command + Option + I en Mac. 
También puedes acceder al inspector de elementos haciendo clic derecho en cualquier parte de la página web y seleccionando "Inspeccionar".
20. ¿Qué significa "HTTP" en las siglas de Encabezados HTTP? (1 punto)

Respuesta: HTTP son las siglas de Hypertext Transfer Protocol, que en español significa "Protocolo de transferencia de hipertexto". Es un protocolo de comunicación que permite solicitar datos y recursos, como documentos HTML, entre un navegador y un servidor web. 
21. (*) ¿Cuál es la diferencia entre los encabezados HTTP y los encabezados HTTPS? (4 puntos)

Respuesta: La principal diferencia entre los encabezados HTTP y los encabezados HTTPS radica en que HTTPS es la versión segura y encriptada de HTTP, lo que garantiza una transmisión de datos protegida.

-HTTP: Los mensajes HTTP son enviados en texto claro, lo que significa que cualquier persona puede interceptarlos y ver su contenido.

-HTTPS: Utiliza certificados SSL/TLS para cifrar los datos transmitidos entre el navegador y el servidor, protegiendo la información de accesos no autorizados.

Los encabezados HTTP son datos que se intercambian entre un navegador y un sitio web al visitar una página. Estos encabezados pueden incluir detalles como el tipo de formato de los datos solicitados o el origen del contenido.
22. (*) ¿Cuáles son los tipos de métodos HTTP qué mas se utilizan? (mencione al menos 5) (4 puntos)

Respuesta:
-POST 
-GET 
-PUT 
-PATCH  
-DELETE
23. (*) ¿Qué permiten hacer las herramientas de desarrollo del navegador con respecto a los encabezados HTTP? (4 puntos)

Respuesta: Las herramientas de desarrollo de los navegadores permiten acceder a los encabezados HTTP, incluso si se generan en relación con el servidor y no con el navegador. 
24. (*) ¿Qué es un "Proxy" y cómo se relaciona con los Encabezados HTTP? (4 puntos)

Respuesta:Un servidor proxy proporciona una puerta de enlace entre los usuarios e Internet. Es un servidor denominado “intermediario”, porque está entre los usuarios finales y las páginas web que visitan en línea. Cuando una computadora se conecta a Internet, utiliza una dirección IP. Esto es similar a la dirección de su casa: le indica a los datos entrantes adónde ir y marca los datos salientes con una dirección de devolución para que otros dispositivos se autentiquen. Un servidor proxy es esencialmente una computadora en Internet que tiene una dirección IP propia. 
25. (*) ¿Cómo se pueden usar los Encabezados HTTP para optimizar el SEO de un sitio web? (4 puntos)

Respuesta: Los encabezados HTML son fundamentales para el SEO técnico de un sitio web, ya que facilitan la organización del contenido y mejoran su comprensión por parte de los motores de búsqueda. Para optimizarlos, se recomienda seguir estos principios:

-Jerarquía: Mantener un orden lógico en los encabezados sin omitir niveles.
-Relevancia: Asegurarse de que cada encabezado sea pertinente al texto y aporte contexto y valor al contenido.
-Palabras clave: Incluir palabras clave relevantes en cada sección de la página.
-Estructura: Usar las etiquetas de encabezado para dividir las diferentes secciones de la página.
-Actualización: Revisar y actualizar las etiquetas H cuando se actualice el contenido.
-Featured snippets: Optimizar los encabezados para mejorar las posibilidades de aparecer en los fragmentos destacados de los motores de búsqueda.
-Legibilidad: Mejorar la accesibilidad y facilidad de lectura del contenido.
Los encabezados facilitan a los motores de búsqueda el rastreo de una página y la determinación de cómo clasificar su contenido, además de mejorar la experiencia de lectura de los usuarios.




