# SmartHome information screen

SmartHome is an information screen which displays useful information such as bus times, train line status and other information useful for modern day SmartHome.

## API credits
This application uses the [https://www.transportapi.com/](TransportAPI).

## How to get Bus Stop ID
1. On [https://www.openstreetmap.org/?layers=TD](OpenStreetMap) zoom right in on a bus stop you're interested in
2. Click the bus stop node to reveal its tags on the left
3. Copy the `naptan:AtcoCode` code.

## Environment variables
```
REACT_APP_SECRET=somesecretstring
REACT_APP_TRANSPORT_APP_ID=
REACT_APP_TRANSPORT_API_KEY=
REACT_APP_BUS_STOP_DATA=[{"id": "490000077E", "title": "My closest bus stop"},{"id": "490000077E", "title": "Towards Stratford station"}]
```

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
