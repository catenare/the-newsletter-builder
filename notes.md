# Email formatting using Foundation from Zurb
## [Foundation](http://foundation.zurb.com/emails.html)

## Notes
* [Github Repository](https://github.com/catenare/newsletter-builder)
* Rationale
  * __master__ tracks main Zurb Email Template Repo - [Zurb email template](https://github.com/zurb/foundation-emails-template)
  * __{monthdayyear}__ repo for creating current newsletter.
* Instructions
  1. Checkout __master__ branch. ```git checkout master```
  1. Create branch for newsletter from __master__ branch. ```git checkout -b september072017```
  1. Content for newsletter is in ```src/pages/index.html```
  1. Layout is ```src/layouts/main.html```
* Running the server
  1. ```npm install``` - install all the modules
  1. ```npm start``` - start the server and open the browser
  1. ```npm run zip``` - build the zip files. Zip file was in ```dist/index.zip```
