# Revisión editorial del TFG

**Documento revisado:** report(3).pdf, «Sistema de préstamos descentralizado basado en la red Blockchain de Ethereum», fechado el 28 de octubre de 2026. 105 páginas físicas.

**Dictamen:** conviene realizar una última ronda de corrección antes de considerarlo terminado. Hay numerosas erratas, faltas de concordancia y puntuación, varios restos de edición y algunas incoherencias internas. Muchas correcciones son rápidas, pero las frases señaladas y las tablas merecen atención individual.

## Alcance y localización

Se ha leído el texto extraído de todas las páginas, incluidos resumen, abstract, índices, cuerpo, anexos, bibliografía y glosario. Se han contrastado visualmente páginas con anomalías de tablas, listados y glosario. No se ha realizado una auditoría técnica del código ni una comprobación externa de las afirmaciones y fuentes. El contenido incrustado exclusivamente en imágenes no tiene la misma cobertura que el texto extraíble.

Las páginas que siguen son **las impresas en la memoria**. Desde la introducción, la página del visor PDF se obtiene sumando 11: página 1 de la memoria = página 12 del PDF; página 36 = página 47 del PDF. Las páginas preliminares se identifican expresamente por su posición en el PDF.

Los fragmentos citados se presentan sin los guiones que el PDF utiliza para dividir palabras al final de línea. Esos guiones tipográficos normales no se consideran erratas. Las propuestas de redacción son alternativas editoriales, no citas del original. El PDF original no se ha modificado.

## 1. Prioridades antes de cerrar la memoria

1. Corregir las erratas de las tablas de la sección 2 y las frases de la sección 3 de este informe.
2. Corregir los restos de edición: «figura r3.2», «en el 2», «ECONÓMICAS S», duplicaciones de palabras y los triples acentos graves del listado 3.9.
3. Reparar la tabla 3.16: descripción repetida, frase incompleta y celda vacía. Revisar también los nombres de las funciones frente al código del anexo.
4. Ajustar el listado del anexo A en las páginas 68–69: parte del código queda fuera del margen y aparece fragmentada verticalmente.
5. Limpiar la puntuación y las entradas del glosario; después, regenerar los índices para que recojan las correcciones.
6. Resolver las incoherencias internas señaladas al final: algunos párrafos parecen describir una versión anterior del sistema.

## 2. Erratas y correcciones directas por página

Una fila puede agrupar varias ocurrencias o varios errores de la misma página. Las correcciones de identificadores de código se distinguen de las del lenguaje natural: no debe hacerse una sustitución global sobre el código sin revisar sus usos.

### Preliminares y capítulo 1

| Página | Texto actual | Corrección o actuación |
|---|---|---|
| PDF 1–2 | «Guillermo Sánchez Gutierrez-Cabello» | Comprobar la grafía oficial del apellido; si es Gutiérrez, falta la tilde. No modificar un nombre propio sin verificarlo. |
| PDF 2 | «km. 7» | «km 7». El símbolo no lleva punto. |
| PDF 5, abstract | «This bachelor thesis» | «This bachelor’s thesis». |
| PDF 5, abstract | «contracts(Smart Contracts)» | «smart contracts» en la frase completa; eliminar la repetición entre paréntesis y el problema de espaciado. |
| PDF 5, abstract | «in a Blockchain network»; «registered in the Blockchain» | Más natural: «on a blockchain network»; «recorded on the blockchain». |
| 1 | «intentando de algún modo, evitar» | «intentando, de algún modo, evitar» o «intentando evitar». |
| 1 | «el acceso […] sea descentralizada» | «el acceso […] sea descentralizado». |
| 2 | «protipo» | «prototipo». |
| 2 | «En esa sección» | «En esta sección». |
| 2 | «proceso de prestamo» | «proceso de préstamo». |
| 2 | «como pueden ser, la seguridad» | «como pueden ser la seguridad». |
| 2 | «desde un solo punto, y facilitando» | «desde un solo punto, facilitando». |
| 2 | «datos sensibles, y el procesamiento» | «datos sensibles y el procesamiento». |
| 3 | «Optimizar eficiencia de ejecución de código» | «Optimizar la eficiencia de ejecución del código». |
| 3 | «mecanismos […] automatizado» | «mecanismos […] automatizados». |
| 3 | «natuaraleza» | «naturaleza». |
| 3 | «pudiendose» | «pudiéndose». |
| 3 | «aportar a mundo» | «aportar a un mundo». |
| 3 | «habla en su blog que» | «explica en su blog que». |
| 4 | «El código fuente con las pruebas unitarias […] se pueden encontrar» | «El código fuente con las pruebas unitarias […] se puede encontrar». |
| 4 | «siguiente repositorio [3]» | Añadir punto final. |

### Capítulo 2

