Initially created for better.vote but forked at an early boilerplate stage for general use. Based off of https://github.com/mars/heroku-cra-node, but refactored to use top level folder instead of nested structure. Sets up heroku to work slightly differently and adds buildpack type info.

Instructions are generally the same as initial instructions.md except no need to cd down into folders twice. NPM Install and start server at root folder then cd once into react-ui and follow instructions.

### Deploy to HEROKU:

```
//root folder no need to run build inside react-ui. package.json script will auto do it on heroku server.

heroku create
git push heroku master

```

Other instructions I believe are the same.
