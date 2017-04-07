# Newsletter Building

## Change to the newsletter work folder
  * Newsletter folder is python virtual environment
  * Using mkdocs to track documentation
  * `workon newsletter` - gets you going


## Process
* Rationale
    * **zurb-foundation** branch follow **zurb foundation** repository
    * **master** branch is stable/production branch
* Process
   1. Create new working branch
      * `git checkout master`
      * `git checkout -b april2017`
   1. Pull all changes from the `zurb foundation` into my `zurb-foundation` branch.
      * `git checkout zurb-foundation`
      * `git pull zurb master`
   1. Pull changes from `zurb-foundation` branch into `april2017` branch
      * `git checkout april2017`
      * `git merge zurb-foundation`
   1. Complete the newsletter and merge back to master
      * `git checkout master`
      * `git merge april2017`
   1. Push all changes to github
      * `git push origin --all`

## Creating/updating the newsletter
1. Create new branch from master
1. Update zurb-foundation branch from zurb
1. Pull changes from zurb-foundation into new work branch
1. Finish the newsletter
1. Send newsletter via MailChimp
1. Merge work branch to master

## Creating newsletter
* Save word document as text to **newsletter/txt** folder
* Run `npm start` to run development server 
* Edit files in source
* Run `npm run zip`
  * Create zip file for MailChimp
* Upload file to [MailChimp](https://mailchimp.com)

## Additional Resources
* **tools/snippets.html** - snippets of code I have previously used.
 
