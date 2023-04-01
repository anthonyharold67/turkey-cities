### Installing

```
npm i turkey-cities-towns
```

or

```
yarn add turkey-cities-towns
```

### Usage
```jsx
import React from "react";
import useCities from "turkey-cities-towns";

const App = () => {
  const { cities } = useCities();

  return (
    <div className="App">
      {cities.map(city=> <p key={city.plate}>{city.name}</p>)}
    </div>
  );
};

export default App;

```
