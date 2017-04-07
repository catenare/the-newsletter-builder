# Setup

## Project Config
* Using [Zurb Foundation for Emails](http://foundation.zurb.com/emails.html) as the template
* Newsletter is sent via [Mailchimp](https://mailchimp.com).
* Documentation is in **tools\\**
  *  Using Python virtual environment (`workon newsletter`)
  * [MkDocs](http://www.mkdocs.org) for documentation.

## Git Branches
* *master* - tracking the zurb foundation master branch
* *default* - merge changes from master to this branch. Also changes from the latest newsletter.
* *april2017* - current newsletter being worked on.

## Setting up project
1. `git clone https://github.com/catenare/newsletter-builder newsletter`
1. `npm install` - install node modules
1. `mkvirtualenv -a . newsletter` - setup python virtual environment
1. `pip install -r requirements.txt` - install python modules for doing the documentaiton
1. `npm start` - start the development server
