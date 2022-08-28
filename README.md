# todos

[![style: very good analysis][very_good_analysis_badge]][very_good_analysis_link]
[![License: MIT][license_badge]][license_link]
[![Powered by Dart Frog](https://img.shields.io/endpoint?url=https://tinyurl.com/dartfrog-badge)](https://dartfrog.vgv.dev)

An example todos app built with dart_frog

How to run?

0. Read the [prerequisites](https://dartfrog.vgv.dev/docs/overview#prerequisites)

1. Clone the repo and cd into it

2. Run `dart pub get` on each package

3. Run `dart_frog dev` from root project

4. Open http://localhost:8080 at your browser (or REST client app if you want)

Usage

0. GET http://localhost:8080/todos to show all todos

1. POST http://localhost:8080/todos and give it a body of `{"title": "Your note here"}` to create new todo

2. GET http://localhost:8080/todos/<id> to read specific todo by id

3. PUT http://localhost:8080/todos/<id> and give it a body of `{"title": "Update note here", "isCompleted": true}` to update specific todo by id

4. DELETE http://localhost:8080/todos/<id> to delete a specific todo by id

[license_badge]: https://img.shields.io/badge/license-MIT-blue.svg
[license_link]: https://opensource.org/licenses/MIT
[very_good_analysis_badge]: https://img.shields.io/badge/style-very_good_analysis-B22C89.svg
[very_good_analysis_link]: https://pub.dev/packages/very_good_analysis