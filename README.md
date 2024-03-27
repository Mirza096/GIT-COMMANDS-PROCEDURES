"# GIT-COMMANDS-PROCEDURES" 

Steps to follow in creating package.json, tsconfig.json, installation of node module and index.ts file.

1- create a folder in which you want to work e.g : simple-calculator, 45 exercises, number-guessing-game
2- open that folder in VS code
3-Run npm init (to create package.json and follow the steps add "type": "module", below the line "main": "index.js")
4-Run tsc --init (to create tsconfig.json )(make channges in "target": ES2022, NodeNext, NodeNext)
5- npm i inquirer (to install node_modules)
6- create index.ts (to write your code)
7-Run npm i --save-dev @types/inquirer

TO PUSH ON GITHUB

Create a new repository on the command line

echo "# number-guess-game" >> README.md
git init
git add README.md
git commit -m "first commit" or any message you want
git branch -M main
git remote add origin https://github.com/Mirza096/number-guess-game.git
git push -u origin main