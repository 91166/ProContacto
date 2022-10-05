![imagen](https://user-images.githubusercontent.com/16022218/194113196-e219c5c6-4f53-4e6c-a425-91f818a8542b.png)

## EJERCICIO 1

### Se realizan la descarga e instalación de:

VSCodeUserSetup-x64-1.71.2

Git-2.38.0-64-bit

**También se van a usar más adelante**

Postman-win64-Setup

zulu19.28.81-ca-jdk19.0.0-win_x64

dataloader_win_v56.0.4

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

### Revisar los conceptos de la sintaxis “json” antes de arrancar con los ejercicios

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


**¿Qué diferencias se observan entre las llamadas del punto 1 y 3?**

De primera mano, la instrucción del paso 2 esta mal, no estaba comillado el email y solo se obtenía error. Una vez comillado se ejecutó correctamente la inserción, y al hacer el paso 3 del GET a la dirección indicada, se observa que se han insertado los datos que se envió, al final del response.

## EJERCICIO 4
### Se solicita el usuario de TrailHead y se procede al cambio del idioma, tal cual se indica en las instrucciones. Posterior se realizan los módulos indicados.

## EJERCICIO 5

### Los siguientes objetos de Salesforce conceptualmente son:

•	[**Lead** ](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Lead.htm?q=lead "Lead ")- Representa un prospecto o un cliente potencial. Datos estándar son: Address, City, Company, Country, etc.

•	[**Account**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Account.htm?q=account "Account") - Representa una cuenta individual, que es una organización o persona involucrada con su negocio (como clientes, competidores y socios). Datos estándar son: Id, Description, Account Source, etc.

•	[**Contact**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Contact.htm?q=Contact "Contact") - Representa un contacto, que es una persona asociada a una cuenta. Datos estándar son: AccountId, Email, Department, Description, etc.

•	[**Opportunity**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Opportunity.htm?q=Opportunity "Opportunity") - Representa una oportunidad, que es una venta o un acuerdo pendiente. Datos estándar son: AccountId, Amount, Description, Id, etc.


•	[**ProductAttributeSetProduct**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_ProductAttributeSetProduct.htm?q=Product "ProductAttributeSetProduct") - Representa el producto asociado a un conjunto de atributos. Datos estándar son: Id, Name, ProductId, ProductAttributeSetId, etc.

•	[**PriceBook2**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Pricebook2.htm?q=pricebook2 "PriceBook2") - Representa un libro de precios que contiene la lista de productos que su organización vende. Datos estándar son: Id, Name, Description, CreatedById, etc.


•	[**Quote**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Quote.htm?q=quote "Quote") - El objeto Cotización representa una cotización, que es un registro que muestra los precios propuestos para productos y servicios. Datos estándar son: Id, Name, Pricebook2Id, Status, etc.

•	[**Asset**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Asset.htm?q=Asset "Asset") - Representa un artículo de valor comercial, como un producto vendido por su empresa o por un competidor, que un cliente ha comprado. Datos estándar son: Id, Address, City, Description, Country, etc.


•	[**Case**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Case.htm?q=Case "Case") - Representa un caso, que es un asunto o problema del cliente. Datos estándar son: Id, Origin, Status, etc.

•	[**KnowledgeArticleVersion**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_KnowledgeArticleVersion.htm?q=KnowledgeArticleVersion "KnowledgeArticleVersion") - Proporciona una vista global de los campos estándar de los artículos en todos los tipos de artículos en función de su versión. Datos estándar son: Id, Title, ArticleNumber, Language, etc

## EJERCICIO 4


## EJERCICIO 5

### Explicar conceptualmente los datos almacenados en cada uno de los siguientes objetos de Salesforce

•	[**Lead**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Lead.htm?q=lead "Lead") - Representa un prospecto o un cliente potencial. Datos estándar son: Address, City, Company, Country, etc.

•	[**Account**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Account.htm?q=account "Account") - Representa una cuenta individual, que es una organización o persona involucrada con su negocio (como clientes, competidores y socios). Datos estándar son: Id, Description, Account Source, etc.

•	[**Contact**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Contact.htm?q=Contact "Contact") - Representa un contacto, que es una persona asociada a una cuenta. Datos estándar son: AccountId, Email, Department, Description, etc.

•	[**Opportunity**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Opportunity.htm?q=Opportunity "Opportunity") - Representa una oportunidad, que es una venta o un acuerdo pendiente. Datos estándar son: AccountId, Amount, Description, Id, etc.

•	[**Product**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_ProductItemTransaction.htm?q=Product "Product") - Representa una acción realizada sobre un artículo de producto en el servicio de campo. Las transacciones de artículos de producto son registros autogenerados que le ayudan a realizar un seguimiento cuando un artículo de producto se repone, se consume o se ajusta. Datos estándar son: Id, Description, Quantity, ProductItemId, etc.

•	[**PriceBook2**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Pricebook2.htm?q=PriceBook "PriceBook2") - Representa un libro de precios que contiene la lista de productos que su organización vende. Datos estándar son: Id, Name, Description, CreatedById, etc.

•	[**Quote**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Quote.htm?q=Quote "Quote") - El objeto Cotización representa una cotización, que es un registro que muestra los precios propuestos para productos y servicios. Datos estándar son: Id, Name, Pricebook2Id, Status, etc.

•	[**Asset**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Asset.htm?q=Asset "Asset") - Representa un artículo de valor comercial, como un producto vendido por su empresa o por un competidor, que un cliente ha comprado. Datos estándar son: Id, Address, City, Description, Country, etc.

•	[**Case**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_Case.htm?q=Case "Case") - Representa un caso, que es un asunto o problema del cliente. Datos estándar son: Id, Origin, Status, etc.

•	[**KnowledgeArticleVersion**](https://developer.salesforce.com/docs/atlas.en-us.sfFieldRef.meta/sfFieldRef/salesforce_field_reference_KnowledgeArticleVersion.htm?q=Article "KnowledgeArticleVersion") - Proporciona una vista global de los campos estándar de los artículos en todos los tipos de artículos en función de su versión. Datos estándar son: Id, Title, ArticleNumber, Language, etc

### Enumerandolos y relacionando los campos a través de un UML:


## EJERCICIO 6

Respuestas breves sobre:

### Soluciones de Salesforce

•	[**¿Qué es Salesforce?**](https://www.salesforce.com/es/products/what-is-salesforce/ "¿Qué es Salesforce?") - Salesforce es una plataforma de gestión de las relaciones con los clientes (CRM) basada en la nube que proporciona a todos los departamentos de su organización, incluidos los de marketing, ventas, servicio de atención al cliente y ecommerce, una visión unificada de sus clientes en una plataforma integrada.

•	[**¿Qué es Sales Cloud?**](https://www.expandlatam.com/que-es-salesforce-crm/ "¿Qué es Sales Cloud?") - Salesforce Sales Cloud es una plataforma de ventas que da seguimiento al proceso de ventas, desde perfilar prospectos, hacer el contacto inicial hasta el final de la compra.

•	[**¿Qué es Service Cloud?**](https://www.expandlatam.com/que-es-salesforce-crm/ "¿Qué es Service Cloud?") - Es la plataforma de servicios de Salesforce, número uno en el mundo y se concentra en empresas enfocadas en productos tipo servicio. Service Cloud ayuda a las empresas ya consolidadas que quieren impulsar la satisfacción del cliente.

•	[**¿Qué es Health Cloud?**](https://wilcosource.com/es/health-cloud-quickstart/ "¿Qué es Health Cloud?") - Health Cloud permite una conversación personalizada entre el paciente y las entidades sanitarias asociadas. No solo es beneficioso para los equipos de atención médica, sino que también beneficia a los pacientes al establecer comunicaciones digitales con su equipo de atención.

•	[**¿Qué es Marketing Cloud?**](https://www.expandlatam.com/que-es-salesforce-crm/ "¿Qué es Marketing Cloud?") - Esta plataforma sirve para crear y automatizar campañas de marketing. Al enlazar esta gestión con la de ventas, es más fácil llegar a los clientes potenciales, crear campañas y hablar uno a uno.

### Funcionalidades de Salesforce

•	[**¿Qué es un Record Type?**](https://snakeoncode.com/record-types-salesforce/ "¿Qué es un Record Type?") - Los Record Types en Salesforce nos permiten definir diferentes Business Process, Pages Layouts y Picklist Values en un determinado objeto. Así mismo, los Record Types nos ayudan a mostrar distintos tipos de información según el perfil del usuario.

•	[**¿Qué es un Page Layout?**](https://help.salesforce.com/s/articleView?id=sf.customize_layout.htm&type=5 "¿Qué es un Page Layout?") - Los diseños de página controlan la disposición y organización de los botones, campos, s-control, Visualforce, enlaces personalizados y listas relacionadas en las páginas de registros de objetos. También ayudan a determinar qué campos son visibles, de sólo lectura y obligatorios. Utilice los diseños de página para personalizar el contenido de las páginas de registro para sus usuarios.

•	[**¿Qué es un Compact Layout?**](https://help.salesforce.com/s/articleView?id=sf.compact_layout_overview.htm&type=5 "¿Qué es un Compact Layout?") - Un diseño compacto muestra los campos clave de un registro de un vistazo en la aplicación móvil de Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

•	[**¿Qué es un Perfil?**](https://help.salesforce.com/s/articleView?id=sf.admin_userprofiles.htm&type=5 "¿Qué es un Perfil?") - Los perfiles definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación. Cuando cree usuarios, asigne un perfil a cada uno.

•	[**¿Qué es un Rol?**](https://help.salesforce.com/s/articleView?id=000322715&type=1 "¿Qué es un Rol?") - Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. Usuarios en cualquier función dada pueden ver, editar, e informar sobre todos los datos para funciones por debajo de ellos en la jerarquía de roles.

•	[**¿Qué es un Validation Rule?**](https://help.salesforce.com/s/articleView?id=sf.fields_defining_field_validation_rules.htm&type=5 "¿Qué es un Validation Rule?") - Las reglas de validación verifican que los datos que un usuario introduce en un registro cumplen las normas que usted especifica antes de que el usuario pueda guardar el registro. Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y devuelve un valor de "Verdadero" o "Falso".

•	[**¿Qué diferencia hay entre una relación Master Detail y Lookup?**](https://studysection.com/blog/difference-between-master-detail-and-lookup-relationships/ "¿Qué diferencia hay entre una relación Master Detail y Lookup?") - La relación de búsqueda de Salesforce no tiene relación con otros registros. No depende de ningún otro objeto, mientras que una relación maestro-detalle tiene una asociación con otros registros. Por otro lado, la relación de búsqueda es sólo una referencia. Incluso puede estar en blanco o ser NULL.

•	[**¿Qué es un Sandbox?**](https://help.salesforce.com/s/articleView?id=sf.data_sandbox_environments.htm&type=5 "¿Qué es un Sandbox?") - Un Sandbox es una copia de su organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación. Los sandbox están completamente aislados de su organización de producción de Salesforce.

•	[**¿Qué es un ChangeSet?**](https://help.salesforce.com/s/articleView?id=sf.changesets.htm&type=5 "¿Qué es un ChangeSet?") - Use conjuntos de cambios para enviar personalizaciones de una organización de Salesforce a otra. Por ejemplo, puede crear y probar un nuevo objeto en una organización de sandbox y luego enviarlo a su organización de producción mediante un conjunto de cambios.

•	[**¿Para qué sirve el import Wizard de Salesforce?**](https://trailhead.salesforce.com/es-MX/content/learn/modules/lex_implementation_data_management/lex_implementation_data_import "¿Para qué sirve el import Wizard de Salesforce?") - Esta herramienta permite importar datos en objetos estándar comunes, como contactos, prospectos, cuentas y objetos personalizados. Permite importar hasta 50.000 registros a la vez. Es una interfaz sencilla para especificar parámetros de configuración, fuentes de datos y asignaciones de campos (en el archivo de importación se asignan los mismos nombres de campos que en Salesforce). 

•	[**¿Para qué sirve la funcionalidad Web to Lead?**](https://www.nts-solutions.com/blog/leads-salesforce-web-to-lead.html "¿Para qué sirve la funcionalidad Web to Lead?") - Siguiendo un procedimiento intuitivo, Web-to-Lead permite diseñar un formulario incluyendo las preguntas más adecuadas para cada tipo de negocio con el objetivo de insertarlo en un blog o una web corporativa, automatizando así la captación de leads y la integración de los datos de los usuarios en Salesforce.

•	[**¿Para qué sirve la funcionalidad Web to Case?**](https://discover.egafutura.com/objeto-de-caso-de-salesforce-su-guia-definitiva/ "¿Para qué sirve la funcionalidad Web to Case?") - El objeto de caso de Salesforce forma la base de la capacidad de gestión de casos de Service Cloud, que ayuda a mejorar la experiencia general del usuario tanto para los clientes como para el personal.

•	[**¿Para qué sirve la funcionalidad Omnichannel?**](https://trailhead.salesforce.com/es-MX/content/learn/modules/omni-channel-lex/get-started-omni-lex "¿Para qué sirve la funcionalidad Omnichannel?") - Omnichannel es una función personalizable y flexible que se puede configurar de forma declarativa en Salesforce, es decir, sin necesidad de escribir código. Omnichannel ayuda al enrutamiento automático de diferentes tipos de elementos de trabajo (como casos y clientes potenciales) a los agentes.

•	[**¿Para qué sirve la funcionalidad Chatter?**](https://trailhead.salesforce.com/es-MX/content/learn/modules/chatter/chatter_intro "¿Para qué sirve la funcionalidad Chatter?") - Chatter es una aplicación de colaboración en tiempo real de Salesforce que permite a sus usuarios trabajar juntos, comunicarse y compartir información. Chatter conecta, compromete y motiva los usuarios para trabajar de forma eficiente en la organización independientemente de la función o ubicación.

### Conceptos generales

•	[**¿Qué significa SaaS?**](https://www.salesforce.com/mx/saas/ "¿Qué significa SaaS?") - **SaaS**, o Software as a Service, es una forma de poner. a disposición softwares y soluciones de tecnología por medio de la internet, como un servicio. Con este modelo, tu empresa no necesita instalar, mantener y actualizar hardwares y softwares.

•	[**¿Salesforce es Saas?**](https://www.techtarget.com/searchcustomerexperience/definition/Salesforcecom "¿Salesforce es Saas?") - **Salesforce, Inc.** es un proveedor de software como servicio (SaaS) de computación en la nube y empresas sociales con sede en San Francisco. Fundada en marzo de 1999 por el ex ejecutivo de Oracle Marc Benioff, Parker Harris, Dave Moellenhoff y Frank Domínguez, la empresa comenzó como un proveedor de plataformas de gestión de relaciones con los clientes (CRM). Con el tiempo, Salesforce se ha transformado en una potencia de SaaS, ofreciendo múltiples plataformas en la nube que sirven para fines especializados.

•	[**¿Qué significa que una solución sea Cloud?**](https://www.salesforce.com/mx/crm/?bc=OTH "¿Qué significa que una solución sea Cloud?") - El CRM en la Nube, o CRM Cloud, se basa en cloud computing. Podemos decir que es un CRM en línea y, por lo tanto, no se instala en una computadora ni requiere que tu empresa cuente con un equipo de TI dedicado a mantener el software. Esta es también la razón por la cual el CRM en línea puede llamarse software como servicio (SaaS), visto que toda la infraestructura es administrada de forma remota por el equipo de expertos de la solución. Con un CRM basado en la nube, tu equipo solo necesita entrar a la página de inicio de sesión desde cualquier lugar y en cualquier momento, por medio del navegador, en cualquier dispositivo o mediante la app.

•	[**¿Qué significa que una solución sea On-Premise?**](https://www.salesforce.com/mx/crm/?bc=OTH "¿Qué significa que una solución sea On-Premise?") - El CRM Local, también conocido como CRM On-Premise, es el tipo de CRM que se aloja en un servidor físico de la empresa y requiere manutención por parte de un equipo de TI propio. En este caso, es necesario instalar el software CRM en el servidor o en una computadora que se use como tal.

•	[**¿Qué es un pipeline de ventas?**](https://www.sydle.com/es/blog/que-es-un-pipeline-de-ventas-61292aa4b060f576043b5687/ "¿Qué es un pipeline de ventas?")  - El pipeline de ventas es, precisamente, el proceso de actividades y estrategias que necesita un vendedor para acelerar el ciclo de ventas, transformando clientes potenciales (aquellos que acaban de conocer tu marca o servicio) en clientes.

•	[**¿Qué es un funnel de ventas?**](https://www.salesforce.com/es/blog/2022/08/que_es_funnel_marketing_importante_definirlo.html?bc=OTH "¿Qué es un funnel de ventas?") - El «funnel marketing», «funnel de ventas» o «embudo de ventas», es un proceso que identifica las fases que llevan a un consumidor a comprar productos o servicios de una marca. Se adapta en función de la organización del sector de una empresa, combinando promoción y venta online y offline.

•	[**¿Qué significa Customer Experience?**](https://www.salesforce.com/mx/blog/2021/11/customer-experience-y-la-gestion-de-relacion-con-el-cliente-en-las-pymes.html?bc=OTH "¿Qué significa Customer Experience?") – Customer Experience (CX), o Experiencia del Cliente (en español) es como se llama al conjunto de percepciones e impresiones que un consumidor posee sobre una determinada empresa tras interactuar con ella, ya sea online o en vivo.

•	[**¿Qué significa omnicanalidad?**](https://www.salesforce.com/mx/blog/2022/08/omnichannel.html?bc=OTH "¿Qué significa omnicanalidad?") - El término omnicanal define actualmente a uno de los modelos de negocio más buscados en todo el mundo. Y no es para menos: a fin de cuentas, se refiere a la omnipresencia de los clientes (e, idealmente, de las marcas) en los más diversos canales de atención y conversión.

•	[**¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?**](https://www.tiendanube.com/blog/b2b/ "¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?")[**¿Qué es un KPI?**](https://www.sydle.com/es/blog/kpi-615de90225ce5d3ef29a5570/ "¿Qué es un KPI?") - El B2B (business to business) es el modelo de negocio en el que se realizan transacciones comerciales entre empresas. En cambio, en el modelo B2C (business to consumer) esas transacciones se efectúan entre negocios —de cualquier magnitud— y los consumidores.

Del inglés, el acrónimo KPI significa Key Performance Indicator, es decir, Indicador Clave de Desempeño. Estos son los indicadores o valores cuantitativos que se pueden medir, comparar y monitorear, con el fin de exponer el desempeño de los procesos y trabajar en las estrategias de un negocio.

•	[**¿Qué es una API y en qué se diferencia de una Rest API?**](https://hevodata.com/learn/api-vs-rest-api/ "¿Qué es una API y en qué se diferencia de una Rest API?") - El objetivo principal de las API es estandarizar el intercambio de datos entre servicios web. Dependiendo del tipo de API, la elección del protocolo cambia. Por otro lado, REST API es un estilo arquitectónico para construir servicios web que interactúan a través de un protocolo HTTP.

•	[**¿Qué es un Proceso Batch?** ](https://www.seas.es/blog/informatica/el-proceso-batch-y-la-mejora-de-la-productividad/ "¿Qué es un Proceso Batch? ")- El proceso batch o procesamiento por lotes es un proceso por el cual un ordenador realiza procesos, muchas veces de forma simultánea, de forma continuada y secuencial. Normalmente, este tipo de procesos se dividen en pequeñas partes que se realizan de forma continua consiguiendo una mejor depuración.

•	[**¿Qué es Kanban?**](https://www.salesforce.com/mx/blog/2021/12/que-son-metodologias-agiles-y-como-pueden-ayudar-a-tus-equipos-de-trabajo.html?bc=OTH "¿Qué es Kanban?") - Kanban es una palabra japonesa que en español significa “tarjeta visual”. Esta metodología sugiere una comunicación en tiempo real y controla el trabajo a través de una línea de producción. Es decir, se crean tres columnas: pendientes, en proceso y terminadas. De esa forma, es posible clasificar las tareas y visualizar fácilmente sus avances.

•	[**¿Qué es un ERP?**](https://dynamics.microsoft.com/es-es/erp/define-erp/ "¿Qué es un ERP?") – La planificación de recursos empresariales, también conocida como ERP, es un sistema que ayuda a automatizar y administrar los procesos empresariales de distintas áreas: finanzas, fabricación, venta al por menor, cadena de suministro, recursos humanos y operaciones.

•	[**¿Salesforce es un ERP?**](https://www.salesforce.com/mx/products/what-is-salesforce/?bc=OTH "¿Salesforce es un ERP?") - Salesforce es una solución de gestión de relaciones con clientes que une empresas y clientes. Es una plataforma CRM integrada que brinda a todos tus departamentos, incluidos marketing, ventas, comercio y servicios, una vista única y compartida de cada cliente.


## EJERCICIO 7
