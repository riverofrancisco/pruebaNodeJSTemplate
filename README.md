# Enunciado Prueba de Nivel

### 09/07/2024

Necesitamos construir la lógica del dominio de una aplicación de streaming. En concreto debemos poder crear las entidades y los metodos principales de los usuarios de esta aplicación. Todos los usuarios deben tener un nombre de usuario.

## Nivel 1

1. Crea una clase para cada tipo de usuario (premium o standard) que herede de una clase base.

2. Crea una propiedad con el tipo de suscripción (premium o standard) dentro de la clase base y asignale un valor en las clases extendidas.

## Nivel 2

3. Usa una interfaz para que la clase base tenga un método que devuelva el medio de pago de cada suscripción segun su tipo. Si es premium, el medio de pago será "Credit Card", y si es standard devolverá "Free".

## Nivel 3

4. Crea un test que compruebe que el metodo de obtener el medio de pago existe y se ejecuta correctamente.
