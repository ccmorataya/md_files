# Microsoft SQL Server

![sqlserver-linea-de-tiempo](https://image.slidesharecdn.com/diplomadosqlserver2012-session001-140111233726-phpapp02/95/diplomado-tcnico-sql-server-2012-sesin-18-6-638.jpg?cb=1389557673)

Microsoft SQL Server o SQL Server es un RDBMS (Relational DataBase Management System) desarrollado por Microsoft, como un servidor de base de datos es un producto con la función primaria de almacenar y obtener data solicitada desde otras aplicaciones, las cuales pueden correr tanto en la misma máquina, o en otra a través de una red (o internet).
Inicio con SQL Server 1.0 en el año de 1989 y se ha mantenido al día de hoy incluyendo diversas mejoras e interoperabilidad, se encuentra desarrollado en C, C++; la versión más reciente SQL Server 2017 (14.0) se encuentra disponible no solo para sistemas operativos Windows, sino tambien para Linux y para contenedores Docker [¹], el lenguaje utilizado dentro del mísmo cumple con los estandares SQL, sin embargo lo han extendido con la implementación de T-SQL, tradicionalmente la instalación de SQL Server es únicamente el motor de base de datos, sin embargo desde hace tiempo atras se ha incorporado la herramienta SSMS (SQL Server Management Studio) la cual es una interfáz gráfica para interactuar con el motor.

## Posición en el mercado

![sqlserver-gant](https://msdnshared.blob.core.windows.net/media/2017/11/Gartner_ODBMS_MQ_20171.jpg)

Segun Gartner, Inc. en noviembre de 2017 Microsoft presumia de ser el lider en relación a los ODBMS, solo por sobre Oracle, AWS, SAP e IBM. Teniendo en cuenta que el sistema está diseñado para ser seguro, incorporando capas de cifrado, autenticación, monitoreo y auditoria tanto de disco como de base de datos y aplicación [²]  
Definitivamente SQL Server tiene gran impacto y presencia al punto de ser de los más populares motores de bases de datos SQL, junto a MySQL (MariaDB), Oracle y PostrgreSQL.

## Ventajas
* Facilidad de sopoerte de transacciones
* Escalabilidad, estabilidad y seguridad
* Soporte de procesos almacenados (Stored Procedures)
* Entorno gráfico incluido
* Producto bastante maduro y con buena base cimentada y buena comunidad
* Alta capa de seguridad permitiendo administrar permisos para todo

## Desventajas
* Alta utilización de memoria RAM
* Relación calidad-precio esta por debajo de Oracle
* Bastante restrictiva para cuestiones de prácticas
* Tamaño de página fijo y demasiado pequeño
* Mala implementación de dipos de datos y variables
* Limitante de conexiones simultaneas para las páginas

#### ¹ [Wikipedia SQL Server](https://en.wikipedia.org/wiki/Microsoft_SQL_Server)
[¹]:#-wikipedia-sql-server    

#### ² [Blog technet Microsoft](https://blogs.technet.microsoft.com/microsoftlatam/2017/11/21/tres-anos-consecutivos-microsoft-es-un-lider-en-el-cuadrante-magico-de-sistemas-de-administracion-de-bases-de-datos-operativas/)
[²]:#-blog-technet-microsoft
