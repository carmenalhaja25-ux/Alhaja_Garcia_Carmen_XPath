# Alhaja_Garcia_Carmen_XPath
Este repositorio contiene mi trabajo para la unidad de Almacenamiento de información en formatos de intercambio de datos. Como parte del equipo de auditoría de TechNova Cloud, mi misión ha sido extraer información específica sobre el inventario de hardware y software de sus centros de datos.

He utilizado VS Code y la extensión XPath Notebook para generar un informe de consultas preciso sobre el archivo CatalogoCloud.xml. El objetivo es demostrar el uso de lenguajes de consulta (XPath) para gestionar información en documentos de intercambio de datos.

Mis archivos recogidos para realizar este trabajo son:
auditoria_Alhaja_García_Carmen.xbook: Archivo principal con las consultas XPath solicitadas.
CatalogoCloud.xml: El catálogo de datos que sirve como base para las consultas.
CatalogoCloud.xsd: El esquema de validación del documento XML.

En el archivo .xbook he resuelto las siguientes tareas de auditoría:
Misión 1 (Seguridad): Listado de puertos de servicios que funcionan en la ubicación de Paris.
Misión 2 (Mantenimiento): Identificación de la versión del sistema operativo para el servidor con ID srv-db-01.
Misión 3 (Capacidad): Localización de todos los discos con capacidad igual o superior a 8 TB.
Misión 4 (Eficiencia): Búsqueda del primer servidor registrado que se encuentra en estado "apagado".
Misión 5 (IA): Extracción del atributo de arquitectura de la CPU en aquellos servidores que cuentan con una GPU instalada.

Gracias a esta auditoría, he puesto en práctica el uso de XPath para la extracción de datos en entornos profesionales y he aprendido a realizar navegaciones tanto absolutas como relativas y a utilizar filtros avanzados (predicados) para localizar información específica, como versiones de sistemas operativos o capacidades de hardware.