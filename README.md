# Caffeine MC - a meta-compiler

Select, configure and extend your to-JavaScript compiler, with arbitrary code, on a per file bases from within the file.

### Examples

* myFileName1.caf
```javascript
|javascript

// this is JavaScript
(function(){console.log("Hello from JavaScript!")})()
```

* myFileName2.caf
```coffeescript
|coffee-script

# this is CoffeeScript
do -> console.log "Hello from CoffeeScript!"
```