| Página | Texto actual | Corrección o actuación |
|---|---|---|
| 6 | «aparación»; «analisis»; «protolocos»; «privadaos» | «aparición»; «análisis»; «protocolos»; «privados». |
| 6 | «cada uno de estos protocolos han sido creados» | «cada uno de estos protocolos ha sido creado». |
| 6 | «La integridad de estos protocolos se apoyan» | «La integridad de estos protocolos se apoya». |
| 6 | «las cuales se hablan en este proyecto» | «de las cuales se habla en este proyecto». |
| 6 | «ethereum» | «Ethereum». |
| 6 | «los Smart Contract […] siendo público y accesible» | «los contratos inteligentes […], que son públicos y accesibles». |
| 6 | «no solo […] si no que también» | «no solo […], sino que también». |
| 6–7 | «préstamo, Dependiendo» | «préstamo. Dependiendo». |
| 7 | «en la la red» | «en la red». Aparece en Aave, Compound y Uniswap. |
| 7–8 | «mas información» | «más información». |
| 7 | «garantias» | «garantías». |
| 8, apartado Uniswap | «documentación oficial del protocolo AAVE» | «documentación oficial del protocolo Uniswap». |
| 8 | «dichas tecnología» | «dichas tecnologías». |
| 8 | Párrafos que terminan en «UI» y «[10]» | Añadir punto final. |
| 8 | «Universitat Politécnica de Catalunya» | Revisar la forma del nombre institucional; si se conserva en catalán, «Universitat Politècnica de Catalunya». |
| 9 | «información la red» | «información a la red». |
| 9 y 88, referencia [11] | «CIENCIAS ECONÓMICAS S» | Eliminar la «S» final suelta del título, previa comprobación del título de la fuente. |
| 9 | «código de referencia al bloque anterior hash» | «código de referencia al bloque anterior, denominado hash». |
| 9 | «Cada bloque y cada transacción […] está asegurada» | «Cada bloque y cada transacción […] están protegidos». |
| 9 | «Cada nodo contiene […] y son responsables» | «Cada nodo contiene […] y es responsable». |
| 9 | Finales «alteración» y «por su labor» | Añadir punto final. |
| 10 | «obener»; «dificil»; «facil» | «obtener»; «difícil»; «fácil». |
| 10 | «fomra»; «obiene»; «mediente»; «demas» | «forma»; «obtiene»; «mediante»; «demás». |
| 10 | «pseudo-aleatoria» | «pseudoaleatoria». |
| 12 | «el resto de la red sigue siendo seguro» | «el resto de la red sigue siendo seguro» puede referirse al resto; para evitar ambigüedad, «la seguridad del resto de la red se mantiene». Reformular el párrafo completo. |
| 12 | «mientras ente el 51 y 70 %» | Errata: «entre». La frase y los porcentajes necesitan revisión de contenido; no basta con corregir esa palabra. |
| 12 | «¿cómo se puede crear un sistema automatizado?.» | «¿Cómo se puede crear un sistema automatizado?». No añadir punto después del cierre de interrogación. |
| 12 | «artibulos» | «artículos». |
| 12 | «En 2014. publicó» | «En 2014 publicó». |
| 13, figura 2.2 | «a tiempo real» | «en tiempo real», si se habla de la web. Una captura representa una fecha concreta; ajustar el pie a esa circunstancia. |
| 13 | «Coin Market Cap [16]» | Añadir punto final; unificar la grafía del nombre en todo el texto. |
| 14 | «ethereum»; «descentrelizada»; «estandares» | «Ethereum»; «descentralizada»; «estándares». |
| 14 | «criptomenda»; «pudiendose» | «criptomoneda»; «pudiéndose». |
| 14 | «ERC-72 [19]» | «ERC-721 [19]», de acuerdo con la propia referencia [19]. |
| 14 y 93 | «Documento Naciona de Identidad» | «Documento Nacional de Identidad». Corregir también la definición de la sigla. |
| 14–15 | Títulos corridos «Plataforma para dApps», «Criptoeconomía y Modelo de Tokenización», «Identidad», «Oráculos» | Separarlos de su explicación con dos puntos o punto. Por ejemplo: «Oráculos: son servicios…». |
| 15 | «ethereum»; «posiblidad»; «identifición»; «a traves» | «Ethereum»; «posibilidad»; «identificación»; «a través». |
| 16 | «por su puesto» | «por supuesto». |
| 16 | «funcioniento» | «funcionamiento». |
| 16 | «información necesaria la EVM» | «información necesaria para la EVM». |
| 16 | «Sepholia-ETH» | «Sepolia» o «red de pruebas Sepolia». |
| 16 | «pero si utilizar criptomonedas reales» | «pero sin utilizar criptomonedas reales». Falta una letra que invierte el sentido. |
| 16 | «dsitintas» | «distintas». |
| 16 | Finales «Wallet», «Blockchain» y «EVM» | Añadir los puntos que faltan. |
| 17 | «las herramienta»; «articifial»; «exhausitivo» | «las herramientas»; «artificial»; «exhaustivo». |
| 17 | «a demás» | «además». |
| 17 | «sobretodo» | «sobre todo», con el sentido de «especialmente». |
| 17 | «bockchain» | «blockchain». |
| 17–18 | «Javascript»; «solidity» | «JavaScript»; «Solidity». |
| 18 | «hacen más sencillo las tareas» | «hacen más sencillas las tareas». |
| 18 | «etc..» | «etc.». |
| 18 | «orientado en el desarrollo» | «orientado al desarrollo». |
| 18 | Final «entorno “pre-Inteligencia Artificial”» | Añadir punto final y revisar la formulación por su imprecisión. |

### Capítulo 3: páginas 19–38

