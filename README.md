"# GIT-COMMANDS-PROCEDURES" 

Steps to follow in creating package.json, tsconfig.json, installation of node module and index.ts file.
<br>
1- create a folder in which you want to work e.g : simple-calculator, 45 exercises, number-guessing-game
<br>
2- open that folder in VS code
<br>
3-Run npm init -y (to create package.json and follow the steps add "type": "module", below the line "main": "index.js")
<br>
4-Run tsc --init (to create tsconfig.json )(make channges in "target": ES2022, NodeNext, NodeNext)
<br>
5- npm i @types/nodes
<br>
6- npm i inquirer (to install node_modules)
<br>
7- create index.ts (to write your code)
<br>
8-Run npm i --save-dev @types/inquirer
<br>

TO PUSH ON GITHUB
<br>
Create a new repository on the command line
<br>
echo "# number-guess-game" >> README.md
<br>
git init
<br>
git add README.md
<br>
git commit -m "first commit" or any message you want
<br>
git branch -M main
<br>
git branch : to check branch
<br>
git remote - v : to verify remote
<br>
git remote add origin https://github.com/Mirza096/number-guess-game.git
<br>
git push -u origin main
