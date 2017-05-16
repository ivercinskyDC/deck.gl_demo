This is a minimal standalone version of the 3DHeatmap example
on [deck.gl](http://deck.gl) website.

### Grafico

El grafico muestra la distribucion geografica de los supermercados registrados en la pagina de precios claros

### Usage
- Copy the content of this folder to your project. 

- Install Package
```
npm install
```

- Delete last line in `webpack.config.js`
```
module.exports = require('../webpack.config.local')(module.exports);
```

- Add [Mapbox access token](https://www.mapbox.com/help/define-access-token/) 
by run this command in your terminal.

```
export MAPBOX_ACCESS_TOKEN=<Your_Token>
```

or you can directly add it to `app.js`
```
// Set your mapbox token here
const MAPBOX_TOKEN = <Your_Token>>;
```
- Start the app. 
```
npm start
```

### Data format
Sample data is stored in the `data` folder. To use your own data, checkout
the [documentation of HexagonLayer](../../docs/layers/hexagon-layer.md)
