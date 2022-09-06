
# [¿Qué es PostgreSQL?](https://blog.infranetworking.com/servidor-postgresql/)

## Para qué sirve, características e instalación.

Es un sistema de código abierto de administración de bases de datos del tipo relacional, aunque también es posible ejecutar consultas que sean no relaciones. En este sistema, las consultas relacionales se basan en SQL, mientras que las no relacionales hacen uso de JSON.

* Es de código abierto.
* Es gratuito.
* Ese multiplatforma.
* Es facil de usar.
* Permite manejar gran volumen de datos.
* Soporte total de ACID.

Dos detalles a destacar de PostgreSQL es que posee data types (tipos de datos) avanzados y permite ejecutar optimizaciones de rendimiento avanzadas, que son características que por lo general solo se ven en sistemas de bases de datos comerciales, como por ejemplo SQL Server de Microsoft u Oracle de la compañía homónima.

## *Cómo administrar PostgreSQL mediante interfaz gráfica.*

**pgAdmin:** es probablemente el gestor de PostgreSQL más conocido y utilizado del mundo. Es fácil de utilizar, intuitivo y compatible con gran cantidad de sistemas operativos, además claro de ser gratuito. Estas características han hecho que se vuelva una de las herramientas más utilizadas a la hora de administrar bases de datos en Postgres. Inicialmente era conocido como pgManager pero con el paso del tiempo cambió de nombre. Su versión más reciente es pgAdmin 4 y podemos correrlo en diversos entornos como Windows, Linux y macOS.

**PhpPgAdmin:** esta herramienta es muy parecida a phpMyAdmin, más incluso que la ya nombrada pgAdmin. Si conoces phpMyAdmin entonces no tendrás muchos problemas para utilizarla pues funciona de manera muy similar. En el menú izquierdo del programa se despliegan los servidores de PostgreSQL y las bases de datos que contiene cada uno, y del lado derecho tenemos diversas herramientas y funcione como por ejemplo exportar e importar, ajustar privilegios, editar campos, etc.

**DBeaver:** es un conocido programa para administrar bases de datos. No solo es compatible con Postgres, sino también con muchos motores más como por ejemplo MySQL, Oracle, SQL Server, MariaDB, etc. Este estupendo gestor está disponible para distintos sistemas operativos y es completamente gratuito. Sus características y funciones hace que sea una de las herramientas preferidas de gran cantidad de usuarios, desarrolladores y administradores de servidores de bases de datos que trabajan a diario con Postgres.

## Comparación de PostgreSQL vs MySQL

En lo que refiere a las consultas o queries, las soportadas por MySQL tienden a ser más simples, mientras que PostgreSQL soporta queries más complejas, lo cual le ha válido el título del sistema de bases de datos relacionales más avanzado del mercado.
En términos de rendimiento cada uno tiene su situación para brillar: MySQL es mejor si se manejan bajos volúmenes de datos, es decir, si tenemos bases de datos pequeñas o medianas a las cuales se hagan una cantidad de consultas no muy alta. Por su parte, PostgreSQL es mejor a la hora de manejar volúmenes de datos grandes y se suele usar más cuando se tienen bases de datos grandes y con alta cantidad de consultas.
Si miramos el cumplimiento de ACID nos toparemos conque MySQL no lo soporta al 100%, sino solamente las tablas que hagan uso de NDB Cluster o InnoDB, mientras que PostgreSQL sí lo soporta completo en todos los casos.

**Resumiendo**, por ahora ambos son gratis, así que debemos elegir basándonos en rendimiento más que nada: si quieres un sistema para bases de datos medianas o pequeñas y consultas no muy complejas ni muy abundantes ve por MySQL, de lo contrario PostgreSQL es mejor opción si vas a manejar un volumen notable de datos.


# [Introducción a Supabase](https://supabase.com/docs/guides/database)

Supabase is an open source Firebase alternative providing all the backend features you need to build a product. You can use it completely, or just the features you need.

Start a project with the [hosted](https://app.supabase.com/) platform or learn how to [host Supabase](https://supabase.com/docs/guides/hosting/overview) yourself.

## Postgres or PostgreSQL?
PostgreSQL the database was derived from the POSTGRES Project, a package written at the University of California at Berkeley in 1986. This package included a query language called "PostQUEL".

In 1994, Postgres95 was built on top of POSTGRES code, adding an SQL language interpreter as a replacement for PostQUEL. Eventually, Postgres95 was renamed to PostgreSQL to reflect the SQL query capability.

After this, many people referred to it as Postgres since it's less prone to confusion. Supabase is all about simplicity, so we also refer to it as Postgres.
## videos misiontic
[generalidades de base de datos](https://youtu.be/PWO2ZREcS7s)
[]()

# entidades de springboot
https://docs.oracle.com/javaee/6/tutorial/doc/bnbqa.html#:%7E:text=An%20entity%20is%20a%20lightweight,entities%20can%20use%20helper%20classes.
whta is a java entity





[https://mystery.knightlab.com/](https://stackoverflow.com/questions/63414381/what-is-entity-in-spring-jpa#:~:text=An%20entity%20is%20a%20lightweight,entities%20can%20use%20helper%20classes.)

repositorio de springboot
https://zetcode.com/springboot/repository/#:~:text=A%20repository%20is%20a%20mechanism,be%20autodetected%20through%20classpath%20scanning.

working with springboot repositories
https://docs.spring.io/spring-data/data-commons/docs/1.6.1.RELEASE/reference/html/repositories.html
