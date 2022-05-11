# Go Bootcamp - Coding challenge

## Instrucciones

Construir una aplicación en Go que consuma 5 productos de cada uno de los siguientes endpoints:

- Café: [https://random-data-api.com/api/coffee/random_coffee?size=5](https://random-data-api.com/api/coffee/random_coffee?size=5)
- Cerveza: [https://random-data-api.com/api/beer/random_beer?size=5](https://random-data-api.com/api/beer/random_beer?size=5)
- Productos varios: [https://fakestoreapi.com/products?limit=5](https://fakestoreapi.com/products?limit=5)

Una vez obtenidos, deberán ser transformados para que cada uno cuente con los siguientes campos y valores:

### Coffee

- **id:** *id* value
- **category**: “coffee”
- **name**: *blend_name* value
- **description**: *notes* value
- **price**: random (5.0, 100.0)
- **origin**: *origin* value
- **variety**: *variety* value

### Beer

- **id:** *id* value
- **category:** “beer”
- **name:** *brand* + *name* values
- **description:** *hop, yeast & malts* values
- **price:** random (5.0, 100.0)
- **style:** *style* values
- **alcohol:** *alcohol* value

### Additional products

- **id:** *id* value
- **category:** *category* value
- **name:** *title* value
- **description:** *description* value
- **price:** *price* value

Estos productos deberán ser consolidados en una lista y almacenados en un archivo local en formato JSON.
