# What is this?

It's the same as [https://github.com/angular/material2]@angular/material2 but over here we got Multi Column Sorting for `mat-table`.

It's the same as [https://github.com/relair/material2]@relair/material2 but over here we are synched to latest []@angular/material2.

See some discussion about `MatMultiSort` feature in the [Github issue](https://github.com/angular/material2/pull/13538).

# How I use this?

1. Let's say you have your project in your local folder `/code/myproject`
2. Open terminal to `/code`
3. `git clone https://github.com/hughanderson4/material2.git`
3. `cd material2`
4. `yarn`
5. `gulp material:build-release`
6. `cd ../myproject`
7. `rm -r -f node_modules/@angular/material`
8. `yarn add @angular/material2@../material2/dist/releases/material`
9. Now edit `angular.json` in `myproject` and set `preserveSymLinks=true`, since you are referencing local material.  See [StackOverflow post](https://stackoverflow.com/a/53123513/213050).
10. Now you can use the features of `MatMultiSort`, it is documented [here](https://github.com/angular/material2/pull/13538#issuecomment-461852259).