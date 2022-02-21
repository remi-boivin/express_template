# Express cleancode template
### _An express template_

This is a template to be able to create faster express projects.

## Features

- User management

## Tech

The template uses a number of open source projects to work properly:

- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework

## Installation

the template requires:
- nodeJS +17.4.0.
- git flow

## Development

Open your favorite Terminal and run these commands.

First Tab:

```sh
nodejs src/index.js
```

(optional) To test if it's work:

```sh
curl http://localhost:7890/users
```

## Contributing

Want to contribute ? Great!

We use git flow to managage branches.

__To start a feature:__

- git checkout develop
- git flow feature start issueNB_title_of_issue

__When your feature is done:__

- ```yarn test --coverage  --collectCoverageFrom="./app/**"```
- ```git add some_files```
- ```git commit``` and follow [commit conventions](https://www.conventionalcommits.org/en/v1.0.0/)
- ````git flow feature publish issueNB_title_of_issue````
- Create a pull request

If you want more informations feel free to read [CONTRIBUTING.md](./CONTRIBUTING.md) file

*nb: To publish you feature you must have at least 90% test coverage on your feature*

## License

The project is under GNU licence. For more informations please read [LICENCE](./LICENSE) file