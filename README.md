# Node JS Learning

Install Node JS : Download latest Software from -> https://nodejs.org/en/download/
=====================
Aftall installation check the below command for Instalation validation
>node --version
or
>node
------------------------
First Node JS Example
-----
create a folder using command prompt: 
> mkdir myfirsapp
> cd myfirstapp
> create a notepad file index.js
  add the below code 
  ------------------------------------
  const express = require('express') <br>
  const app = express() <br>
  const port = 3000 <br>
<br>
  app.get('/', (req, res) => { <br>
    res.send('Hello World!') <br>
  }) <br>
<br>
  app.listen(port, () => { <br>
    console.log(`Example app listening at http://localhost:${port}`) <br>
  }) <br>
  ------------------------------
> npm init
[provide the basic info]
package name: (basic-rest-example) 
version: (1.0.0) 
description: basic example
entry point: (index.js) 
test command: 
git repository: 
keywords: 
author: 
license: (ISC) 
> npm install express --save
open the URL (http://localhost:3000) in prower


