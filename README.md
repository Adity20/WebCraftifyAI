#  ACES software aid frontend repository

This is the repository for the frontend of the software aids project

## Contributing

First, clone this repo using

```bash
git clone *repo url here (without asterisks)*
```
You'll see the folder structure and file naming standards, please abide by it.
* Create a folder for the page you're working on ```pages``` folder.
* Create ```css```, ```images```, ```js``` folders within the folder you just created. Each page must use different folder and files.
* Shared js, images, css and icons will be stored in the ```common``` folder.
* Below is an example for sign up page
```
 |-- common
    |-- icons
    |-- images
    |-- css
    |-- js

 |-- pages
     |-- signup
         |-- css
         |-- images
         |-- js
```
* Create all JS files in the ```assets/js``` folder

* Images & icons go in ```assets/images``` & ```assets/icons``` folders respectively
* Use lowercase letters for file names
* Use hyphens for naming CSS-classes and IDs, eg ```header-section```. Use readable names.
* Javascript functions/variables use ``` snake_case``` naming convention.
* If you're unsure of how to arrange your code, follow the ```style guides```.
* [Link to JAVASCRIPT style guide](https://github.com/airbnb/javascript).
* [Link to HTML/CSS style guide](https://google.github.io/styleguide/htmlcssguide.html).
* Please go through the style guide at least once!.
* Please remember to write comments so that others can follow.

### IMPORTANT!
* Create a new branch for every feature you add, push and create a pull request to the ```dev``` branch.
* Do not push directly to ```main```, ```dev``` or ```deploy``` branches!
* Use snake_case for branch names.
* Write descriptive commit messages.
* Explain what you did in a few words in your pull request comment.
* Never merge or close a PR by yourself, only one person does handles this to avoid confusion!.
