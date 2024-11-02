







Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
scoop install symfony-cli
symfony new e-commerce --webapp
composer require symfony/webpack-encore-bundle 
npm i
composer require symfonycasts/verify-email-bundle
npm install bootstrap @popperjs/core bs-custom-file-input --save-dev
npm install node-sass sass-loader --save-dev
--configuration du fichier webpack.config.js
Decommenter ->  .enableSassLoader()
npm run watch
***dans le dossier e-c
symfony console make:user