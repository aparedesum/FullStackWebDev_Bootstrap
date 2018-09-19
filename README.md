Bootstrap demo :(

Components:
Bootstrap
Jquery
Popper
SASS
Font Awesome
Bootstrap Social
Lite-server
OnChange
ParallelShell


Setup initial env:

npm init
npm install bootstrap@4.0.0 --save
npm install jquery@3.3.1 popper.js@1.12.9 --save
npm install font-awesome@4.7.0 --save
npm install bootstrap-social@5.1.1 --save
npm install lite-server --save-dev
npm install --save-dev node-sass@4.7.2

npm install --save-dev onchange@3.3.0 parallelshell@3.0.2

package.json file:

MAC OS / Linux
"watch:scss": "onchange 'css/*.scss' -- npm run scss",
    
"watch:all": "parallelshell 'npm run watch:scss' 'npm run lite'

Windows
"watch:scss": "onchange \"css/*.scss\" -- npm run scss",
    
"watch:all": "parallelshell \"npm run watch:scss\" \"npm run lite\""

