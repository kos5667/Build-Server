## Node.js WAS

> **목록**



---

### 1. initialize node.js server

1. package.json 생성

   ```bash
   $ npm init
   This utility will walk you through creating a package.json file.
   It only covers the most common items, and tries to guess sensible defaults.
   
   See `npm help json` for definitive documentation on these fields
   and exactly what they do.
   
   Use `npm install <pkg>` afterwards to install a package and
   save it as a dependency in the package.json file.
   
   # (default)
   package name: ({path}) was
   version: (1.0.0)
   description: build was
   entry point: (index.js)
   test command:
   git repository:
   keywords:
   author:
   license: (ISC)
   About to write to ../package.json:
   
   {
     "name": "was",
     "version": "1.0.0",
     "description": "build was",
     "main": "index.js",
     "scripts": {
       "test": "echo \"Error: no test specified\" && exit 1"
     },
     "author": "",
     "license": "ISC"
   }
   
   Is this OK? (yes)
   ```

2. index.js 생성

   ```javascript
   // index.js
   
   console.log('start node...');
   ```

   



---

#### 2. Inital Nose.js server



> 참조
>
> 

