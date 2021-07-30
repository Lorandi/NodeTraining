
# NODE TRAINING

This repository was created as a training for Nodejs by Alura.



## How to start it
You will need Nodejs installed on your machine. If is necessary, you can download it here: https://nodejs.dev/
After cloning the repository from GitHub is necessary to install the project's dependencies , through the terminal with the command 
```
npm install
```

and then

```
npm start
```

the terminal should show

```
server at port 3000
``` 

### How to run the code
`http://localhost:3000/livros`

or

`http://localhost:3000/livros/form`


## Main technical decisions
For this code I use Nodejs, Express, Nodemon, Jest, ESLint, Sqlite3 and Marko. I tried to keep the code simple, organized and clean to be easier to read and mantain.

## Comments about project
TODO


## How to test 
To check out if the code is working properly, you need to run Jest
```
npm run test
```
To learn more about Jest https://jestjs.io/

## How to find and fix problems
ESLint statically analyzes the code to quickly find problems.
Go to the folder you want to analize and run ESLint.
```
npm run eslint
```  
and to fix the problems
```
npm run eslint:fix
```
To learn more about ESLint https://eslint.org/
