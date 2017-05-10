# A starter project for React/Redux

> A minimalistic React/Redux starter project

To use:

* Copy this repo
* Rename your repo according to the app you're building
    └─ mv boilerplate-react-redux [new project name]
    └─ git remote set-url origin https://github.com/daniel-reason/PROJECT-NAME
* npm
* npm run build

To start the express server, run `npm start`, and go to [http://localhost:3000](http://localhost:3000).

This is the structure of this boilerplate:

```
.
├── client
│   ├── actions
│   │   └── index.js
│   ├── components
│   │   ├── AddWord.jsx
│   │   ├── App.jsx
│   │   ├── Word.jsx
│   │   └── Words.jsx
│   ├── containers
│   │   └── WordsContainer.js
│   ├── reducers
│   │   ├── index.js
│   │   └── words.js
│   └── index.js
├── public
│   ├── index.html
│   └── main.css
├── server
│   ├── index.js
│   └── server.js
├── .gitignore
├── package.json
├── README.md
└── webpack.config.js
```
