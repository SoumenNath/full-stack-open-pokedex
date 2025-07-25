# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build

After creading build_step.sh I ran the following on git bash
git update-index --chmod=+x build_step.sh
git commit -am "Make build_step.sh executable"
git push
(aLso changed the file from CRLF To LF just on VSCODE)

Deployed on:
https://full-stack-open-pokedex-clra.onrender.com