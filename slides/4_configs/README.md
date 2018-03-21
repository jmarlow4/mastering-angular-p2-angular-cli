# Part 2 - Angular CLI
## 4 - Making Changes in Configurations

Let's actually create some changes

* First let's change the app's prefix

    * in line 20 of .angular-cli.json, change it to "ma"

    * if you'd like to apply it to your root component, use the "find all references in project" (vs-code: ctrl/cmd + shift + F) and look for 'app-root.' Ignore any reference in package-lock.json

    * in line 4 of app.component.ts, change the selector to 'ma-root'

    * in line 12 of src/index.html, change the element to ma-root

    * in line 9 of e2e/app.po.ts, change the css selector to ma-root

* Next we're going to change the styling language

    * in line 57 of .angular-cli.json, change css to scss

    * in line 22 of .angular-cli.json, change the filename to styles.scss

    * rename the src/styles.css file in src to styles.scss

    * rename the src/app/app.component.css file to app.component.scss

    * change the reference to that css file in the src/app/app.component.ts on line 6 to scss
  
* You can also just use the right flags upon first creating a project to achieve the same effect
```
  $ ng new myProj --style scss --prefix ma
```
[View these changes here](https://github.com/jmarlow4/mastering-angular-p2-angular-cli/commit/3647cf6440b68ea4f7442208d0efba3010a69650)
