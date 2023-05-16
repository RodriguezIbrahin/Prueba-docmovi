<img src="assets/docmovi-logo.png" width="150">
<br/>
<br/>

# Prueba técnica — Trainee developer

## Objetivo

El objetivo de esta prueba técnica es que el candidato muestre sus habilidades con las herramientas que utilizará luego en su trabajo diario en docmovi. Está diseñado para verificar las habilidades de desarrollo y su capacidad para resolver problemas.

Pondremos el foco en obtener un **código simple, bien diseñado y organizado**, así como el cumplimiento de todos los requerimientos solicitados.
<br/>
<br/>

## Requisitos de Stack

Para el desarrollo de la aplicación deberá utilizar:

- Meteor.JS
- React / React Hooks
- Librería de estilos (styled-components, CSS modules, o similar)
- MongoDB
- Manejo de errores
- _(opcional)_ TypeScript
- _(opcional)_ Bootstrap
- _(opcional)_ React hook form
- _(opcional)_ rutlib/lib ...

Importante saber:

- Se pueden utilizar otras librerías que crea conveniente, aunque para estilo se recomienda bootstrap, react-hook-form para el manejo de formularios y rutlib/lib para rut.
- No es obligatorio pero se valora el diseño responsive.
  <br/>
  <br/>

## Desarrollo del proyecto

- Se deberá clonar este repositorio para poder modificarlo y completarlo con la resolución del proyecto.
- Una vez que su código esté listo, suba el código a un repositorio público propio y envíenos el enlace a dicho repositorio para que lo revisaremos.

> Se pueden utilizar herramientas como [meteor create my-app](https://react-tutorial.meteor.com/simple-todos) y similares para inicializar el proyecto.
<br/><br/>

## Prueba técnica

Usando la estructura estandar de un projecto meteor, deberá crear un conjunto de pantallas y componentes React para crear la aplicación solicitada.

Se deberá incluir también `README` con instrucciones de configuración/ejecución y cualquier prueba u otra documentación que haya creado como parte de su solución.

Además, agregue la siguiente información a su archivo `README`:

- ¿Hay alguna mejora que pueda hacer en su envío?
- ¿Qué haría de manera diferente si se le asignara más tiempo?
  <br/>
  <br/>

## Detalles

Necesitará construir las siguientes componentes con React:
<br/>
<br/>

- Un componente creación de medicos.
<br/>

  > Estructura del usuario:
  >
  > - Nombre
  > - Apellido paterno
  > - Apellido materno
  > - Rut
  > - Fecha de nacimiento
  > - Nacionalidad
  > - Domicilio
  > - Región (select)
  > - Comuna (select)
  >
  > Funcionalidad:
  >
  > - Validar rut y otros errores
  > - Comuna, debe estar condicionado a la región seleccionada _(opcional)_
  > - Crear medicos

<br/>
<br/>

- Un componente lista de médicos.
<br/>

  > Funcionalidad:
  >
  > - Borrar médicos
  > - Listar médicos en tiempo real

<br/>
<br/>
Necesitará construir en Mongo:

- Una coleccion acorde.

<br/>
**Importante**

- Los componentes en react deben de estar en una sola view, donde al crear o borrar un médico, este se altera en el componente de listado.

- Adaptando la guia [meteor react-app](https://react-tutorial.meteor.com/simple-todos) puede completar lo requerido sin problema.

- Como empresa, creemos que la comunicación es la clave del éxito. Entonces, si algo no está claro, o si tiene dudas sobre la tarea, consultanos!
  <br/>
  <br/>

> Happy coding!

<img src="https://user-images.githubusercontent.com/5693916/30273942-84252588-96fb-11e7-9420-5516b92cb1f7.gif" width="150">
