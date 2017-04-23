# Jobtech Developer
>This site is a collection of all APIs, free of usage, from the Swedish Public Employment Service, Arbetsförmedlingen.

## Install
Make sure you have Node.js and npm installed.

```bash
$ git clone https://github.com/simon-johansson/jobtech-developer.git && cd jobtech-developer
$ npm install
```

## Development
To watch for file changes and compile as you go:
```bash
$ npm run watch
```
This will compile the pug and scss files and put them in the `dist/` folder.

## Deployment
```bash
$ npm run compile
```
This will build and compile the pug and scss files and put them in the `dist/` folder. It will also make a copy of the `images/` folder and place the copy in the `dist/` folder as well as copy the favicon.
