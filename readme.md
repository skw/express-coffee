# Express Coffee Template 9 (1.9.0)

This is a Node Express CoffeeScript Stack Template

It comes ready to go with connect-assets that give you the option
to use coffee-script and stylus for the client side.

## Technologies
This is a template that can be used to create nodejs applications using 

- **Engine**: Node v0.10.x
- **Framework**: Express v3.2.x
- **Lang**: CoffeeScript v1.6.x
- **Asset management**: asset-rack v2.2.x
- **Template Language**: Jade v0.30.0
  - configured using consolidate.js v0.9.1
- **CSS Preprocessor**: Stylus v0.32.x 
- **CSS Framework(s)**: 
  - Axis-css v0.0.3
  - Nib v0.9.x
- **Database / Driver**: MongoDB / Mongoose 3.6.x

## Requirements

- [NodeJs](http://nodejs.org)
- [Express](http://expressjs.com)
- [asset-rack](https://github.com/techpines/asset-rack)
- [CoffeeScript](http://coffeescript.org)
- [Jade](http://jade-lang.com/)
- [Consolidate.js](https://github.com/visionmedia/consolidate.js)
- [Stylus](http://learnboost.github.io/stylus/)
- [axis-css](https://github.com/Acquisio/bootstrap-stylus)
- [Nib](http://visionmedia.github.io/nib/)
- [Mocha](http://visionmedia.github.com/mocha/)
- [Mongoose](https://github.com/LearnBoost/mongoose)

These will install with npm, just do 

```
npm install
```

In your project directory.

---

## Install, Build, Run, Test, and Watch

```
# Install nodejs and npm

git clone http://github.com/twilson63/express-coffee.git [project-name]
cd [project-name]
npm install
```

## Install coffee-script, mocha and docco

``` sh
npm install coffee-script -g
npm install mocha -g
npm install docco -g
```

# Run

```
cake dev
```

### Mocha and Request for testing

mocha is an extremely powerful and easy to use testing framework

see [http://visionmedia.github.com/mocha/](http://visionmedia.github.com/mocha/)

    describe 'Sample test', ->
      it 'should be true', ->
        true.should.equal true

to run mocha

    cake test

### Setup to deploy to heroku

    rm -rf .git
    git init
    echo 'node_modules' >> '.gitignore'
    git add .
    git commit -am "first commit"
    heroku create
    git push heroku master
    heroku open


## Thanks to

- [Jeremy Ashkenas](https://github.com/jashkenas) for creating coffee-script
- [TJ Holowaychuk](https://github.com/visionmedia) for creating express
- [Miško Hevery](https://github.com/mhevery) for creating Jasmine-Node
- [TJ Holowaychuk](https://github.com/visionmedia) for creating mocha and should.js

## About

express-coffee is a template or boiler-plate to get started writing 
express web applications in CoffeeScript.  It comes ready to go with base
setup for an Express Web App.  It includes a Cakefile that lets you build, 
spec, and watch your coffeescript as you develop.  You hack in the src folder
and run cake build to build you server files, write your mocha in
your test folder and run cake test or spec to run your test suite.  Create your
jade views in the views folder and put your public assets in the public
folder.  Enjoy your express-coffee 


## License

See LICENSE

## Contribute

pull requests are welcome
