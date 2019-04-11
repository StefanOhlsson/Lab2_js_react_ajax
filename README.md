## Lab 2 - JavaScript
Ni ska skapa en webbapplikation där man kan spara sina favoritböcker. Laborationen ska utföras två och två. Syftet är att träna på DOM-manipulation och AJAX med JavaScript och React.

## Uppgiften
Ni ska göra en webbapplikation som visar en lista med böcker. Till er hjälp har ni ett API, med dokumentation här: https://www.forverkliga.se/JavaScript/api/crud.php

API:et har funktioner som motsvarar SQL insert, select, update och delete. Varje operation returnerar ett svar i JSON-format, som talar om ifall operationen har lyckats eller inte. Efter att ni har fått svar från API:et ska ni tala om för användaren om operationen misslyckades, eller om den lyckades och efter hur många försök.

Sidan ska vara en Single Page App (SPA) dvs inga länkar till andra HTML-filer, utan alla förändringar på sidan ska göras med JavaScript/React.

Ge användaren möjlighet att begära en ny API-nyckel. Ni kan spara den senaste i koden eller med localStorage.

Det ska finnas ett formulär för att lägga till en ny bok.

Existerande böcker ska visas i en lista med titel och författare.

Minst 3 olika komponenter ska användas

Minst 5 olika komponenter ska användas (VG)

Det ska finnas ett formulär för att ändra en bok i listan. (VG)

Det ska finnas en funktion för att ta bort en bok ur listan. (VG)

Den som vill ha en extra utmaning (inte betygsatt) kan implementera ett filter: en textruta där man skriver text; listan med böcker uppdateras så att bara de böcker som matchar texten visas. Görs bäst med higher order functions.



This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

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

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
