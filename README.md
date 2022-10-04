# ProContacto
## EJERCICIO 1
Se realizan la descarga e instalación de:

VSCodeUserSetup-x64-1.71.2

Git-2.38.0-64-bit

Postman-win64-Setup (que también se va a usar más adelante)

## EJERCICIO 2
### Cuestionario de preguntas de comprensión del protocolo HTTP

[•	**¿Qué es un servidor HTTP?** ](https://developer.mozilla.org/es/docs/Learn/Common_questions/What_is_a_web_server "•	¿Qué es un servidor HTTP? ")- Un servidor HTTP es una pieza de software capaz de comprender URLs (direcciones web) y HTTP (el protocolo que tu navegador usa para obtener las páginas web).

•	[**¿Qué son los verbos HTTP? Mencionar los más conocidos**](https://developer.mozilla.org/es/docs/Web/HTTP/Methods "¿Qué son los verbos HTTP? Mencionar los más conocidos") - HTTP define un conjunto de métodos de petición para indicar la acción que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados HTTP verbs. Cada uno de ellos implementan una semántica diferente, pero algunas características similares son compartidas por un grupo de ellos: ej. un request method puede ser safe, idempotent (en-US), o cacheable.

•	[**¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?**](https://developer.mozilla.org/es/docs/Web/HTTP/Messages "¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?") - Los mensajes HTTP, son los medios por los cuales se intercambian datos entre servidores y clientes. Hay dos tipos de mensajes: peticiones, enviadas por el cliente al servidor, para pedir el inicio de una acción; y respuestas, que son la respuesta del servidor. Los headers o cabeceras HTTP de una petición siguen la misma estructura que la de una cabecera HTTP. Una cadena de caracteres, que no diferencia mayúsculas ni minúsculas, seguida por dos puntos (':') y un valor cuya estructura depende de la cabecera. La cabecera completa, incluido el valor, ha de ser formada en una única línea, y pude ser bastante larga.

•	[**¿Qué es un queryString? (En el contexto de una url)**](https://codigofacilito.com/articulos/query-string "¿Qué es un queryString? (En el contexto de una url)") - Dentro del protocolo HTTP podemos encontrar diferentes métodos (verbos) con los cuales podemos realizar diferentes tipos de peticiones. El método más utilizado sin duda es el método GET, método cual nos permite obtener un recurso por parte del servidor, ya sea una página web, un archivo txt, un gif etc. Algo interesante de este método es que podemos enviar información al servidor de tal forma que seamos más precisos en el recurso que deseamos obtener. La información la enviaremos atraves de la URL, en una sección denominada Query String.

•	[¿**Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?**](https://es.ryte.com/wiki/C%C3%B3digos_de_Estado_Http "¿**Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?**") - Un código de estado es una parte de la respuesta devuelta por el servidor cuando un cliente (por ejemplo, un navegador) llama a una URL. Con la ayuda de un código de estado, el servidor indica al cliente si la solicitud se ha procesado correctamente o si se ha producido un error.

•	[**¿Cómo se envía la data en un Get y cómo en un POST?**](https://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=527:get-y-post-html-method-formas-de-envio-de-datos-en-formulario-diferencias-y-ventajas-ejemplos-cu00721b&catid=69&Itemid=192 "**¿Cómo se envía la data en un Get y cómo en un POST?**") - La diferencia entre los métodos get y post radica en la forma de enviar los datos a la página cuando se pulsa el botón “Enviar”. Mientras que el método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).

•	[**¿Qué verbo http utiliza el navegador cuando accedemos a una página?**](https://developer.mozilla.org/es/docs/Web/HTTP/Overview "¿Qué verbo http utiliza el navegador cuando accedemos a una página?") - Un método HTTP, normalmente pueden ser un verbo, como: GET , POST o un nombre como: OPTIONS (en-US) o HEAD (en-US), que defina la operación que el cliente quiera realizar. Para poder mostrar una página Web, el navegador envía una petición de documento HTML al servidor. Entonces procesa este documento, y envía más peticiones para solicitar scripts, hojas de estilo (CSS), y otros datos que necesite (normalmente vídeos y/o imágenes). El navegador, une todos estos documentos y datos, y compone el resultado final: la página Web. Los scripts, los ejecuta también el navegador, y también pueden generar más peticiones de datos en el tiempo, y el navegador, gestionará y actualizará la página Web en consecuencia.

•	[**Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.** ](https://programmerclick.com/article/60681955413/ "**Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.** ")- **JSON(JavaScript Object Notation)** es un formato de intercambio de datos ligero, que es completamente independiente del idioma. Está basado en el lenguaje de programación JavaScript y es fácil de entender y generar. Por ejemplo:

![imagen](https://user-images.githubusercontent.com/16022218/193893963-4ef7d30c-0770-4350-8b96-2457119f4237.png)


**XML(Lenguaje de marcado extensible)** está diseñado para transmitir datos, no mostrar datos. Esta es la recomendación del W3C. El lenguaje de marcado extensible (XML) es un lenguaje de marcado que define un conjunto de reglas para codificar documentos en formatos legibles por humanos y legibles por máquina. Los objetivos de diseño de XML se centran en la simplicidad, versatilidad y usabilidad en Internet. Es un formato de datos de texto que proporciona un potente soporte para diferentes lenguajes humanos a través de Unicode. Aunque el diseño de XML se centra en documentos, el lenguaje se utiliza ampliamente para representar estructuras de datos arbitrarias, como las que se utilizan en los servicios web. Por ejemplo:

![imagen](https://user-images.githubusercontent.com/16022218/193894342-c67f7800-cd43-408b-bc77-f89ab4d7ce0f.png)

**JSON** es la notación de objetos de JavaScript, **XML** es el lenguaje de marcado extensible.

•	[**Explicar brevemente el estándar SOAP**](https://www.ibm.com/docs/es/rsas/7.5.0?topic=standards-soap "Explicar brevemente el estándar SOAP") - SOAP es un estándar basado en XML para la transmisión de mensajes en HTTP y otros protocolos de Internet. Es un protocolo ligero para el intercambio de información en un entorno descentralizado y distribuido.

•	[**Explicar brevemente el estándar RESTful**](https://www.redhat.com/es/topics/api/what-is-a-rest-api "Explicar brevemente el estándar RESTful") - Es considerada una técnica de arquitectura de software, es decir, un conjunto de principios y patrones de comunicación que ayudan a crear una forma de pensar y construir las APIs. Este tipo de arquitectura se define por un conjunto de restricciones entre los elementos, componentes, conectores y datos usados. Una API de REST, o API de RESTful, es una interfaz de programación de aplicaciones (API o API web) que se ajusta a los límites de la arquitectura REST y permite la interacción con los servicios web de RESTful.

•	[**¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?**](https://developer.mozilla.org/es/docs/Web/HTTP/Headers/Content-Type "¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?") – Como ya se indico antes los headers o cabeceras HTTP de una petición siguen la misma estructura que la de una cabecera HTTP. Content-Type es la propiedad de cabecera (header) usada para indicar el media type (en-US) del recurso. Content-Type dice al cliente que tipo de contenido será retornado.

## Ejercicio 3

•	Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
![imagen](https://user-images.githubusercontent.com/16022218/193928585-7b48f4a8-6e91-44bb-b9bb-ea9c7f3b1703.png)

•	Realizar un request POST a la URL anterior, y con body:
{
"name":"emilio",
"email":"emilio.jarrin@procontacto.com.mx"
}
![imagen](https://user-images.githubusercontent.com/16022218/193929359-372a26ad-2186-460f-9fab-7fa989058b43.png)


•	Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
![imagen](https://user-images.githubusercontent.com/16022218/193930340-9d60f596-e6bf-4b7e-abd1-85ac6451620f.png)


¿Qué diferencias se observan entre las llamadas el punto 1 y 3?

De primera mano, la instrucción del paso 2 esta mal, no estaba comillado el email y solo se obtenía error. Una vez comillado se ejecutó correctamente la inserción, y al hacer el paso 3 del GET a la dirección indicada, se observa que se han insertado los datos que se envió, al final del response.

## EJERCICIO 4
Se solicita el usuario de TrailHead y se procede al cambio del idioma, tal cual se indica en las instrucciones. Posterior se realizan los módulos indicados.

## EJERCICIO 5

Los siguientes objetos de Salesforce conceptualmente son:

•	[**Lead** ](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Lead.htm?q=lead "Lead ")- Representa un prospecto o un cliente potencial. Datos estándar son: Address, City, Company, Country, etc.

•	[**Account**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Account.htm?q=account "Account") - Representa una cuenta individual, que es una organización o persona involucrada con su negocio (como clientes, competidores y socios). Datos estándar son: Id, Description, Account Source, etc.

•	[**Contact**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Contact.htm?q=Contact "Contact") - Representa un contacto, que es una persona asociada a una cuenta. Datos estándar son: AccountId, Email, Department, Description, etc.

•	[**Opportunity**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Opportunity.htm?q=Opportunity "Opportunity") - Representa una oportunidad, que es una venta o un acuerdo pendiente. Datos estándar son: AccountId, Amount, Description, Id, etc.


•	[**ProductAttributeSetProduct**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_ProductAttributeSetProduct.htm?q=Product "ProductAttributeSetProduct") - Representa una acción realizada sobre un artículo de producto en el servicio de campo. Las transacciones de artículos de producto son registros autogenerados que le ayudan a realizar un seguimiento cuando un artículo de producto se repone, se consume o se ajusta. Datos estándar son: Id, Description, Quantity, ProductItemId, etc.

•	[**PriceBook2**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Pricebook2.htm?q=pricebook2 "PriceBook2") - Representa un libro de precios que contiene la lista de productos que su organización vende. Datos estándar son: Id, Name, Description, CreatedById, etc.


•	[**Quote**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Quote.htm?q=quote "Quote") - El objeto Cotización representa una cotización, que es un registro que muestra los precios propuestos para productos y servicios. Datos estándar son: Id, Name, Pricebook2Id, Status, etc.

•	[**Asset**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Asset.htm?q=Asset "Asset") - Representa un artículo de valor comercial, como un producto vendido por su empresa o por un competidor, que un cliente ha comprado. Datos estándar son: Id, Address, City, Description, Country, etc.


•	[**Case**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Case.htm?q=Case "Case") - Representa un caso, que es un asunto o problema del cliente. Datos estándar son: Id, Origin, Status, etc.

•	[**KnowledgeArticleVersion**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_KnowledgeArticleVersion.htm?q=KnowledgeArticleVersion "KnowledgeArticleVersion") - Proporciona una vista global de los campos estándar de los artículos en todos los tipos de artículos en función de su versión. Datos estándar son: Id, Title, ArticleNumber, Language, etc
