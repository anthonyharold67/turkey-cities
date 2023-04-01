### Installing

```
npm i turkey-cities
```

or

```
yarn add turkey-cities
```

### Usage
```jsx
import React from "react";
import useCities from "turkey-cities";

const App: React.FC = () => {
  const { cities } = useCities();

  return (
    <div className="App">
      {cities.map(city=> <p key={city.plate}>{city.name}</>)}
    </div>
  );
};

export default App;

```
