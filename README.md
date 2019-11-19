### apod-explorer

[![Build Status](https://api.travis-ci.com/mgzwarrior/apod-explorer.svg?branch=master)](https://travis-ci.com/mgzwarrior/apod-explorer)

`apod-explorer` is an application that serves two primary purposes:

- as a GraphQL-backed API, exposing data access to asynchronously download in bulk high-definition APOD photos
- as a data visualization UI that enables exploration of APODs using a chosen date range; it'll dynamically download APODs if it's missing the range

See [nasa4s](https://github.com/brandon-powers/nasa4s) for information on the service that bulk downloads APODs by command, mediated by an AWS SQS queue. This is what backs the API and the UI mentioned above.
