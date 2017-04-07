# Newsletter Building

## Change to the newsletter work folder
  * Newsletter folder is python virtual environment
  * Using mkdocs to track documentation
  * `workon newsletter` - gets you going


## Process
* Updating the default branch
  * Update `default` branch with `{last newsletter}` branch
    * `git checkout default`
    * `git pull feb2017`
  * Pull all changes from the `zurb foundation` branch into my `master` branch.
    * `git checkout master`
    * `git pull {zurb foundation}`
  * Pull changes from `master` branch into `default` branch
    * `git checkout default`
    * `git pull master`
  * Create new branch from `default`
    * `git checkout default`
    * `git checkout -b april2017`

## Creating/updating the newsletter
* Save word document as text to **newsletter/txt** folder
* Run `npm start` to run development server 
