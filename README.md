# Vue Test

## Indicaciones
El presente proyecto contiene 1 componente padre y 4 componentes hijo al mismo nivel. El objetivo es construir una aplicación de To Do's (Pendientes) Que cumpla con los siguientes objetivos y/o características.

## Datos de la tarea
Cada tarea debe tener un título, un estado pendiente o realizada, así como una fecha y hora a la que se deben realizar, junto con un entero que marque su prioridad en una escala del 1 al 5.

## Estructura del proyecto
La siguiente estructura de archivos y funciones/métodos debe seguirse. 

### app.vue
Componente padre dónde se debe manejar toda la data.

### doneList.vue
Componente dónde se listan todas las tareas ya realizadas.
1.- Este componente debe tener un método que ordene las tareas por hora y fecha, así como alfabéticamente y por orden de prioridad. De manera ascendiente y descendiente.

### selectedToDo.vue
Componente dónde se muestra la tarea seleccionada.
Este componente debe poder mostrar la tarea seleccionada por el usuario, con la posibilidad de modificar sus datos, eliminarla o marcarla como realizada o pendiente.

### toDoList.vue
Componente dónde se listan todas las tareas pendientes de realizar. 
1.- El punto 1 del doneList.vue también se aplica a este componente. 

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
