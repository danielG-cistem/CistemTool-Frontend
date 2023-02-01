# **Generación de Bundles**

En Vue JS puedes generar un bundle o por su traducción, "paquete", de código de la aplicación, con todo nuestro código listo y optimizado para ser ejecutado en un navegador.

Tenemos tres tipos de **bundles**:

- 👉 **Bundle de Desarrollo**: Consiste en generar un paquete con nuestro código, apto para un ambiente de pruebas o desarrollo. Este bundle, suele tener un peso elevado debido a que en desarrollo, los ficheros **NO ESTÁN** optimizados para el navegador.
    
    Para generar este bundle, aplique el siguiente comando:
    
    ```jsx
    npm run dev
    ```
    
- 👉 **Bundle de Producción**: Consiste en generar un paquete con nuestro código, apto para un ambiente de producción. Se suele generar este bundle cuando ya es la versión final a entregar. Este tiene un peso ligero debido que los ficheros **SI ESTÁN** optimizados (minifícado, ofuscado y con un hash en los nombres de los ficheros) para el navegador.
    
    Para generar este bundle, aplique el siguiente comando:
    
    ```jsx
    npm run build
    ```

- 👉 **Bundle de Prueba para Producción**: Este bundle es diferente y especifíco. Consiste en ejecutar el bundle generado por el **"npm run build"**, que es la versión de nuestra aplicación para producción.
    
    Sonará extraño, pero es como “El ambiente de desarrollo de producción”. 😅
    
    En ocasiones, se recomienda ejecutar este comando ANTES de liberar la aplicación a producción. La razón, es para asegurarnos que todo salga bien, pues no siempre la versión de desarrollo y producción mostrarán el mismo contenido.
    
    Para generar este bundle, aplique el siguiente comando:
    
    ```jsx
    npm run preview
    ```

## 🚀 **Bundle Adicional**

Este bundle, es una variante del **Bundle de Desarrollo**, pues genera precisamente lo mismo que un ambiente de desarrollo. 

Su proposito, es el de exponer la aplicación via Internet, para que se pueda acceder, desde otros equipos, como por ejemplo, otras computadoras o dispositivos móviles. En otras palabras, el localhost, lo hace público por medio de la IP local y otras personas pueden accerder a el.

```jsx
npm run dev-network
```
    
La única observación a tener en cuenta, es que, para ingresar a una aplicación expuesta con este comando, el usuario que quiera ingresar, tiene que estar conectado a la misma red wifi que el dispositivo local que esta exponiendo la aplicación. De otro modo, no podrá ingresar.

> **Nota**: El nombre de los scrips de ejecución, son los que están por defecto en la aplicación. Dicho esto, son libres de renombrarlos a como mejor prefieran o incluso, pueden agregar nuevos scripts.

---
📌 [**Convención de Commits**](./CONVENTIONAL_COMMITS.md) 

📌 [**Esquema de Versionamiento**](./VERSIONING_SCHEME.MD)

© 2015 Cistem Innovación ® | Casa de Software. All Rights Reserved. Soluciones de Cistem Innovación ® Casa de Software.