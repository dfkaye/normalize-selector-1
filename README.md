# Normalize-Selector

Normalize CSS selectors.

Examples:

* `#foo>.bar` -> `#foo > .bar`
* ` 	#foo 	 > 	 .bar 	 ` -> `#foo > .bar`
* `foo[ a = 'b' ]` -> `foo[a='b']`

# tests

run mocha tests on node.js with 

    npm test
    
or

    node ./test/mocha/node-suite.js
    
# rawgit

view the browser suite directly on 
[rawgit](https://rawgit.com/getify/normalize-selector/master/test/mocha/browser-suite.html)

## License

The code and all the documentation are released under the MIT license.

http://getify.mit-license.org/
