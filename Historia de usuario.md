

# SPRINTS Y SEMANAS 


## Sprint 1: Creación de un repositorio en Github  Semana (2)


Tener creado el repositorio de las fuentes en GitHub 

Realizar pull/request con cada cambio al proyecto 

Tener creadas las ramas principales Development, Release, Master 

Dar permisos a todos los integrantes del equipo 

Hacer comentarios sobre cada cambio que se sube al repositorio 

Hacer cambios (todos los integrantes) a las fuentes y verlos en el historial 

Definir contexto del negocio 



## Sprint 2: Creación de pipelines Semana (3)


Modelar mockups 

Crear interfases gráficas de usuario  

Generar comunicación entre las interfases gráficas de usuario  

Entregar informe de retrospectiva  


## Sprint 3: Creación y modelamiento de bases de datos en MongoDB Semana (5) 


Desarrollo de algunas funcionalidades del rol administrador


El modelado de base de datos debe tener todas las entidades (documento), como usuarios, roles, productos, plenamente identificados

Las entidades deben tener definidos los valores de las propiedades

Identificar los comandos sobre MongoDB para poblar datos en las estructuras del proyecto

Identificar los comandos para traer la información almacenada en las estructuras

Deberán realizar algunas de las historias de usuario SOLAMENTE relacionadas con las funcionalidades del rol de administrador.


## Sprint 4: Finalización del proyecto Semana (7)

Se deben desarrollar las historias de usuario pendientes del rol administrador
Todas las historias de usuario del rol cliente
En este sprint se deberá terminar de desarrollar el proyecto y desplegarlo en la nube mediante la herramienta de su elección, además de hacer informe de retrospectiva


# CONTENIDO DEL APLICATIVO


## Módulo de gestión de usuarios
* Gestión de ingreso al sistema de información. El sistema tendrá las interfaces gráficas para el registro e ingreso a la aplicación. Para el registro se deberá ingresar el correo, la identificación, el nombre completo y la contraseña, y quedará registrado en el sistema por defecto con el estado de “Pendiente”. Para la autenticación, el usuario deberá ingresar el correo y la contraseña.

* Gestión de estado de usuarios. El sistema tendrá una interfaz gráfica para que el administrador pueda ver y cambiar el estado de los registrados como administrador, y otros roles (Pendiente/Autorizado/No autorizado). 

* Gestión de perfil. El sistema tendrá una interfaz gráfica para que el usuario, independientemente del rol, pueda actualizar los datos personales que ingresó cuando se registró (Incluyendo la contraseña).

## Módulo de inventario

El sistema tendrá una interfaz gráfica para que el (o los) administrador pueda registrar productos nuevos, listar y ver los detalles de los productos. El (o los) otro rol tendrá la opción que lo direccione a la interfaz de stock disponible del producto.


## Módulo de ventas

Este módulo debe conectar con el módulo de inventario para que se actualicen los saldos de productos en bodega con cada venta. El sistema tendrá una interfaz para que los usuarios del sistema puedan seleccionar los productos a llevar y estos se carguen a un carrito y muestre el valor a pagar. 

## Módulo de pagos

El sistema tendrá una interfaz para que el usuario pueda cargar y simular una pasarela u opción de pago para finalizar la venta. En este punto se debe tener en cuenta el registro de entrega de mercancías a domicilio o recogida en tienda.  





# HISTORIAS DE USUARIOS

## HU_001 
Dada la herramienta en la nube “GitHub” Cuando requiera crear un lugar de almacenamiento de fuentes Entonces construiré un repositorio para almacenar las fuentes 

## HU_002 
Dada un repositorio en GitHub Cuando clone el repositorio en mi equipo loca Entonces crearé una rama/branch 

## HU_003 
Dada una rama/branch basada en la rama principal “main” Cuando tenga la rama/branch en el equipo local Entonces crearé las carpetas de fuentes, basedatos, documentos 

## HU_004 
Dada una rama/branch basada en la rama principal “main” Cuando tenga la rama/branch en el equipo local Entonces adicionaré las fuentes y artefactos generados en el desarrollo a las respectivas carpetas 

## HU_005 
Dada una rama/branch generada en el equipo local Cuando haga cambio y/o adiciones de carpetas, artefactos, fuentes Entonces adicionaré los cambios a la rama/branch de mi equipo local y empujaré los cambios en GitHub 

## HU_006 
Dada que tengo una rama/branch nueva en el repositorio de GitHub Cuando requiera mezclar los cambios hechos con la rama principal “main” Entonces haré un pull request

