# WolfBeacon Momentum Integration

Integration with [Momentum (Chrome extension)](https://momentumdash.com/)

## Installation

1. You need [Node.js and NPM (LTS versions)](https://nodejs.org).

2. Clone the repository

3. From the project root, run `npm install`

## Tasks

(From the project root)

- Do `npm start` and `npm run build-dev` on separate terminals to open a browser sync server on port 8888 which can be accessed by `[localhost](http://localhost:8888)`

- `npm run test` will run integration and unit tests. **First, you must run `npm start` and `npm run start-selenium-server` in separate terminals before this command.**

## Testing

All tests use the following:

- Framework: Mocha
- Assertions: Chai

White-box testing will use Karma while black-box testing will use Webdriver.io to connect to a Selenium server.

## Contributing

* Your `master` branch should point to `origin/master`.

* **NEVER EVER WORK ON `master`**. Keep the `master` branch updated with upstream `git pull upstream master`. It's only to be used a reference/starting point.

* In reference to the above point, create a different branch for the issue you are working on off your master branch like `git checkout -b username-work`.

* Whenever you begin work, be sure to `git pull --rebase upstream master`.

* `npm run lint` will run the `standard` linter. Use this before issuing any PRs or pushing any changes.

* When you have completed, `git push origin username-work` and issue a PR to the repository.

* In case you have a PR pending on this branch, `checkout` to your local `master` branch, `checkout` another `work` branch and work there. Needless to say, `git pull --rebase upstream master` is always important.

## Credits

[Brendan Graetz: Front-end Boilerplate](https://github.com/bguiz/front-end-js-testing)