# Bug Reproduction

```
$ node_modules/.bin/babel entry.js
TypeError: Cannot read property 'length' of undefined
    at Buffer._append (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/buffer.js:115:26)
    at Buffer.append (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/buffer.js:81:10)
    at Generator._append (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/printer.js:202:52)
    at Generator.word (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/printer.js:126:10)
    at Generator.Identifier (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/generators/types.js:43:8)
    at /Users/swerner/test-async-babel/node_modules/@babel/generator/lib/printer.js:315:23
    at Buffer.withSource (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/buffer.js:178:28)
    at Generator.withSource (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/printer.js:182:15)
    at Generator.print (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/printer.js:314:10)
    at Generator.printJoin (/Users/swerner/test-async-babel/node_modules/@babel/generator/lib/printer.js:382:12)
```
