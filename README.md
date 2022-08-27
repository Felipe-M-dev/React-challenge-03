https://react-challenge03.netlify.app/

# Desafío 3 - Base de datos colaboradores

En este desafío validaremos nuestros conocimientos en la renderización dinámica de componentes.

Lee todo el documento antes de comenzar el desarrollo, para asegurarte de tener el máximo de puntaje y enfocar bien los esfuerzos.

## Descripción

Un cliente nos solicita una aplicación que muestre un listado de colaboradores a partir de unos datos entregados, donde adicionalmente se pueda agregar colaboradores nuevos y filtrar la lista de resultados a partir de una barra de búsqueda que filtre en función del nombre del colaborador.

Datos iniciales: ``BaseColaboradores``

```javascript
export const BaseColaboradores = [
  {
    id: "1",
    nombre: "Colaborador 1",
    correo: "colaborador1@colaborador1.com"
  },
  {
    id: "2",
    nombre: "Colaborador 2",
    correo: "colaborador2@colaborador2.com"
  },
  {
    id: "3",
    nombre: "Colaborador 3",
    correo: "colaborador3@colaborador3.com"
  },
]
```

## Material de estudio asociado

  ● Guía 3 - Renderización dinámica de componentes
  ● Guía 2 - Estado de los componentes y eventos (Puede ser útil para el punto 2)

## Requerimientos

1. Cargar los datos base desde un archivo e importarlos en el archivo App.js y mostrarlos (de la forma que fue enseñado en la guía). (3 Puntos)

2. Agregar colaboradores a la lista. (3 Puntos)

Hint: Si para agregar una tarea necesitamos un input y un estado para guardar el input, para agregar un colaborador con nombre y correo se necesitan dos inputs y dos estados del tipo string o un estado del tipo objeto.

3. Crear una búsqueda de colaboradores por nombre. (3 Puntos).

Hint: Puedes utilizar el método .filter() de JavaScript para retornar el nuevo arreglo de colaboradores, a diferencia del borrado, el filter() se debe aplicar sobre el arreglo original en lugar del estado anterior.

4. Darle el estilo a la aplicación utilizando CSS. El estilo aplicado debe ser coherente con la aplicación. (1 Puntos)

😊¡Mucho éxito!

<p align="center">
  <img src="https://github.com/Felipe-M-dev/React-challenge-03/blob/main/01.png?raw=true?raw=true" alt="Imagen 01"><br>
Imagen 1. Resultado de aplicación<br>
Fuente: Desafío Latam
</p>

Consideraciones y recomendaciones |
--- |
● Los estilos de la aplicación quedan a libre elección mediante CSS, Bootstrap, react-bootstrap o algún otro Framework a elección. |
