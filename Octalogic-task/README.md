
localhost:3000/vehicles - get all the vehicles
localhost:3000/wheels-options - returns an array containing wheel options [4,2]
localhost:3000/wheels/:wheels - returns types of vehicle based on wheels number (:wheels)
localhost:3000/type/:type - returns different car models based on the type (:type)

localhost:3000/bookings (GET)- shows all the bookings
loclahost:3000/bookings (POST) - creates a new booking
localhost:3000/bookings/:id (PUT) - changes a booking according to id
localhost:3000/bookings/:id (DELETE) - deletes a booking of give id
```

## Installation

```bash
$ npm install
```



## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## License

Nest is [MIT licensed](LICENSE).
