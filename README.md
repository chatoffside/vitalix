# Vitalix

## Vitalix is the react-native app that consumes that API that is exposed by satoshi which is a fork of rndflo.io

## Links
https://www.youtube.com/watch?v=NO2DaxhoWHk

https://github.com/Remchi/bookworm-react


//------------------------------------------------------------------------------------------------------------------------------------
## Steps
==> rails new vitalix --api -d mysql -T --no-rdoc --no-ri

//------------------------------------------------------------------------------------------------------------------------------------
==> rails generate model Project title:string desc:string

//------------------------------------------------------------------------------------------------------------------------------------


## In the top-level vitalix folder
==> create-react-app vitalix

//------------------------------------------------------------------------------------------------------------------------------------

==> rails g controller Projects

//------------------------------------------------------------------------------------------------------------------------------------

==> rails s -p 3001



curl -G http://localhost:3001/api/v1/projects

//------------------------------------------------------------------------------------------------------------------------------------

==> npm install webpack -g

==> npm install -g webpack-cli

==> cd vitalix && npm install webpack --save-dev


//------------------------------------------------------------------------------------------------------------------------------------

==> npm install webpack-dev-server --save-dev
//------------------------------------------------------------------------------------------------------------------------------------
https://thinkster.io/tutorials/build-a-real-world-react-redux-application

//------------------------------------------------------------------------------------------------------------------------------------

Inside that directory, you can run several commands:

  yarn start
    Starts the development server.

  yarn build
    Bundles the app into static files for production.

  yarn test
    Starts the test runner.

  yarn eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd vitalix
  yarn start

//------------------------------------------------------------------------------------------------------------------------------------

==> create-react-app vitalix

//------------------------------------------------------------------------------------------------------------------------------------

  yarn add --dev eslint prettier eslint-config-airbnb@^15.0.1 eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y@^5.1.1


# Update node to latest on mac

  ==> node -v
v9.7.1

==> brew update

==> brew upgrade node

==> node -v
v10.9.0

//------------------------------------------------------------------------------------------------------------------------------------
