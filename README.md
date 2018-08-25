# advanced-react
PluralSight. Advanced React.js by Same Buna



yarn init

#eslint 
yarn add --dev eslint

yarn eslint -- --init

Plugin babel-eslint
yarn add --dev eslint-plugin-react babel-eslint

Express and EJS
yarn add express ejs

## Hot deployment
For windows 
yarn add nodemon
For other 
yarn add pm2

"scripts" : {
    "dev" : "nodemon lib/server.js"
}

# Babel
 "babel" : {
    "presets" : ["react", "env", "stage-2"]
  },
  yarn add babel-cli babel-preset-react babel-preset-env babel-preset-stage-2

git tag -a 2.2 -m "Configuring a Full-stack JavaScript Environment: Server Side"