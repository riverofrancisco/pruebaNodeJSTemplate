# Prueba de Nivel
> [!IMPORTANT]
> - **Fecha:** 25/07/2024
> - **Criterio de Aprobación:** Debes completar almenos un punto de cada ejercicio y un mínimo de 4 puntos entre los 3 ejercicios para aprobar la prueba. Tienes 30 minutos para realizar la prueba.
> - **Adicional:** Como es una instancia de evaluación, no podrás revisar internet. Sí puedes consultar trabajos que hayas realizado en Sprints anteriores, pero no material ajeno.

## Enunciado

Necesitamos construir la lógica del dominio de una heladeria. En concreto debemos poder crear las entidades y los metodos principales de los helados que vende la heladeria. Los helados pueden servirse distintos recipientes (`'Cono'` o `'Vaso'`).

### Ejercicio 1

- **1.1)** Crea tres clases que hereden de una clase base para clasificar el tamaño que puede tener cada helado (`'Pequeño'`, `'Mediano'` o `'Grande'`). Presta atención a la estructura que debe cumplir la clase base.
- **1.2)** Crea una propiedad tamaño, que puede ser `'Pequeño'`, `'Mediano'` o `'Grande'`, en la clase base. Asignale un valor en las clases extendidas.

### Ejercicio 2
> En nuestra heladería, los helados pequeños tienen 1 sabor, los medianos 2 sabores y los grandes hasta 3 sabores.

- **2.1)** Define y usa una interfaz para que las clases extendidas tengan un método que devuelva la cantidad de sabores que tendrá el helado según su tamaño.
- **2.2)** Implementa la funcionalidad de ese método en las clases extendidas para que devuelvan el valor correspondiente. Si el tamaño es `'Pequeño'`, devolverá `1`, si es `'Mediano'` devolverá `2` y `3` si es `'Grande'`.

### Ejercicio 3

- **3.1)** Crea un test que compruebe que la propiedad tamaño toma el valor correcto en las clases extendidas.
- **3.2)** Crea un test que compruebe que el metodo de devolver la cantidad de sabores se ejecuta correctamente.
