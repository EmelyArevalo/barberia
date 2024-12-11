
# Proyecto Barbería  

## Descripción y contexto del proyecto  
Este proyecto es un sistema web para la gestión de una barbería. Se desarrolló utilizando PHP puro como lenguaje principal, junto con CSS para el diseño y JavaScript con AJAX para las funcionalidades dinámicas del cliente. La aplicación incluye dos vistas principales:  
1. **Vista de administrador**: Permite gestionar los servicios, horarios, y datos de clientes.  
2. **Vista de cliente**: Ofrece la posibilidad de reservar citas y visualizar servicios.  

El sistema utiliza una base de datos alojada en **phpMyAdmin**, que contiene las tablas necesarias para manejar usuarios, servicios, horarios y reservaciones.  

## Guía de usuario  
El sistema cuenta con una estructura intuitiva para facilitar la interacción de los usuarios:  
- **Vista de administrador**: Accesible con credenciales específicas para gestionar las operaciones de la barbería.  
# USUARIO:configuroweb
# CONTRASEÑA:1234abcd..
- **Vista de cliente**: Diseñada para permitir a los clientes interactuar con los servicios de la barbería.  

Para obtener ayuda sobre el sistema:  
1. Revise los archivos de documentación incluidos en la carpeta `docs/`.  
2. Consulte el archivo `help.txt` para preguntas frecuentes y soluciones comunes.  
3. Si necesita soporte adicional, comuníquese con el equipo de desarrollo a través del correo proporcionado en la sección de autores.  

## Guía de instalación  

### Requisitos del sistema operativo  
- **Sistema operativo**: Windows, macOS, o Linux con soporte para servidores web.  
- **Servidor web**: Apache (parte del paquete XAMPP o LAMP recomendado).  
- **PHP**: Versión 7.4 o superior.  
- **Base de datos**: MySQL (incluido en XAMPP).  

### Instalación de XAMPP  
1. Descargue XAMPP desde su página oficial: [https://www.apachefriends.org/](https://www.apachefriends.org/).  
2. Ejecute el instalador descargado y siga estos pasos:  
   - Seleccione los componentes requeridos: Apache, MySQL, PHP, y phpMyAdmin.  
   - Seleccione el directorio de instalación (recomendado: `C:\xampp\`).  
   - Complete la instalación y abra el panel de control de XAMPP.  
3. Desde el panel de control de XAMPP:  
   - Inicie los servicios **Apache** y **MySQL** presionando los botones "Start".  

### Configuración de phpMyAdmin y creación de cuenta  
1. Abra su navegador y acceda a phpMyAdmin ingresando `http://localhost/phpmyadmin` en la barra de direcciones.  
2. Para crear una nueva cuenta de usuario:  
   - Seleccione la pestaña **Usuarios**.  
   - Haga clic en **Agregar usuario**.  
   - Complete los campos con los siguientes datos:  
     - **Nombre de usuario**: [nombre_usuario]  
     - **Host**: `localhost`  
     - **Contraseña**: [contraseña_segura]  
   - Seleccione la opción **Crear base de datos con el mismo nombre y otorgar todos los privilegios** si desea asociar automáticamente una base de datos.  
   - Haga clic en **Continuar** para guardar los cambios.  

### Subir la base de datos  
1. En phpMyAdmin, seleccione la pestaña **Bases de datos** y cree una nueva base de datos:  
   - Ingrese `barberia` como nombre y seleccione la intercalación `utf8_general_ci`.  
   - Haga clic en **Crear**.  
2. Subir el archivo SQL:   
   -puedes encontrar la base de datos aqui --> 

### Configuración del proyecto  
1. Copie los archivos del proyecto en la carpeta raíz del servidor web (por ejemplo, `C:\xampp\htdocs\barberia`).  

2. Acceda al sitio web desde su navegador utilizando la URL `http://localhost/barberia`.  

## Autores  
- grupo 5 

  

---
## Manual de usuario
si tienes alguna duda sobre el funcionamiento aqui te dejamos el manual de usuario
LINK------------------>
 Explorando nuestra barberia https://drive.google.com/file/d/1LXxHMv-L3TmrFNEVbQPaDeeLJVhzoAlv/view?usp=sharing
 Reserva tu cita en minutos  https://drive.google.com/file/d/1sknkjtplMxZQUoZFiQpuub2qOrpTlFXb/view?usp=sharing 
 conoce nuetra galeria y servicios https://drive.google.com/file/d/1NW16iD2O9mXxOdgA2wC7sNNlPsl6Vmw1/view?usp=sharing 
 

## Preguntas frecuentes 
puedes encontrar las FAQS en este apartado por si tienes alguna pregunta lo puedes encontrar en el archivo llamado
FAQS.html
