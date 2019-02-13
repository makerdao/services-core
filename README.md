# @makerdao/services-core

A dependency injection framework extracted from [dai.js](https://github.com/makerdao/dai.js). 

### Usage

TODO: finish this example.

```js
class MyService extends PrivateService {
  constructor(name = 'serviceRoleName') {
    super(name, dependencyRoleNames);
  }

  initialize(settings) {
    // initialize() for all its dependencies will run first
  }

  connect() {
    // connect() for all its dependencies will run first
  }

  authenticate() {
    // authenticate() for all its dependencies will run first
  }
}
```
