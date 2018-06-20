# A React Template

## Inspiration And Source

When I use Vue, [webpack](https://github.com/vuejs-templates/webpack) is a good template for develop Vue. So this project is a template for React. There are too much templates in open source community, why I try new one? I just want to how to build a project from nothing.

## reference

* [vue-templates/wepback](https://github.com/vuejs-templates/webpack)
* [create-react-app](https://github.com/facebook/create-react-app)

## Usage

Do this command:

```bash
# install dependences
$ npm install

# dev run
$ npm run dev

# production run
$ npm run build
```

## Devolopement Process

### Create Base Files

New some base files, so your directory will like this:

```
├── build
│   ├── build.js
│   ├── webpack.base.conf.js
│   ├── webpack.dev.conf.js
│   └── webpack.prod.conf.js
├── config
│   ├── dev.env.js
│   ├── index.js
│   └── prod.env.js
├── index.html
├── package.json
└── src
    ├── common
    ├── components
    ├── containers
    │   └── Demo
    │       ├── actionTypes.js
    │       ├── actions.js
    │       ├── index.css
    │       ├── index.js
    │       └── reducer.js
    ├── index.js
    ├── reducers.js
    ├── routes.js
    └── utils
```

### Install webpack

```bash
npm install --save-dev webpack webpack-dev-server
```

### Install babel

```bash
npm install --save-dev babel-core babel-loader babel-preset-es2015 babel-preset-react babel-preset-stage-0
```
