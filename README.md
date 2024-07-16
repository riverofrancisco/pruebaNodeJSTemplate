# Prueba de Nivel
> [!IMPORTANT]
> - **Fecha:** 18/07/2024
> - **Criterio de Aprobación:** Debes completar almenos un punto de cada ejercicio y un mínimo de 4 puntos entre los 3 ejercicios para aprobar la prueba.
> - **Adicional:** Como es una instancia de evaluación, no podrás revisar internet. Sí puedes consultar trabajos que hayas realizado en Sprints anteriores, pero no material ajeno.

## Enunciado

Necesitamos construir la lógica del dominio de una tienda de ropa. En concreto debemos poder crear las entidades y los metodos principales de la ropa que vende la tienda. Todas las prendas deben tener un tamaño (`'XS'`, `'S'`, `'M'`, `'L'`, `'XL'`).

### Ejercicio 1

- **1.1)** Crea dos clases que hereden de una clase base para clasificar el género que puede tener cada prenda (`'Masculino'` o `'Femenino'`).
- **1.2)** Crea una propiedad con el género (`'Masculino'` o `'Femenino'`) dentro de la clase base y asignale un valor en las clases extendidas.

### Ejercicio 2
> En nuestra tienda, las prendas de mujer van en planta baja y las de hombre en la primera planta.

- **2.1)** Usa una interfaz para que la clase base tenga un método que devuelva la planta en que se ubicará la prenda según su género.
- **2.2)** Implementa la funcionalidad de ese método en las clases extendidas para que devuelvan el valor correspondiente. Si el género es `'Masculino'`, se ubicará en `'primera planta'`, y si es `'Femenino'` se ubicará en `'planta baja'`.

### Ejercicio 3

- **3.1)** Crea un test que compruebe que la propiedad género existe en las clases extendidas.
- **3.2)** Crea un test que compruebe que el metodo de devolver el tipo de vaso se ejecuta correctamente.