| Página | Texto actual | Corrección o actuación |
|---|---|---|
| 19 | «possedora»; «prestamos»; «usario» | «poseedora»; «préstamos»; «usuario». |
| 19 | «está autorizada a ofrecer […], configurar […] y gestiona» | «está autorizada a ofrecer […], configurar […] y gestionar». |
| 19 | «se basa en en el diseño» | «se basa en el diseño». |
| 19 | «estados en los que puede llegar» | «estados en los que puede encontrarse». |
| 19 | «como actúa»; «como se queda» | «cómo actúa»; «cómo queda». |
| 20, figura 3.1 | «Diagrama algoritmo de estados» | «Diagrama de estados» o «Diagrama del algoritmo de estados». |
| 20 | «[32], el objetivo» | «[32]. El objetivo». El párrafo necesita además comprobar su cronología. |
| 21 | «para lea emisión» | «para la emisión». |
| 21 | «Las acciones que pueden llegar limitar el proyecto es» | Reformular: «Una de las exigencias que pueden limitar el proyecto es…». |
| 21 | «Euros» | «euros». |
| 21 | «350.000E» | Revisar la composición del importe y utilizar «350 000 €» si se refiere a euros; verificar el glifo en el archivo fuente. |
| 22 | «pero sí ejecutar un desarrollo» | «pero sí exige un desarrollo». |
| 22 | «diagrmas» | «diagramas». |
| 22 | «estructura y flujo del sistema» | «estructura y el flujo del sistema», tras «la». |
| 22 | «pueden participan» | «pueden participar». |
| 23 | «figura r3.2» | «figura 3.2». Hay una «r» sobrante. |
| 23 | «mostrar como»; «muestra como» | «mostrar cómo»; «muestra cómo». |
| 23 | «lína de tiempo» | «línea de tiempo». |
| 23 y 90 | «Diagrama de Se cuencia-UML» | «Diagrama de secuencia UML». El espacio interior está también en el glosario. |
| 23 | Final «figura 3.3» | Añadir punto final. |
| 24, figura 3.3 | «Diagrama Secuencia que representa como» | «Diagrama de secuencia que representa cómo». |
| 24, figura 3.3 | «la inmutabilidad y confianza propia» | «la inmutabilidad y la confianza propias». Añadir punto final al pie. |
| 24 | «debe de ser ’finito’ y no ’infinito’» | Si expresa obligación: «debe ser». Mejor sustituir toda la justificación por una referencia al alcance limitado del proyecto. |
| 25 | «incio comun» | «inicio común». |
| 25 | «Pantalla principal de prestamista/prestatario» | «Pantalla principal del prestamista/del prestatario». |
| 25 | Final «tablas 3.1 y 3.2» | Añadir punto final. |
| 26 | «casos de uso futuro» | «casos de uso futuros». |
| 26 | «segun» | «según». |
| 26 | «respectiva página correspondiente» | Eliminar la redundancia: «página correspondiente a su rol». |
| 28 | «En el momento que» | «En el momento en que». |
| 28 | «prestamos»; «su respectivos estados» | «préstamos»; «sus respectivos estados». |
| 28 | «-En» | «- En», o emplear una lista tipográfica uniforme. |
| 29 | «comprobar que mensualidades» | «comprobar qué mensualidades». |
| 29 | «aumentaran» | «aumentarán». |
| 30 | «prestámos»; «sistmea»; «prestamos» | «préstamos»; «sistema»; «préstamos». |
| 31, tabla 3.14 | «Definción» | «Definición». Corregir también el índice de tablas. |
| 31 | Final «sistema propuesto» | Añadir punto final. |
| 32, título 3.4 | «Análisis Smart contracts implicados» | «Análisis de los contratos inteligentes implicados». |
| 32 | «arquitectura de de diseño» | «arquitectura de diseño». |
| 32 | Final «figura 3.5» | Añadir punto final. |
| 33 | «En la figura anterior, 3.5, también define» | «La figura 3.5 también define» o «En la figura 3.5 también se representa». |
| 33 | «patron»; «asi»; «varibles» | «patrón»; «así»; «variables». |
| 33, listado 3.1 | «prestamos producto» | «préstamos producto»; mejor revisar el título para describir los préstamos en curso. |
| 33 | «prestamosCurando» | «prestamosCursando», según el identificador que aparece en el listado. |
| 34 | «Contract Factory , es decir cada Contrato Préstamo» | «Contract Factory, es decir, cada contrato de préstamo,»; cerrar el inciso antes de «mantiene». |
| 34 | «tal y como podemos ver en 3.2» | «tal y como se muestra en el listado 3.2». |
| 35 | «distintipos tipos» | «distintos tipos». |
| 35 | «identifacado» —dos veces— | «identificado»; mejor reformular ambas frases: «…si el usuario se identifica con la dirección del propietario». |
| 35 | «préstamo(Importe» | «préstamo (importe». |
| 36–38 | «Descripcion» | «Descripción». |
| 36 | «Devuelve la listado» | «Devuelve el listado». |
| 36 | «Contráto» | «Contrato». |
| 36 | «Transfiere unidades Contract Factory.» | Falta la preposición; si describe el ingreso: «Transfiere fondos al Contract Factory». |
| 37 | «a traves» | «a través». |
| 37 | «figura 3.18» | «tabla 3.18». |
| 38 | «calculoCuotaMensua» | «calculoCuotaMensual», si se refiere a la función del anexo. |
| 38 | «numero»; «calcula el la cuota» | «número»; «calcula la cuota». |
| 38 | «decisiones técnicas reservar responsabilidades» | «decisiones técnicas para asignar responsabilidades…». |
| 38 | «lineas» | «líneas». |
| 38 | «función 3.3» | «función del listado 3.3». |

### Capítulo 3: páginas 39–57

| Página | Texto actual | Corrección o actuación |
|---|---|---|
| 39 | «contrato prestamo» | «contrato de préstamo». |
| 39 | «se define un struct 3.4» | «se define una estructura, mostrada en el listado 3.4,». |
| 40 | «constructor del Contract Préstamo 3.5» | «constructor del contrato de préstamo, mostrado en el listado 3.5,». |
| 40, listado 3.5 | «struct TipoContrato» | El fragmento muestra un constructor. Propuesta: «Constructor de PrestamoCursando». |
| 40 | «Cada solicitud de producto solicitada» | «Cada solicitud de préstamo». |
| 40–41 | «se puede registrar las direcciones» | «se pueden registrar las direcciones». |
| 41 | «proporcionar mecanismo centralizado» | «proporcionar un mecanismo centralizado». |
| 41 | «función 3.6» | «función del listado 3.6». |
| 41 | «solidity»; «únidad»; «infromación» | «Solidity»; «unidad»; «información». |
| 41 | «contrato 3.8, El primer fragmento» | «contrato (listado 3.8). El primer fragmento». |
| 41, listado 3.7 | «Recuperacion de informacion» | «Recuperación de información». |
| 42, listado 3.8 | «Muestra de informacion» | «Muestra de información» o «Visualización de la información». |
| 42, texto de interfaz en código | «Fin plazo acutal» | «Fin del plazo actual». Es una etiqueta visible, no un identificador. |
| 43 | «En solidity […] actualizar realizar» | «En Solidity […] realizar». Véase la propuesta de frase completa. |
| 43 | «inical» | «inicial». |
| 43 | «Se puede ver como» | «Se puede ver cómo». |
| 45 | «independiente de la formación» | «independientemente de su formación». |
| 45 | «la interfaz si reúne» | «la interfaz sí reúne». |
| 45 | «no se ha recalcado en» | «no se ha hecho hincapié en». |
| 45 | «mas amigable»; «evalúar»; «identificadión» | «más amigable»; «evaluar»; «identificación». |
| 46, figura 3.7 | «Metmask» | «MetaMask». Corregir también el índice de figuras. |
| 46 | «con el el OS 6» | «con el OS 6». |
| 46 | «ejcutar»; «cutoas»; «despés» | «ejecutar»; «cuotas»; «después». |
| 46 | «es posible que […] puede suponer» | «es posible que […] pueda suponer». |
| 46 | «en caso de que tengo» | «en caso de que tenga». |
| 47 | «auomáticamente» | «automáticamente». |
| 48 | «OS7 el cuál» | «OS 7, el cual». |
| 48 | «necesidad existente en procesar» | «necesidad de procesar». |
| 48 | «posibildad» | «posibilidad». |
| 49 | «adjuntado distintas capturas» | «adjuntando distintas capturas». |
| 49 | «se puede comprobar distintos items» | «se pueden comprobar distintos ítems»; más natural: «distintos elementos». |
| 49 | «figura3.9» | «figura 3.9». |
| 49 | «usuario .» | «usuario.». |
| 49 | «una nueva transacción […] el cual es el contrato» | Reformular: una transacción y un contrato no son el mismo referente. |
| 49, figura 3.10 | «Panel de control usuario» | «Panel de control del usuario». |
| 50 | «figur»; «pude observar» | «figura»; «puede observar». |
| 50 | «366Wei» | «366 wei». |
| 50, figura 3.11 | «Información Etherscan»; «SmartContract» | «Información de Etherscan»; «contrato inteligente». |
| 51 | «a traves»; «verficación» | «a través»; «verificación». |
| 51–57 | «los test», «estos test» | Unificar como «las pruebas», «estas pruebas», o emplear «tests» si se conserva la voz inglesa en plural. |
| 51 | Final «Mocha test Framework» | «framework Mocha.» o «entorno de pruebas Mocha.». |
| 52 | Finales «Prestamo Contract» y «anexo B» | Añadir punto final. |
| 53, listado 3.9 | Líneas 3 y 15 con tres acentos graves | Eliminar los delimitadores Markdown impresos dentro del listado. Comprobado visualmente. |
| 53 | «se establece primero las variables» | «se establecen primero las variables». |
| 53 | «necesarias a la contratación» | «necesarias para la contratación». |
| 53 | «prestamo»; «prestamos» | «préstamo»; «préstamos» en el texto explicativo y el título del listado. |
| 53 | «para que se le pueda solicitar prestamos» | «para que se le puedan solicitar préstamos». |
| 55 | «El contenido de los test se pueden ver» | «El contenido de las pruebas se puede ver». |
| 55 | «a) 1. Pruebas…» y «b) 2. Pruebas…» | Evitar la doble numeración; conservar un solo nivel. |
| 57 | «metodo»; «indice»; «publica» | «método»; «índice»; «pública». Más natural: «Esta función es pública». |
| 57 | «una atacante malicioso» | «un atacante malicioso». |
| 57 | «timeOut Mocha» | «tiempo de espera de Mocha» o «timeout de Mocha». |
| 57 | «Dejando a parte» | «Dejando aparte». |
| 57 | «proceso de de validación» | «proceso de validación». |
| 57 | «dolares»; «suamndo» | «dólares»; «sumando». |

