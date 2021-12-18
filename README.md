# Node JS Learning

Install Node JS : Download latest Software from -> https://nodejs.org/en/download/
=====================
Aftall installation check the below command for Instalation validation
>node --version <br/>
or <br/>
>node <br/>
------------------------ <br/>
First Node JS Example <br/>
----- <br/>
create a folder using command prompt:  <br>
> mkdir myfirsapp <br>
> cd myfirstapp <br>
> create a file with name index.js <br>
  add the below code  <br>
  ------------------------------------
  <h5>
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
  </h5>
  ------------------------------ <br>
  <h7>
> npm init <br>
[provide the basic info] <br>
package name: (basic-rest-example) <br>
version: (1.0.0)  <br>
description: basic example <br>
entry point: (index.js)  <br>
test command:  <br>
git repository: <br>
keywords: <br>
author: <br>
license: (ISC) <br>
> npm install express --save<br>
> node index.js <br/>
open the URL (http://localhost:3000) in broweser<br>
  </h7>


