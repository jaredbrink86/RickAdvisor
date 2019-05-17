# RickAdvisor - About Microservice

This is a full stack web application that was built using service-oriented architecture. It was designed to mirror the view and functionality of the popular hotel booking website TripAdvisor. This component is the 'About' section of a hotel page, and displays a snapshot of hotel features.

# Live Demo

![](About_Microservice.gif)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

From within the root directory:

```sh
npm install -g webpack
npm install
```

## Running the tests

To run individual test with Jest:

```
npm run test
```

To run continuous test with Jest:

```
npm run test:watch
```

To run code coverage tests with Jest:

```
npm run test:coverage
```

## Deployment

Our deployment process consisted of using Docker to containerize our web application, which we uploaded to Amazon's ECR registry service. We used our Docker images to spin up four instances of our application using AWS's EC2/ECS horizontal scaling architecture.

## Built With

- [React.js](https://reactjs.org) - Front-end framework used
- [Node.js](https://nodejs.org/en/) - Server-side solution
- [Express.js](https://expressjs.com/) - Node.js framework used
- [MongoDB](https://www.mongodb.com/) - Data persistence
- [Mongoose](https://mongoosejs.com/) - ORM

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests.

## Related Projects

- https://github.com/rickadviser/gabe-reviews-service
- https://github.com/rickadviser/Jared-About-Service
- https://github.com/rickadviser/RickMorrisonService
- https://github.com/rickadviser/Pete_Location

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