### Capítulo 4, anexos, referencias y glosario

| Página | Texto actual | Corrección o actuación |
|---|---|---|
| 58 | «se pueden llegar a las siguientes conclusiones» | «se puede llegar a las siguientes conclusiones». |
| 58 | «el contrato de nuevos préstamos queda […] automatizado» | «la contratación de nuevos préstamos queda […] automatizada». |
| 58 | «dentro de la una interfaz» | «dentro de una interfaz». |
| 58 | «ejecución en la red las operaciones» | «ejecución en la red de las operaciones». |
| 58 | «realización de préstamo» | «concesión de préstamos». |
| 58 | «Exite» | «Existe». |
| 58 | «del uso que se de» | «del uso que se dé». |
| 59 | «prestamos»; «prestamo» | «préstamos»; «préstamo». |
| 59 | «CU12 :» | «CU12:». |
| 59 | «automaticamente»; «debera»; «solided» | «automáticamente»; «deberá»; «solidez». |
| 59 | «En situaciones en los que» | «En situaciones en las que». |
| 59 | «se pudo comprobar las ineficencias» | «se pudieron comprobar las ineficiencias». |
| 59 | «Sobretodo evitar» | «Sobre todo, se debe evitar». |
| 59 | «ninguna característica en las que» | «ninguna de las características en las que». |
| 59 | «manteniendo siempre reflejado […] la situación» | «manteniendo siempre reflejada […] la situación». |
| 60 | «sección de 3.2.1» | «sección 3.2.1». |
| 60 | «abrueba» | «aprueba»; revisar además el tiempo verbal y la cronología. |
| 60 | «En el 2 se habla» | «En el objetivo principal 2 (OP 2) se establece». La referencia ha quedado incompleta. |
| 60 | «facil»; «Aunque si»; «crar»; «intefaz» | «fácil»; «Aunque sí»; «crear»; «interfaz». |
| 60 | «más intuitiva al usuario» | «más intuitiva para el usuario». |
| 60 | «sistemas que utilicen Oráculo» | «sistemas que utilicen oráculos». |
| 60 | «tipos de prestamo» | «tipos de préstamo». |
| 61 y 93 | «Coperación» | «Cooperación». Corregir también la sigla OCDE. |
| 61 | «aumenter»; «A demás» | «aumentar»; «Además». |
| 61 | «plataformas DeFi y lo que podría» | «plataformas DeFi, lo que podría». |
| 61 | «la responsabilidad […] dificultan» | «la responsabilidad […] dificulta». |
| 63 | «potential» | «potencial». |
| 63 | «objetivos relacionados en el ámbito» | «objetivos relacionados con el ámbito». |
| 63 | «El desarrollo de plataforma DeFi» | «El desarrollo de plataformas DeFi». |
| 63 | «articifiales»; «esta tecnologías»; «mas» | «artificiales»; «estas tecnologías»; «más». El párrafo necesita reformulación completa. |
| 63 | «la transparencia […] suponen» | «la transparencia […] supone». |
| 63 | «valided» | «validez». |
| 63–64 | «aunque, es cierto, que» | «aunque es cierto que». |
| 64 | «lo mismo que los apartados anteriores» | «lo mismo que en los apartados anteriores». |
| 64 | «utilizar […] en paliar» | «utilizar […] para paliar». |
| 64 | «efectos adversos que este sistema incide» | «efectos adversos que este sistema provoca». |
| 65 | «descentralizada. y el contrato» | «descentralizada, y el contrato» o reconstruir la enumeración completa. |
| 65 | «Prestamos Factory» | Si es el nombre del contrato: `PrestamosFactory`. |
| 68, comentarios | «conrtrato»; «faciltar» | «contrato»; «facilitar». |
| 69, comentarios | «ultimo»; «nostros» | «último»; «nosotros». |
| 72, comentarios | «no de un numero entero»; «despues» | «no dé un número entero»; «después». |
| 73, comentario | «Numero de cuotas» | «Número de cuotas». |
| 75 | «los smart contract» | «los contratos inteligentes». |
| 75 | «préstamos cursando» | «préstamos en curso». |
| 75, listado B.1 | «Pruebas de prestamos cursando» | «Pruebas de préstamos en curso». |
| 78, comentario | «Inversion inicial» | «Inversión inicial». |
| 79, comentarios | «Pago ultima cuota»; «sus estado» | «Pago la última cuota»; «su estado». |
| 80, comentario | «ni el el prestamo» | «ni el préstamo». |
| 83, textos de pruebas | «diferrent»; «porcentage»; «porentage» | «different»; «percentage»; «percentage». |
| 89, referencia [32] | «Criptoativos» | «Criptoactivos». |
| 90 | «básada» | «basada». |
| 90, dApp y DeFi | «Descentrelized» | «Decentralized». |
| 90, DeFi | «descentralizdo» | «descentralizado». |
| 91 | «Javascript»; «Metamask» | «JavaScript»; «MetaMask». |
| 91, ETH | «Ether, es» | «Ether es». |
| 92, Solidity | «programarSmart Contract» | «programar contratos inteligentes». Falta un espacio. |
| 92, Tipo Address | «En solidity»; «que valores»; «a el de una dirección» | «En Solidity»; «qué valores»; mejor: «El tipo address representa direcciones de la red». |
| 92, SHA-256 | «Secure Hash Algorithm 256, es» | Eliminar la coma entre sujeto y predicado o formular la expansión entre paréntesis. |

