# ¿Quieres salir?

Este es un simple proyecto HTML que presenta una pregunta con dos opciones "Sí" y "No". Si se elige "No", el elemento se mueve a una posición aleatoria en la ventana. Si se elige "Sí", aparece un mensaje adicional.

## Estructura del archivo HTML

El archivo HTML consiste en una estructura básica con:

- La declaración `<!DOCTYPE html>`.
- El elemento `<html>` con el atributo `lang="en"`.
- La sección `<head>` que incluye metadatos, título y estilos.
- La sección `<body>` que contiene el contenido visible.

## Estilos CSS

Se definen algunos estilos CSS para dar formato al contenido, incluido un fondo de imagen, diseño de contenedor y estilo de opciones.

## JavaScript

Se incluye un script JavaScript que contiene dos funciones:

1. `cambiarPosicion(elemento)`: Esta función toma un elemento como argumento y lo mueve a una posición aleatoria en la ventana.
2. `dijoSi()`: Esta función se llama cuando se hace clic en la opción "Sí", muestra un mensaje adicional.

## Uso

Puedes abrir este archivo HTML en cualquier navegador web para interactuar con él. Al hacer clic en las opciones "No" o "Sí", se activarán las funciones correspondientes.

## Nota

- Asegúrate de tener una imagen de fondo llamada `fondo.jpg` en la misma carpeta que este archivo HTML para que los estilos se apliquen correctamente.
- La opción "No" tiene un comportamiento interactivo donde se mueve a una posición aleatoria en la ventana cada vez que se hace clic en ella.
