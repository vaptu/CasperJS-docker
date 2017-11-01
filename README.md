## Descrption
CasperJS is a navigation scripting & testing utility for PhantomJS and SlimerJS (still experimental). It eases the process of defining a full navigation scenario and provides useful high-level functions, methods & syntactic sugar for doing common tasks 

 Navigation scripting and testing utility for PhantomJS and SlimerJS http://casperjs.org/
  
docker hub: https://hub.docker.com/r/vaptu/casperjs/

## Casperjs released
*  1.1.4 (latest)


  

## Container Base of node

### Installation / Usage
1. Install the vaptu/casperjs container:
```
docker pull vaptu/casperjs
```

2. Run casperjs
```
docker run --rm vaptu/casperjs:latest casperjs --version
```
```
docker run -v $PWD:/data vaptu/casperjs:latest  casperjs /data/test.js
```