## 3. Frases que conviene sustituir completas

Las siguientes propuestas conservan la intención que se desprende del texto, pero eliminan ambigüedades y construcciones defectuosas. En los casos donde hay una decisión de contenido, se indica expresamente.

### Página 1: motivación y centralización

**Localizador:** «Debido a que la existencia de las criptomonedas no soluciona directamente el problema de la necesidad…».

**Propuesta:** «La existencia de criptomonedas no elimina por sí sola la dependencia de los bancos tradicionales y de otras entidades centralizadas para acceder a financiación. Este proyecto propone una alternativa basada en contratos inteligentes.»

**Localizador:** «Aunque el acceso a la financiación […] sea descentralizada […] incentivar la producción de este sistema a una entidad competente».

**Propuesta:** «Aunque los usuarios acceden al sistema mediante una aplicación descentralizada, la oferta de financiación queda centralizada en una única entidad, responsable de definir los productos y aportar los fondos.»

La expresión «incentivar la producción […] a una entidad» no permite saber si se habla de desarrollo, explotación o puesta en producción. Si esa motivación es importante, añadir una frase específica.

### Página 2: introducción de los objetivos

**Propuesta:** «En esta sección se detallan los objetivos del proyecto. Se distinguen dos objetivos principales (OP) y siete objetivos secundarios (OS), que concretan distintos aspectos de su desarrollo.»

Evita la doble expansión de las siglas y la unión de dos oraciones completas mediante una coma.

### Página 3: seguridad, eficiencia y rentabilidad

**Localizador:** «Alcanzar la seguridad y eficiencia en los gastos del sistema, suponiendo esto…».

**Propuesta:** «Otra motivación es desarrollar un sistema seguro y eficiente en costes. Ambos aspectos son esenciales para su viabilidad económica y pueden convertirse en puntos débiles si no se abordan con suficiente detalle.»

### Página 6: presentación de los protocolos

**Propuesta:** «El ecosistema de las finanzas descentralizadas (DeFi) ha experimentado un crecimiento significativo en los últimos años. Esto ha favorecido la aparición de distintos protocolos que ofrecen servicios financieros con características propias. El análisis siguiente se centra en sus aspectos tecnológicos y en su relación con la solución propuesta.»

Conserva aparte, si se desea mantener, la explicación sobre sus equipos y comunidades; la afirmación de que no constituyen estándares no se deduce simplemente de que los hayan desarrollado equipos privados.

### Página 12: seguridad de la red

**Localizador:** «el resto de la red sigue siendo seguro, de hecho dependiendo […] mientras ente el 51 y 70 %…».

**Propuesta editorial:** «La distribución del control entre numerosos nodos reduce la dependencia de un único participante. Las condiciones necesarias para mantener la seguridad dependen del protocolo de consenso de cada red.»

Los porcentajes del original requieren justificación técnica independiente; no conviene conservarlos como una regla general solo corrigiendo la gramática.

### Página 13: pie de la figura 2.2

El pie mezcla nombres de redes con el título de una referencia: «Solana [14], BNBChain [15], “Historia de Ethereum…” [17] las cuales…».

**Propuesta, si coincide con la captura:** «Figura 2.2. Información de mercado de Ethereum, Solana y BNB Chain consultada el 14 de marzo de 2024. Fuente: CoinMarketCap [16].»

Ajustar los activos y la fecha a lo que realmente aparece en la captura. No presentar una imagen estática como información en tiempo real.

### Página 15: conclusión sobre Ethereum

**Localizador:** «desarrollar la intencionalidad del proyecto […] e incluso añadir avales…».

**Propuesta:** «Ethereum ofrece un entorno adecuado para desarrollar el proyecto gracias a la EVM y a la posibilidad de implementar contratos inteligentes. El prototipo utiliza ETH como activo de préstamo. La incorporación de garantías mediante NFT y datos externos se plantea como una posible ampliación futura.»

Esta redacción permite distinguir lo implementado de lo propuesto para el futuro.

### Página 16: Ganache

**Localizador:** «Perfecto para el desarrollo aunque tiende a fallar.»

**Propuesta:** «Ganache permite ejecutar una red local para realizar pruebas durante el desarrollo.» Si los fallos observados son relevantes, describirlos de forma concreta en una frase adicional; «tiende a fallar» es demasiado general.

