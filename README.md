# persistence.js

This is just a helper javascript module to allow JSON objects to be stored on the localStorage object.

Coming soon:
- Cookies failover
- Allow to choose between localStorage and sessionStorage

## Usage

To save a JSON object:

`var johnDoe = { name: 'John', lastName: 'Doe' }`

`LocalStoragePersistence.saveJsonObject('userData-johnDoe', johnDoe)`

To retrieve a JSON object:

`var johnDoe = LocalStoragePersistence.loadJsonObject('userData-johnDoe')`
