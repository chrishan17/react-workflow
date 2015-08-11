# React Workflow

## Features
* Compilation with webpack
* React and es6
* Stylesheets can be CSS, LESS
* Embedded resources like images or fonts use DataUrls if appropriate
* Development
  * Development server
  * Use React hot reloader
* Production
  * Minimized CSS and JavaScript
* Separated webpack config file for dev and prod
* Flux files structure
* React Bootstrap
* Use `html-webpack-plugin`, https://github.com/ampedandwired/html-webpack-plugin, generate the index.html automatically

## Directory Layout

```
.
├── /build/                     # The folder for compiled output
├── /dist/                      # The folder for distributed files
├── /node_modules/              # 3rd-party libraries and utilities
├── /src/                       # The source code of the application
│   ├── /actions/               # Action creators that allow to trigger a dispatch to stores
│   ├── /components/            # React components
│   ├── /constants/             # Constants (action types etc.)
│   ├── /dispatcher/            # Flux dispatcher
│   ├── /stores/                # Stores contain the application state and logic
│   └── /main.js                # Client-side startup script
│── package.json                # The list of 3rd party libraries and utilities
│── webpack.config.js           # Webpack configuration for bundling and optimization
└── webpack.prod.config.js      # Webpack configuration for production

```

## Install
`npm install`

## Dev
`npm run dev`

## Production
`npm run deploy`

## References
1. React-webpack-cookbook, https://christianalfoni.github.io/react-webpack-cookbook/index.html
2. html-webpack-plugin, https://github.com/ampedandwired/html-webpack-plugin
3. React-hot-loader, http://gaearon.github.io/react-hot-loader/getstarted/
4. React-bootstrap Getting Started, http://react-bootstrap.github.io/getting-started.html