### Página 17: Web3

El párrafo emplea «web3» para la evolución de la web y para una herramienta de programación sin distinguir ambos usos.

**Propuesta editorial:** «El término Web3 se utiliza para describir aplicaciones y servicios web basados en tecnologías descentralizadas. En este proyecto también se utiliza la biblioteca Web3.js para conectar la aplicación con la red, consultar información e interactuar con los contratos inteligentes.»

Comprobar que el nombre y la versión de la biblioteca coinciden con el proyecto documentado.

### Página 19: solución propuesta

**Localizador:** «se basa en en el diseño […] deja escrita en la red…».

**Propuesta:** «El sistema se basa en contratos inteligentes que registran en la red la información necesaria para gestionar los préstamos. Estos contratos permiten automatizar parte de la gestión y conservar un historial de las operaciones.»

### Página 22: limitación de escalabilidad

**Propuesta:** «Esta situación no tiene por qué invalidar el proyecto, pero sí exige un desarrollo orientado a mejorar su escalabilidad.»

### Página 25: presentación de pantallas

**Localizador:** «se realiza una declaración de las posibles pantallas que participan en el sistema son».

**Propuesta:** «Para facilitar la comprensión de los casos de uso, se enumeran las principales pantallas del sistema:».

### Página 38: decisiones de implementación

**Propuesta:** «Durante el desarrollo de los contratos inteligentes se han tomado decisiones técnicas sobre la distribución de responsabilidades entre la aplicación y la red, el control de acceso y el registro de las transacciones. A continuación, se presentan las principales decisiones adoptadas.»

### Páginas 40–41: identificación de los préstamos

**Propuesta:** «Cada solicitud de préstamo genera un nuevo contrato con una dirección propia. El contrato principal registra su asociación con el prestatario en la variable prestamosCursando. De este modo, se pueden consultar y administrar los préstamos vinculados a cada usuario.»

### Página 43: protección frente a reentrada

**Propuesta:** «En Solidity es una buena práctica validar las condiciones de una operación y actualizar el estado del contrato antes de realizar transferencias de fondos.»

La expresión original «actualizar realizar» es un resto de edición.

### Página 45: evaluación de la interfaz

**Propuesta:** «La interfaz reúne las funcionalidades del sistema en un único punto de acceso. Sin embargo, durante el desarrollo se ha priorizado la funcionalidad, por lo que la mejora de su accesibilidad y facilidad de uso se plantea como trabajo futuro.»

### Página 46: coste del chequeo mensual

**Propuesta:** «Las funciones que interactúan con la red son sencillas y evitan procesamientos innecesarios. No obstante, la comprobación mensual de los pagos podría resultar costosa si aumenta el número de préstamos. Por ello, se propone estudiar mejoras que reduzcan el procesamiento necesario.»

### Página 49: transacción de creación del contrato

**Propuesta:** «Se ha registrado una transacción de creación de contrato (Contract Creation), correspondiente al nuevo préstamo.»

### Página 57: validación y viabilidad

**Localizador:** «puede llegar a niveles de producción en un entorno real. Dejando a parte…».

**Propuesta:** «Las pruebas realizadas permiten valorar la viabilidad técnica del prototipo. Su utilización en un entorno real requeriría desarrollar los mecanismos adicionales descritos en el apartado de trabajo futuro.»

La conclusión debe ajustarse a lo efectivamente probado; «niveles de producción» no define un criterio comprobable.

**Localizador:** «la cantidad de procesamiento aumenta linealmente […] suamndo esto…».

**Propuesta:** «El procesamiento del chequeo mensual aumenta con el número de contratos. Si este incremento coincide con un coste elevado del gas, la operación puede resultar demasiado costosa. Por ello, sería necesario optimizar la forma en que se realiza la comprobación.»

### Página 58: conclusión sobre la interfaz

**Propuesta:** «Es posible reunir las herramientas de gestión en una única interfaz de usuario, capaz de conectarse con Ethereum y solicitar las operaciones necesarias para administrar los préstamos.»

### Página 59: garantías

**Localizador:** «Se considera la más importante la adopción de garantías de impago…».

**Propuesta:** «La mejora prioritaria es incorporar garantías de devolución en caso de impago, como se recoge en el caso de uso futuro CU12. Aunque el sistema aplica penalizaciones, estas no garantizan por sí mismas la recuperación del capital prestado.»

### Página 61: brecha digital

**Propuesta:** «El acceso a estos servicios requiere conocimientos sobre criptomonedas, carteras digitales y plataformas DeFi, lo que podría ampliar la brecha digital. Además, la responsabilidad de los usuarios sobre la gestión de sus propios activos puede dificultar la utilización de estas herramientas.»

Mantener la referencia que respalde estas afirmaciones y comprobar que la paráfrasis respeta su contenido.

### Página 63: desigualdad e injusticia social

El párrafo que empieza «El desarrollo de plataforma DeFi…» contiene una frase rota: «si no se combate la brecha digital y se evita la creación de barreras articifiales pueden aumentar por parte de los desarrolladores…». La relación entre las condiciones y sus consecuencias queda confusa.

**Propuesta:** «El desarrollo de plataformas DeFi podría contribuir a reducir las desigualdades y favorecer la justicia social (ODS 10). Sin embargo, su impacto depende del uso de la tecnología. Si no se combate la brecha digital ni se evitan nuevas barreras de acceso, estas plataformas podrían aumentar las desigualdades en lugar de reducirlas.»

### Página 63: transparencia y ODS 16

**Propuesta:** «En relación con el ODS 16, la transparencia del registro de transacciones puede facilitar la detección de irregularidades. Su utilidad social depende también de la existencia de mecanismos de supervisión y de una aplicación efectiva de la justicia.»

La expresión «la justicia NO es igual para todos» introduce un registro enfático y una afirmación general poco conectada con la explicación técnica.

### Página 64: cierre ambiental

**Propuesta para el cierre del párrafo:** «Además del consumo energético, deben considerarse otros efectos ambientales, como la gestión de los residuos de la infraestructura. Parte de las mejoras de productividad y de los recursos obtenidos podría destinarse a mitigar estos impactos.»

