## Opis projektu
**Oddam w dobre ręce**.
Celem projektu jest stworzenie miejsca, w którym każdy będzie mógł oddać niepotrzebne rzeczy zaufanym instytucjom.

Projekt będzie **stroną internetową** z prostym formularzem, który ułatwi użytkownikom oddanie rzeczy.

## Skąd pomysł na projekt
-  Użytkownik ma w domu rzeczy, których chce się pozbyć, ale nie wie jak.
- Jest wiele dostępnych rozwiązań, ale wiele z nich wymaga dodatkowego wysiłku lub nie ma do nich zaufania. W zweryfikowane miejsca trzeba pojechać, a nie ma na to czasu/ nie ma jak tam pojechać, a kontenery pod domem lub lokalne zbiórki są niezweryfikowane i nie wiadomo czy te rzeczy faktycznie trafią do potrzebujących.

## Funkcje
1. Widok *Home* - strony głównej wraz z:
  - sekcją "Komu pomagamy" z możliwością przechodzenia pomiędzy grupami i paginacją
  - formularzem kontaktowym z walidacją i wysyłką
2. Widok *Logowania*, *Rejestracji*, *Wylogowania* wraz z Routingiem
3. Ścieżka `/oddaj-rzeczy` wraz z pełni działającym formularzem, podzielonym na odpowiednie kroki według projektu.
4. Zapis akcji formularza do Firebase lub `json-server`.
5. Logowanie i rejestracja użytkownika + wylogowanie [Firebase](https://www.robinwieruch.de/complete-firebase-authentication-react-tutorial/).
6. Możliwość przejścia do *Formularza "Oddaj rzeczy"* tylko po zalogowaniu lub zarejestrowaniu.

## Narzędzia pracy
### React 

- React (https://reactjs.org/)
- create-react-app (https://github.com/facebook/create-react-app ) 

### React Router
Do szybkiego i prostego tworzenia routingu naszej aplikacji, wykorzystałem bibliotekę `react-router-dom`.

- https://www.npmjs.com/package/react-router-dom


### React Scroll
Przewijanie Landing Page do odpowiednich sekcji, ułatwi nam biblioteka `react-scroll`.

- https://www.npmjs.com/package/react-scroll

### Sass
Projekt oparty o Sass, doinstalowana paczka `node-sass` aby móc korzystać z tego preprocesora.

## FONTY
- `Open Sans ` - https://fonts.google.com/specimen/Open+Sans
- `Merriweather` - https://fonts.google.com/specimen/Merriweather

## Kolory
- `#F0F1F1`
- `#5E5322`
- `#FAD648`
- `#737373`
- `#3C3C3C`


######

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts
In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
