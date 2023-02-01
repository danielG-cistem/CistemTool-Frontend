# **Convención de Commits**

A continuación muestro las practicas o convenciones utilizadas para la descripción de los commits de este proyecto. Si tienes la intención de hacer aportes al proyecto, procura leer estas convenciones y seguirlas como tal.

De esta forma, mantendremos la organización y legibilidad de commits en este repositiorio.

## **Estructura**

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```
Explicación de estructura:

- **```<type>:```** Prefijo que indica el tipo de solución implementado para el commit.

- **```<scope>:```** Opcional. Indica el ambito o módulo sobre el que se esta implementando la solución.

- **```<description>:```** Indica una descripción breve sobre la solución.

- **```[optional body]:```** Opcional. Indica información más detallada sobre la solución.

- **```[optional footer(s)]:```** Opcional. Si existe un cambio que afecta a la lógica del proyecto, es requerido que se coloque en el pie de la confirmación dicha advertencia en lo que se soluciona el problema.

## **Prefijos para Soluciones**

- **feat:** Utilice "feat", cuando se esta confirmando una nueva característica en el proyecto, es decir, algo que no se ha creado antes ("feat", proviene de "feature").

- **fix:** Utilice "fix", cuando necesite indicar la corrección de una falla (bug) dentro del proyecto.

- **docs:** Utilice "docs", cuando la solución sea para determinar cambios en la documentación del proyecto.

- **style:** Utilice "style", cuando la solución sea para indicar cambios únicamente sobre el estilo de interfaz del proyecto. Si la solución involucra "lógica + estilos", consideré mejor registrar el commit como un "feat" o "refactor" según parezca.

- **refactor:** Utilice "refactor", cuando necesite indicar modificaciones y cambios en pro de optimizar y mejorar el diseño y/o arquitectura de la aplicación.

- **test:** Utilice "test", cuando necesite indicar cambios o creación de pruebas en el proyecto (unitarias, integración, funcionales, aceptación, etc).

- **chore:** Utilice "chore", cuando necesite indicar cambios o creación de archivos que no afecten a las funcionalidades programáticas principales del sistema.

> NOTA:
> 
> Los prefijos aquí vistos son generales en si. Eres libre de asignar y crear tus propios prefijos.
> 
> La intención principal de las convenciones, es mantener un orden al momento de crear commits.

## **Referencias**

Las convenciones que aquí se describen, son basadas del sitio **[Conventional Commits](https://www.conventionalcommits.org/es/v1.0.0/)**.

---
📌 [**Inicio**](../README.md)

📌 [**Generación de Bundles**](./GENERATE_BUNDLES.md)

© 2015 Cistem Innovación ® | Casa de Software. All Rights Reserved. Soluciones de Cistem Innovación ® Casa de Software.