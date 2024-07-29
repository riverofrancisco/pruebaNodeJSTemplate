# Prueba de Nivel
> [!IMPORTANT]
> - **Fecha:** 29/07/2024
> - **Criterio de Aprobación:** Debes completar almenos un punto de cada ejercicio y un mínimo de 4 puntos entre los 3 ejercicios para aprobar la prueba. Tienes 30 minutos para realizar la prueba.
> - **Adicional:** Como es una instancia de evaluación, no podrás revisar internet. Sí puedes consultar trabajos que hayas realizado en Sprints anteriores, pero no material ajeno.

## Enunciado

Necesitamos construir la lógica del dominio de un restaurante. En concreto debemos poder crear las entidades y los metodos principales de los combos que ofrece el restaurante. Todos los combos tienen un precio base de `15` euros.

### Ejercicio 1

- **1.1)** Crea dos clases que hereden de una clase base para clasificar el tipo de combo (`'Simple'`, `'Completo'`). Presta atención a la estructura que debe cumplir la clase base.
- **1.2)** Crea una propiedad `tipo`, que puede ser `'Simple'` o `'Completo'` en la clase base. Asignale un valor en las clases extendidas.

### Ejercicio 2
> En nuestro restaurant, los combos simples cuestan el precio base, y los combos completos tienen un valor adicional de 7 euros.

- **2.1)** Define y usa una interfaz para que las clases extendidas tengan un método que devuelva el precio del combo según su tipo.
- **2.2)** Implementa la funcionalidad de ese método en las clases extendidas para que devuelvan el valor correspondiente. Si el tipo es `'Simple'`, y si es `'Completo'` devolverá el precio que corresponde.

### Ejercicio 3

- **3.1)** Crea un test que compruebe que la propiedad `tipo` toma el valor correcto en las clases extendidas.
- **3.2)** Crea un test que compruebe que el metodo de devolver la el precio del combo se ejecuta correctamente.
