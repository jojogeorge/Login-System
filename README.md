# Login-System
Login app implemented with Node, Passport

Application with login system 
implementted with node


npm install express ejs
npm install --save-dev nodemon dotenv

.gitignore
.env

server.js

npm run devStart

###################################################
const express = require('express')

const app = express();

app.set('view-engine', 'ejs')

app.get('/',(req,res) =>{
    res.render('index.ejs',{name: 'jojo'});  
})


app.listen(5000);

########################################################

npm install passport passport-local express-session express-flash
npm install bcryptjs

npm install method-override
