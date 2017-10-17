# NgcReproduction

To reproduce the issue: 
- clone the repo 
- run `npm i` 
- go to `src` folder and run `../node_modules/.bin/ngc -p tsconfig.app.json`

When compilation is over, go to `dist`

To compare results with ng v4 compiler, run `npm-ng-latest.sh`, this will install angular 4, then build `src` again.
