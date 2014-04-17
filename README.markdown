# Riemann monitors distributed systems on OSv

* Riemann
Riemann aggregates events from your servers and applications with a powerful stream processing language.
Find out more at [http://riemann.io](http://riemann.io)

* OSv
OSv is a new operating system for the cloud
Find out more at [http://osv.io](http://osv.io)

* Capstan
Capstan is a tool for building and running your application on OSv
Find out more at [http://osv.io/capstan/](http://osv.io/capstan/)

## Prerequisites
You will need the following installed
* [Capstan](https://github.com/cloudius-systems/capstan)
* [lein](https://github.com/technomancy/leiningen)

## Usage

* running the server
```
capstan run -f 5555:5555 -f 5556:5556
```

## Test locally
* prerequisites
```
gem install riemann-client riemann-tools riemann-dash
```

* running a data generator 
```
riemann-health
```
* running a Riemann GUI 
```
riemann-dash
```

## License
Capstan is distributed under the 3-clause BSD license
