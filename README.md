![Alt Text](https://i.ibb.co/RYRgghZ/Frame-1.png)

## 👋 ¡Bienvenido! ¿Estás listo para convertirte en un Front End de Esthetiqo?

El componente **Crypto Market List** en React/Next permite visualizar de manera dinámica y actualizada los diferentes mercados de criptomonedas, como Bitcoin (BTC), Ethereum (ETH), Litecoin (LTC), entre otros. Este componente listara los datos de los mercados cripto, mostrando información relevante como el símbolo, nombre, precio actual y cambio en las últimas 24 horas. Con la posibilidad de personalización y mejoras adicionales, este componente ofrece una base sólida para integrar y visualizar datos cripto de forma efectiva en aplicaciones web. 

> 👉 El desafío: crear un componente de visualización responsivo para los datos proporcionados, cumpliendo con las especificaciones de diseño.


### Criterios de aceptación
A continuación encontrarás los requisitos mínimos que necesitamos para dar por completado este desafío 🎉
- [ ] Debe crear una rama a partir de `master` llamada `feature/market-selector`
- [ ] El componente interactivo debe cumplir con los criterios de diseño, que puede encontrar a continuación, este componente incluye una lista de mercados cripto los cuales contiene **_Symbol_**, **_The last Price_**, **_24h Change_**, **_Markertcap_**, **_24h Volume_**

    - [Figma](https://www.figma.com/file/RA8tAkmpGEjrdHLSBBhYbU/Intentx-Perpetuals-V2?node-id=304-22777&mode=dev)

- [ ] El componente interactivo debe listar todos los Markets (Consulte `markets/data.json` como referencia).
- [ ] Debe exitir un `button` que me permita agregar mercados como favorito (Usar el `icon-start-fill` para indicar los que esten marcados como favoritos)
  > 👉 Los mercado favoritos deben ser capaces de persistir, para esto usar el `localstorage` o en su defecto alguna libreria de manejo de estado
- [ ] La lista debe ser capaz de filtrarse por **_Symbol_** usando la barra de busqueda, en caso de que la barra de busqueda este vacia mostrar la lista original sin filtrado
- [ ] La lista debe ser capaz de filtrarse por **_The last Price_** , **_24h Change_**, **_Markertcap_**, **_24h Volume_** donde la fecha hacia abajo indique el orden ascendente y la fecha hacia abajo el orden descendente
- [ ] Los valores de **_The last Price_** deben ser rojos cuando el valor sea menor a 2.00 y verdes para cuando sean mayores a 2.00
- [ ] Los valores de **_24h Change_** deben ser rojos para valores negativos y verde para vaores positivos 3%
- [ ] Los valores de **_Markertcap_**, **_24h Volume_** deben tener formato numérico en Tableau K para unidades de miles, M para millones y B para miles de millones

### Recursos

- En la carpeta `public/tokens` se encuentra los logos de los tokens con extension `.svg`.

### Requisitos de Stack

- React / React Hooks
- Next
- Redux / Zustand
- Tailwind / styled-components
- TypeScript
- Deploy Versel


### Consejos sobre la entrega
---------

¡Uf! Eran muchos requisitos, ¿no? 😬

A continuación se ofrecen algunos consejos para que este desafío sea realmente agradable:
- **Organizacion** Se tomara en cuenta la organizacion y estructura del proyecto
- **Buenas practicas** Verificaremos el uso de buenas practicas Y logica de los componentes
- **Utilice** **React** junto con el framework **Next**
- **Limpia tu codigo**. Archivos inútiles, pruebas vacías, código comentado y todo eso obstaculiza nuestra capacidad de ver su código real. Por lo tanto, si está utilizando CLI, generadores o código repetitivo de cualquier tipo, sea amable y limpie todo lo que no agregue valor al resultado.
- **Valoramos su tiempo**. No hay límite de tiempo para este desafío (bueno, hablando razonablemente, no esperamos que le tome más de 8 horas ) y siempre que nos entrege un código funcional que cumpla con los criterios descritos anteriormente, estaremos contentos. Sin embargo, no lo pienses demasiado, encuentra una manera fácil de lograr un buen resultado y apégate a ella.
- **Nada de copypaste**, por favor. Puedes encontrar cualquier cosa en GitHub y StackOverflow hoy en día, ¿no? Bueno, nosotros también podemos . No lo culparemos si olvidó cómo utilizar la API LocalStorage. Simplemente no copie y pegue grandes fragmentos de código.

### Ve más allá 🚀
---------

Si cree que cubrir los criterios básicos de aceptación no es suficiente para mostrar lo mejor de sus habilidades, no dude en agregar un poco más. Esto no es de ninguna manera obligatorio, pero si hay alguna habilidad adicional valiosa que le gustaría mostrar, adelante. Estas son sólo algunas ideas de cosas que podrías agregar:

- Escribe algunas pruebas. Unitarias, Integración, E2E, cualquier cosa que garantice que su código sea irrompible.
- Implemente algún nivel de accesibilidad para las personas con discapacidad que revisan su código.
- Coloque en containers de docker todo el sitio web y haga que se ejecute sin problemas en cualquier máquina.
- Cree configuraciones para diferentes entornos `.env` y optimice y verifique su código para uso en producción `build`.

> ⚠️El cielo es el límite, pero también lo es tu tiempo. Recuerda que cualquiera de estos es completamente opcional . Queremos que tu código nos sorprenda. Sea razonable y apéguese a lo que pueda lograr en 8 horas como máximo

### ¿Desafío completado? 
---------

Envía un pull request al repositorio y asigne **Sanji** como reviever. La rama `master` debe contener el resultado completo

¡Feliz codificación! 🙌

<img src="https://user-images.githubusercontent.com/5693916/30273942-84252588-96fb-11e7-9420-5516b92cb1f7.gif" width="100">