### Página 65: introducción al anexo A

**Propuesta:** «El archivo PRESTAMOS_FACTORY.sol incluye el contrato principal PrestamosFactory, encargado de gestionar los tipos de préstamo y la creación de nuevos contratos, y el contrato PrestamoCursando, que representa un préstamo individual en curso.»

## 4. Puntuación, caracteres sueltos y presentación

### Fallos confirmados

- **Página 23:** sobra la «r» de «figura r3.2».
- **Páginas 9 y 88:** aparece una «S» aislada al final del título «CIENCIAS ECONÓMICAS S».
- **Página 53:** se imprimen dos líneas de tres acentos graves dentro del listado 3.9. Son delimitadores de Markdown que no pertenecen al fragmento mostrado.
- **Páginas 68–69:** la llamada al constructor `new PrestamoCursando(...)` queda descompuesta; en la página 69 aparecen puntos y comas aislados en una columna a la derecha, y parte del texto rebasa el margen. Es un fallo de composición, no necesariamente puntuación sobrante en el código. Repartir los argumentos en líneas con sangría normal y recompilar.
- **Página 92:** falta un espacio en «programarSmart Contract».
- **Páginas 7, 19, 32, 46, 57 y 80:** hay duplicaciones como «la la», «en en», «de de» y «el el».

### Glosario: puntos duplicados

En las páginas 90–93 hay finales con «..» o «. .». Se ven, entre otras, en las entradas App Store, Blockchain, criptomoneda, Diagrama de secuencia UML, Diagrama-UML, Euribor, Gas, hash, JavaScript, MetaMask, Oráculo, Pool, Pop-up, script, la segunda entrada Smart Contract, Tipo Address, Uniswap, Wallet, Web3 y Wei.

Dejar un único punto antes de las referencias de página. Por el patrón repetido, revisar si la plantilla añade un punto y la definición ya incluye otro. Esta es una hipótesis sobre la causa; los puntos duplicados sí están presentes visualmente.

### Títulos, referencias y listas

- Los títulos de figuras y tablas deben seguir un criterio uniforme. Preferir «Diagrama de entidad-relación» o «Diagrama entidad-relación», y «Diagrama de secuencia UML»; evitar variantes mezcladas.
- Cambiar «Arquitectura y Desarrollo» por «Arquitectura y desarrollo» si se sigue el criterio habitual de mayúscula inicial en los títulos en español.
- Evitar referencias desnudas: «en 3.2», «función 3.3», «struct 3.4». Utilizar «en el listado 3.2», «la función del listado 3.3» y «la estructura del listado 3.4».
- En las listas con título y explicación en el mismo párrafo, insertar dos puntos o punto: «Identidad: …», «Cuentas utilizadas para las pruebas: …».
- Unificar los puntos finales de las descripciones y flujos de casos de uso. En las páginas 26–31 hay frases completas terminadas sin punto junto a otras que sí lo llevan.
- Utilizar «etc.»; no «etc..» ni «etc…».
- No separar sujeto y verbo con coma. Ejemplos claros: «Ether, es» y «Secure Hash Algorithm 256, es».
- Revisar las oraciones completas unidas solo por coma, frecuentes en las páginas 6–9, 16, 19–21, 29, 48, 57, 59 y 63. En muchos casos conviene un punto y seguido.
- Cuando una referencia corresponde a una oración, mantener un criterio uniforme, por ejemplo: «…entorno digital global [1].».

### Elementos que no deben corregirse como si fueran basura

Los signos del código (`_;`, llaves, punto y coma, flechas, operadores) pueden aparecer solos en una línea y ser necesarios. No eliminarlos por su apariencia. Tampoco añadir tildes a identificadores como `prestamosCursando`, `penalizacionImpago` o `ultimoCheckeo` mediante una sustitución global. Las tildes sí deben corregirse en los comentarios, títulos y texto narrativo.

El identificador `acutalInfo` de la página 77 está escrito de forma poco afortunada; puede renombrarse a `actualInfo`, pero solo cambiando consistentemente sus referencias en el código. No es una errata que deba retocarse únicamente en la transcripción del PDF.

## 5. Terminología y uniformidad editorial

Estas son decisiones de estilo, no faltas ortográficas en todos los casos:

| Tema | Criterio recomendado |
|---|---|
| Contratos inteligentes | Usar «contrato inteligente» y «contratos inteligentes» en el texto. Si se conserva el inglés, mantener «smart contract» / «smart contracts» y no alternar con «SmartContract». |
| Marcas y lenguajes | Mantener Ethereum, Solidity, JavaScript, TypeScript, MetaMask, Node.js y Etherscan con grafía uniforme. |
| Blockchain | Elegir «blockchain» o «cadena de bloques» para el concepto general y aplicar el criterio de forma consistente. |
| Gas y wei | Usar «gas» y «wei» de manera uniforme; separar cifras de unidades: «366 wei», «1000 wei». |
| Login | Preferir «inicio de sesión» o «identificación». Ahora alternan login, log in y Log-In. |
| Pruebas | Preferir «pruebas unitarias» a alternar test, tests y Mocha test. |
| Wallet, pool y framework | Introducir «cartera», «fondo de liquidez» y «entorno de trabajo/biblioteca», según corresponda, y mantener una terminología estable. |
| Costos/costes | Ambas formas son válidas; «costes» encaja con el español de España utilizado en la memoria. |
| Prestamista/prestatario | Mantener la distinción: el prestamista aporta fondos; el prestatario recibe el préstamo. Revisar especialmente CU10 y CU11. |
| Propietario | Elegir «entidad prestamista» o «propietario del sistema». «Entidad bancaria» no siempre es equivalente a «entidad financiera». |
| Comillas | Usar «comillas angulares» de forma consistente en prosa y reservar las comillas de programación para el código. |

## 6. Coherencia interna que conviene resolver

Estas observaciones se basan en comparaciones dentro del propio PDF. No constituyen una auditoría técnica ni legal.

1. **Centralización, páginas 1–2 y 19.** El OP 1 habla de un sistema «sin una entidad centralizada controladora», pero la solución reserva la oferta y administración a una única entidad. Precisar qué parte se descentraliza y qué facultades conserva el propietario.

