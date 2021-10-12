# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).


### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

### Diagramas:

![image](https://user-images.githubusercontent.com/72415333/137005952-61444721-5528-4903-b55c-00af7726a5ee.png)

En este diagrama podemos ver como se hizo el diseño de nuestra pagina web en modo MOVIL.

![image](https://user-images.githubusercontent.com/72415333/137006052-84a26b98-74f9-459b-b097-ad9b185d8e47.png)

En este diagrama podemos ver como se penso la forma de la pagina web en ordenador.

### Diseño:
Sabiendo que debiamos usar react para la creacion de un "clon" de pinterest, decidimos realizar un diseño que correspondiera a esta directiva.
Por lo tanto decidimos usar 5 componentes:
* Header
* Footer
* HeaderMobil
* PinCard
* PinterestLayout
Al tener todos estos componentes, podemos armar nuestra pagina web, ejemplo, podemos ver que los componentes del movil y ordenador no son los mismos, ya que por medio de un condicional, implementamos los componentes:
![image](https://user-images.githubusercontent.com/72415333/137008215-7f0a4b00-a94f-410e-96c2-abcec3e19ca8.png)

Viendo la logica del responsive, estamos mostrando como se hace para el paso a responsive de nuestra pagina web.

A su vez, aconitunuacion, podemos ver como esta compuesto el componente PinterestLayout, que es el que contiene los PinCards, que a su vez contiene las imagene que mostramos en la pagina web:

![image](https://user-images.githubusercontent.com/72415333/137013308-5459ba6b-b2dc-4bbb-aa18-105c9f5c7012.png)

A continuacion, podemos ver los estilos de PinCard, para ver sus styles y los tres tamaños que manejamos para introducir imagenes en la pagina:
![image](https://user-images.githubusercontent.com/72415333/137013664-e8a350e4-918a-4dec-8d63-344fdeb53103.png)

![image](https://user-images.githubusercontent.com/72415333/137013712-177e6014-1e95-442f-8006-47122b8c0c0d.png)


Una vez visto PinCard, podremos pasar a observar Footer y su composicion:

![image](https://user-images.githubusercontent.com/72415333/137017408-81b6e8a0-28da-4859-9b52-c0e0d73ef23c.png)

adicionalmente, tenemos un wrapper, que es lo que contiene nustros iconos del footer:

![image](https://user-images.githubusercontent.com/72415333/137017506-49e51b56-17b3-407b-81e4-08b84ba380b4.png)

Ahora pasamos al Header(es el header de nuestra version o forma ordenador), el cual tambien cuenta con un wrapper que contiene todos sos elementos como iconos, barra de busqueda y logo:

![image](https://user-images.githubusercontent.com/72415333/137017748-0ad46eec-b1ee-4e0b-93b1-ff5318f2e2bb.png)

![image](https://user-images.githubusercontent.com/72415333/137017781-513aea71-d1e6-4297-bc1e-10fd0b91bdc2.png)

Por ultimo tenemos el HeaderMobile, el cual es el que usamos en nuestra version para celular, que tiene la "misma" composicion del header de ordenador, pero distribuido de diferente forma y sin algunos elementos, como por ejemplo la barra de busqueda:

![image](https://user-images.githubusercontent.com/72415333/137018012-582bf113-1d8a-42ff-91ba-1d2220c42156.png)












