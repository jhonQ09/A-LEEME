# Aplicación de Gestión de Inventarios ![Status badge](https://img.shields.io/badge/status-in%20progress-yellow)

![Alt text](https://www.hubspot.com/hubfs/media/04ejemplosdesoftwaredeinventariorightcontrol1.jpeg)

> ## CONTENIDO
* [Descripcion](https://github.com/jhonQ09/A-LEEME.git)
* [Caracteristicas](https://github.com/jhonQ09/A-LEEME.git)
* [Tecnologías Utilizadas](https://github.com/jhonQ09/A-LEEME.git)
* [Propuestas Arquitecturas](https://github.com/jhonQ09/A-LEEME.git)
* [Estructura de Repositorios y Manejo de Librerias](https://github.com/jhonQ09/A-LEEME.git)
* [Pipelines y flujos Git](https://github.com/jhonQ09/A-LEEME.git)
* [Distribucion de Buckets](https://github.com/jhonQ09/A-LEEME.git)
* [Monitoreo y Reportes](https://github.com/jhonQ09/A-LEEME.git)
* [Planeacion MVP e Incrementos](https://github.com/jhonQ09/A-LEEME.git)
* [Autores y Agradecimientos](https://github.com/jhonQ09/A-LEEME.git)
* [Contribuciones e Historial de Versiones](https://github.com/jhonQ09/A-LEEME.git)
* [FAQs](https://github.com/jhonQ09/A-LEEME.git)
* [Licencia](https://github.com/jhonQ09/A-LEEME.git)

## Descripción
✨ Esta aplicación web está diseñada para una empresa de suministros mercantiles con el objetivo de gestionar sus inventarios de bodega de manera eficiente.

## Características

- Listado actual de inventarios.
- Ingreso de inventario nuevo.
- Salida de inventario.
- Autenticación para prevenir fraudes.

## Tecnologías Utilizadas

### ✨Backend

- **Plataforma**: AWS Lambda
- **Lenguaje**: Node.js (v.20)
- **Funcionalidades**:
  - Acceso a base de datos para persistencia de datos.
  - Medidas de seguridad, incluyendo:
    - Autenticación
    - Autorización
    - Sanitización de datos
    - CORS (Cross-Origin Resource Sharing)

### ✨Frontend

- **Framework**: Angular (v.16)
- **Funcionalidades**:
  - Inicio de sesión
  - Vista de inventario
  - Ingreso/modificación de inventario
  - Manejo de seguridad, incluyendo Guards e Interceptors

## Propuestas Arquitecturas
### 🚀Propuesta AWS Backend
![Alt text](/arquitectura.png)

### 🚀Propuesta AWS Front End
![Alt text](/arquitectura-front.png)

## Estructura de Repositorios, Librerias y Pilelines
### 🚀Nemotecnia y Repositorios Backend
![Alt text](/Pipelines-y-Repositorios-Lambdas.png)
### 🚀Repositorios y Librerias Front
![Alt text](/Estructura-Repositorios-Front.png)
 
 Los repositorios se encuentran alojados en la plataforma github:
 ![Alt text](/Repos-github.png)
 * [Link GitHub](https://github.com/jhonQ09/A-LEEME)

## Distribucion de Buckets
![Alt text](/Distribucion-Bucket-AWS.png)

## Monitoreo y Reportes
![Alt text](/Monitoreo-Inventory.png)

## Planeacion 1er MVP e Incrementos
![Alt text](/Planeacion-primer-MVP.png)
* [Link Miro 1](https://miro.com/app/board/uXjVPDzygzk=/?share_link_id=715078870891)
* [Link Miro 2](https://miro.com/welcomeonboard/WnlxbVRQYm9yTHQ2Mmx1cUt5TGJEOWZVQmR0YmxxQmVZSmJZWmhqU2RDc2ZTUXJ4ZHZUdjBWNlFmc1g5NnhsaHwzNDU4NzY0NTM4NTg1OTUwOTQ1fDI=?share_link_id=328504655295)

## Autores y Agradecimientos
* A los Ingenieros Felipe y Jhon Quevedo.

# FAQs
> Lista de Preguntas y Respuestas
+ ¿Cómo puedo restablecer mi contraseña?

Para restablecer tu contraseña, dirígete a la página de inicio de sesión y haz clic en el enlace "Olvidé mi contraseña". Sigue las instrucciones para recibir un enlace de restablecimiento de contraseña en tu correo electrónico.

+ ¿Qué hago si no puedo iniciar sesión?

Asegúrate de que estás usando las credenciales correctas. Si el problema persiste, verifica si tu cuenta está activada o contacta al soporte técnico para asistencia.

+ ¿Cómo puedo agregar un nuevo artículo al inventario?

Inicia sesión en la aplicación, navega a la sección de "Ingreso de Inventario", y completa el formulario con la información del nuevo artículo. Luego, guarda los cambios para añadir el artículo al inventario.

+ ¿Puedo editar un artículo existente en el inventario?

Sí, puedes editar un artículo existente. Ve a la vista de inventario, selecciona el artículo que deseas modificar, y elige la opción de edición. Realiza los cambios necesarios y guarda la actualización.

+ ¿Cómo se gestiona la seguridad de los datos?

La seguridad de los datos se gestiona mediante autenticación y autorización en el backend, y mediante el uso de Guards e Interceptors en el frontend. Además, los datos son sanitizados para prevenir vulnerabilidades.

+ ¿Dónde puedo reportar un problema con la aplicación?

Puedes reportar problemas o errores abriendo un issue en nuestro repositorio de GitHub o contactando al soporte técnico a través del correo soporte@empresa.com.

+ ¿Cómo se implementan las actualizaciones del sistema?

Las actualizaciones del sistema se implementan mediante despliegues tanto en el backend como en el frontend. Asegúrate de seguir las instrucciones de despliegue para cada componente y verificar que todo funciona correctamente después de aplicar las actualizaciones.

## Contribuciones e Historial de Versiones

Los Pull requests son bienvenidos. Para cambios importantes, abra una HA primero

Asegúrese de actualizar las pruebas según corresponda.


|Versión|Área|Participantes|
|-----------------|--------------|-------------------------------------------|
|1.0.0 |Full Stack| Arq. Felipe -Jhon F. Quevedo|
|Versión Inicial|04/09/2024|