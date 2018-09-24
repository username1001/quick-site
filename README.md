# Quick-site 

Quick-site is a shell script which creates a directory `site`, and adds various files/folders for a website setup, including: 
stylesheets/style.css, js/main.js, img, index.html(contains a skeleton for an HTML document). 

## Setting up 
Simply clone the repo, and run `make quick-site`, which will create an executable. To run the executable, type `./quick-site`.
 
Note: When you run the script, it will execute within the directory it's in. In this case, the `quick-site` directory. You may copy the contents of the script, or move it altogether out of the script, or you can edit the script, so that the first line should be as follows: 

```
// Navigate to the directory of your choice.
cd ../
``` 

For example, I write my applications/websites in a directory called `code`, so I may navigate to that directory:

``` 
cd ../code
```
and the site skeleton will be created there. 

After you've executed the script, you'll have the directory `site`, of which you can change the name to be whatever you'd like. 
