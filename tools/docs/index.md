# Newsletter Building

## Change to the newsletter work folder
  * Newsletter folder is python virtual environment
  * Using mkdocs to track documentation
  * `workon newsletter` - gets you going


## Process
* Rationale
  * **zurb-foundation** branch follow **zurb foundation** repository
* Updating the default branch
  * Update `master` branch with `{last newsletter}` branch
    * `git checkout master`
    * `git merge feb2017`
  * Pull all changes from the `zurb foundation` branch into my `zurb-foundation` branch.
    * `git checkout zurb-foundation`
    * `git pull {zurb foundation}`
  * Pull changes from `zurb-foundation` branch into `master` branch
    * `git checkout master`
    * `git merge zurb-foundation`
  * Create new branch from `master`
    * `git checkout master`
    * `git checkout -b april2017`

## Creating/updating the newsletter
* Save word document as text to **newsletter/txt** folder
* Run `npm start` to run development server 