2. **CU10 y CU11, páginas 25 y 30.** La tabla resumen dice «Recoger fondos del prestatario» y «Transferir fondos al prestamista», mientras las fichas detalladas describen retirar fondos del sistema e ingresarlos en él. Unificar los nombres con la operación realmente documentada.

3. **Tabla 3.16, página 36.** `crearTipoPrestamo` y `crearPrestamo` tienen prácticamente la misma descripción, aunque sus nombres y el resto del texto distinguen crear un producto y contratar un préstamo. La fila `consultarPrestamosUsuario` no tiene descripción. Completarla y corregir «Devuelve la listado» y la frase incompleta de `invertirFondos`.

4. **Nombres de funciones, páginas 36–38 frente al anexo A.** Las tablas presentan nombres como `crearTipoPrestamo`, `crearPrestamo`, `recuperarFondos`, `invertirFondos`, `pagoCuota` y `aplicarPenalización`, mientras el anexo utiliza `definirPrestamo`, `contratarPrestamo`, `recolectarFondos`, `invertir`, `pagarMensualidad` y `penalizarPrestamo`. Si las tablas son conceptuales, indicarlo; si documentan la implementación, actualizar los nombres y verificar la correspondencia.

5. **Tipos de datos, página 37.** La tabla 3.17 utiliza `Float` para la deuda y la cuota, pero el listado 3.2 y el anexo emplean `uint256`. La página 41 también explica que se utilizan enteros. Ajustar la tabla.

6. **Tipos de préstamo y préstamos en curso, página 33.** El título del listado 3.1 dice «préstamos producto», pero el identificador y la explicación se refieren a `prestamosCursando`. Poner un título que describa el dato mostrado.

7. **Constructor, página 40.** El listado 3.5 se titula igual que el 3.4, «struct TipoContrato», aunque presenta un constructor. Corregir también el índice de listados.

8. **Objetivos secundarios, páginas 3 y 46–48.** El OS 3 trata de optimizar gas y el OS 4 de mecanismos de control y penalización. En la validación, el punto asociado al OS 3 describe pagos y penalizaciones, y no aparece una justificación explícita del OS 4. Revisar la asignación de evidencias a objetivos.

9. **Estado de `setIndex`, página 57 y anexo A, página 72.** El texto describe un acceso indebido, pero el código presentado ya incluye `onlyContractFactory`. Aclarar si se trata de un fallo encontrado y corregido, de una versión anterior o de una limitación pendiente. La explicación actual mezcla estados distintos del desarrollo.

10. **Biblioteca de aserciones, páginas 52 y 56 frente a los anexos B.** El cuerpo menciona Chai, mientras los archivos mostrados importan `require('assert')`. Ajustar la descripción a las pruebas incluidas o aportar la versión que realmente usa Chai.

11. **Pruebas y resultado, páginas 55–57.** Se afirma que las pruebas demuestran el funcionamiento correcto. Conviene incorporar o identificar el resultado concreto de ejecución al que corresponde esa conclusión, especialmente si los anexos o el código han cambiado después.

12. **Estados, comentario de la página 79.** Se dice que el contrato pasa de «PAGADO» a «PRESTAMO», pero la enumeración del anexo contiene `PAGADO`, `ABIERTO` y `FINALIZADO`. Si se refiere al valor 1 comprobado en la prueba, el comentario debería decir «ABIERTO».

13. **Cronología normativa, páginas 20 y 60 frente a referencia [32].** El cuerpo habla de aprobación en diciembre de 2024 y la referencia está fechada en 2023. Distinguir aprobación y aplicación, y verificar las fechas antes de cerrar el texto. Este informe no valida la interpretación jurídica ni los importes del apartado.

14. **Agenda 2030, páginas 62–63.** El texto la presenta como un plan global adoptado por la ONU, pero el pie de la figura 4.1 dice «agenda europea». Unificar la atribución de acuerdo con la fuente de la imagen y el texto.

15. **Bibliografía [12], página 88.** La referencia a la imagen del proceso de transacción figura con título «SepoliaFaucet», que no corresponde a cómo se describe y utiliza esa imagen. Revisar sus metadatos.

16. **Bibliografía [13] y [17], página 88.** Ambas apuntan a la misma URL de Ethereum con títulos ligeramente distintos. Si representan la misma fuente, fusionarlas y actualizar las citas.

17. **Autores bibliográficos, páginas 87–89.** Aparecen formas como «A. V3», «C. III», «U. V4», «C. M. Cap» y «U. Europea», además de cadenas de autores en mayúsculas y mal separadas en [10] y [11]. Revisar la declaración de autores corporativos y personales en el archivo bibliográfico.

18. **Glosario, página 92.** Existen dos entradas distintas con el mismo rótulo «Smart Contract». Unificarlas o diferenciar claramente los conceptos si se pretendía distinguirlos.

19. **Afirmaciones que necesitan precisión más allá de la ortografía.** Antes de entregar, conviene revisar por separado la explicación de PoS en la página 10, la identificación mediante MetaMask en la página 46, la justificación del uso de enteros en la página 41 y la definición de NFT en la página 92. La redacción actual introduce relaciones que no se resuelven con una corrección lingüística. No se han comprobado contra documentación externa en esta revisión.

## 7. Comprobación final tras aplicar los cambios

- Corregir en los archivos fuente para que los cambios se reflejen también en índices, pies, bibliografía y glosario.
- Regenerar el PDF y revisar especialmente las páginas con tablas, los listados 3.9 y A.1 y las entradas del glosario.
- Buscar las cadenas «la la», «el el», «de de», «en en», «r3.2», «Se cuencia», «programarSmart», «ECONÓMICAS S» y los triples acentos graves.
- Buscar variantes de MetaMask, Ethereum, Solidity, JavaScript y smart contract para unificar el criterio.
- Confirmar que no se han alterado identificadores de código por sustituciones ortográficas generales.
- Revisar la nueva paginación si las reformulaciones cambian los saltos de página.

**Conclusión editorial:** la memoria necesita una corrección formal adicional. Las erratas no se limitan a unas pocas tildes: también hay frases rotas, referencias incompletas y desajustes entre tablas, texto y código. La relación anterior permite resolverlos de forma localizada antes de generar la versión definitiva.