## HU_007 
Dada las necesidades del proyecto “tienda/emprendimiento” Cuando modele las entidades de base de datos Entonces tendré el modelado de los documentos (colecciones) que se requieren para el desarrollo del proyecto 

## HU_008 
Dada las entidades del proyecto a modelar Cuando defina las propiedades de cada entidad Entonces obtendré la información de cada “documento” 

## HU_009 
Dada el motor de base de datos MongoDB Cuando requiera crear la base de datos Entonces veré la base de datos creada en el sistema

## HU_010 
Dada el modelamiento de base de datos Cuando requiera implementar el diseño Entonces usaré MongoDB como gestor de base de datos para la creación de los documentos 

## HU_011 
Dada la información y los datos del proyecto Cuando requiera poblar la base de datos Entonces usaré los comandos dados para ser ingresar datos en MongoDB 

## HU_012 
Dada la información y los datos del proyecto Cuando requiera consultar información de la base de datos Entonces usaré los comandos dados para ser traer información de la base de datos MongoDB

## HU_013 
Dada las funcionalidades implementadas en el código Cuando requiera validar las funcionalidades Entonces configuraré los Jobs de pruebas unitarias 

## HU_ 014 
Dada las fuentes del proyecto de desarrollo web en GitHub Cuando requiera administrar el ciclo de vida del desarrollo Entonces construiré mediante una herramienta de diseño los mockups necesarios para dar claridad de su comunicación 

## HU_015 
Dados los mockups generados mediante el proceso de diseño Cuando requiera implementar el código de mi frontend Entonces construiré mediante React el esqueleto de mi proyecto para trabajar el frontend

## HU_016 
Dados los componentes del proyecto con React Cuando requiera personalizar el estilo de mi frontend Entonces incluiré una plantilla de estilos y la personalizare de acuerdo a mi proyecto 

## HU_017 

## HU_018
 
## HU_013 
Dada las funcionalidades implementadas en el código Cuando requiera validar las funcionalidades Entonces configuraré los Jobs de pruebas unitarias 

## HU_ 014 
Dada las fuentes del proyecto de desarrollo web en GitHub Cuando requiera administrar el ciclo de vida del desarrollo Entonces construiré mediante una herramienta de diseño los mockups necesarios para dar claridad de su comunicación 

## HU_015 
Dados los mockups generados mediante el proceso de diseño Cuando requiera implementar el código de mi frontend Entonces construiré mediante React el esqueleto de mi proyecto para trabajar el frontend Facultad de Ingeniería Como usuario autorizado Dado que voy a ingresar al sistema Cuando necesite autenticarme en el sistema Entonces podré ingresar mi correo y contraseña para ser validados Como usuario Dado que ingresé al sistema Cuando necesite actualizar la información personal Entonces podré ingresar los datos que deseo actualiza

## HU_019 
Como administrador Dado que ingresé al sistema Cuando requiera ver la lista de los usuarios registrados en la plataforma (tanto autorizados como no autorizados) Entonces podré ver la información de los usuarios registrados en la plataforma 

## HU_020 

## HU_021 
Como administrador Dado que estoy viendo la lista de los usuarios registrados en la plataforma Cuando requiera aceptar un usuario en la plataforma Entonces podré cambiar el estado del usuario Como administrador Dado que ingresé al sistema Cuando requiera ver la lista de proyectos registrados en la plataforma Entonces podré ver la lista de los productos registrados en la plataforma

## HU_022 
Como administrador Dado que estoy viendo la lista de los productos registrados en la plataforma Cuando requiera modificar los datos de un producto Entonces podré actualizar el estado del producto 

## HU_023 

## HU_024 

## HU_016 
Dados los componentes del proyecto con React Cuando requiera personalizar el estilo de mi frontend Entonces incluiré una plantilla de estilos y la personalizare de acuerdo a mi proyecto 

## HU_017 



## HU_013 
Dada las funcionalidades implementadas en el código Cuando requiera validar las funcionalidades Entonces configuraré los Jobs de pruebas unitarias 

## HU_ 014 
Dada las fuentes del proyecto de desarrollo web en GitHub Cuando requiera administrar el ciclo de vida del desarrollo Entonces construiré mediante una herramienta de diseño los mockups necesarios para dar claridad de su comunicación 

