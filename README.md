# Prueba de Nivel
> [!IMPORTANT]
> **Fecha:** 18/07/2024
> **Criterio de Aprobación** Debes completar almenos un punto de cada ejercicio y un mínimo de 4 puntos entre los 3 ejercicios para aprobar la prueba.
> **Adicional** Como es una instancia de evaluación, no podrás revisar internet. Sí puedes consultar trabajos que hayas realizado en Sprints anteriores, pero no material ajeno.

## Enunciado

Necesitamos construir la lógica del dominio de una tienda de cafe. En concreto debemos poder crear las entidades y los metodos principales de café que vende la tienda. Todos los café deben tener un tamaño (grande, mediano, pequeño).

### Ejercicio 1

1.1 Crea una clase para cada tipo pedido ("para llevar" o "para consumir en tienda") que herede de una clase base.
1.2 Crea una propiedad con el tipo de pedido ("para llevar" o "para consumir en tienda") dentro de la clase base y asignale un valor en las clases extendidas.

### Ejercicio 2

2.1 Usa una interfaz para que la clase base tenga un método que devuelva el vaso en que se servirá el café segun su tipo de pedido.
2.2 Implementa la funcionalidad de ese método en las clases extendidas para que devuelvan el valor correspondiente. Si es "para llevar", se servirá en "vaso de carton", y si es "para consumir en tienda" se servirá en "taza".

### Ejercicio 3

3.1 Crea un test que compruebe que el metodo de devolver el tipo de vaso donde se sirve el café existe.
3.2 Crea un test que compruebe que el metodo de devolver el tipo de vaso se ejecuta correctamente.
