## Districts

Google geo feature files for every dirticts with grama niladhari divisions in sri lanks.

## sample program

```
// Load json file in to variable and add as

const fs = require('fs');
const data  = JSON.parse(fs.readFileSync('<district>.json'));

// add to map
map = new google.maps.Map(document.getElementById('map'));
map.data.addGeoJson(data);

```