## HU_015 
Dados los mockups generados mediante el proceso de diseño Cuando requiera implementar el código de mi frontend Entonces construiré mediante React el esqueleto de mi proyecto para trabajar el frontend Facultad de Ingeniería Como usuario autorizado Dado que voy a ingresar al sistema Cuando necesite autenticarme en el sistema Entonces podré ingresar mi correo y contraseña para ser validados Como usuario Dado que ingresé al sistema Cuando necesite actualizar la información personal Entonces podré ingresar los datos que deseo actualizar 

## HU_019 
Como administrador Dado que ingresé al sistema Cuando requiera ver la lista de los usuarios registrados en la plataforma (tanto autorizados como no autorizados) Entonces podré ver la información de los usuarios registrados en la plataforma 

## HU_020 

## HU_021 
Como administrador Dado que estoy viendo la lista de los usuarios registrados en la plataforma Cuando requiera aceptar un usuario en la plataforma Entonces podré cambiar el estado del usuario Como administrador Dado que ingresé al sistema Cuando requiera ver la lista de proyectos registrados en la plataforma Entonces podré ver la lista de los productos registrados en la plataforma Como administrador Dado que estoy viendo la lista de los productos registrados en la plataforma Cuando requiera ingresar un nuevo producto Entonces podré ingresar todos los datos y stock de un producto Como administrador Dado que ingresé al sistema Cuando requiera actualizar el stock de un producto en plataforma Entonces podré ver la información de los productos registrados en la plataforma y actualizar la cantidad en stock## HU_025 Como usuario Dado que voy a ingresar al sistema Entonces podré ingresar los datos de registro (incluyendo elegir el rol al que aspiro) Cuando necesite registrarme en el sistema 

## HU_026 

## HU_027 
Como usuario Dado que estoy viendo la lista de los productos disponibles en la plataforma Entonces podré agregar el producto a mi carrito de compra Cuando requiera comprar un producto Facultad de Ingeniería Como usuario Dado que mi carrito ya contiene todos los productos que deseo comprar Cuando requiera finalizar mi compra Entonces podré seleccionar si deseo mis productos a omicilio o reclamarlos en la tienda y se actualizará el valor a pagar Como usuario Dado estoy viendo nuevamente productos y no finalice mi compra Cuando requiera reanudar mi compra Entonces podré continuar seleccionando productos para mi carrito Como usuario Dado Que me encuentro en área personal de mi cuenta Cuando requiera repetir una de mis compras anteriores Entonces podré seleccionar mi compra y enviarla nuevamente a mi carrito Como usuario Dado que quiero ingresar a la aplicación mediante un navegador Cuando intente ingresar a la aplicación mediante una URL Entonces podré interactuar con la aplicación web Como usuario Dado que ingresé al sistema Entonces podré ver la lista de los productos disponibles en la plataforma Cuando requiera ver la lista de productos disponibles en la plataforma

## HU_028 
Como usuario Dado que mi carrito ya contiene todos los productos que deseo comprar Cuando requiera finalizar mi compra Entonces podré ver el valor detallado y total de todos mis productos 

## HU_029 


## HU_030 

## HU_025 
Como usuario Dado que voy a ingresar al sistema Entonces podré ingresar los datos de registro (incluyendo elegir el rol al que aspiro) Cuando necesite registrarme en el sistema 

## HU_026 

## HU_027 
Como usuario Dado que estoy viendo la lista de los productos disponibles en la plataforma Entonces podré agregar el producto a mi carrito de compra Cuando requiera comprar un producto Facultad de Ingeniería Como usuario Dado que mi carrito ya contiene todos los productos que deseo comprar Cuando requiera finalizar mi compra Entonces podré seleccionar si deseo mis productos a omicilio o reclamarlos en la tienda y se actualizará el valor a pagar Como usuario Dado estoy viendo nuevamente productos y no finalice mi compra Cuando requiera reanudar mi compra Entonces podré continuar seleccionando productos para mi carrito 

## HU_031 
Como usuario Dado Que me encuentro en área personal de mi cuenta Cuando requiera visualizar mis pedidos anteriores Entonces podré visualizar todos los pedidos que he realizado y finalizado en la tienda        


## HU_032
Como usuario Dado Que me encuentro en área personal de mi cuenta Cuando requiera repetir una de mis compras anteriores Entonces podré seleccionar mi compra y enviarla nuevamente a mi carrito


## HU_033
Como usuario Dado que quiero ingresar a la aplicación mediante un navegador Cuando intente ingresar a la aplicación mediante una URL Entonces podré interactuar con la aplicación web



