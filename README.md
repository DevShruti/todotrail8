### Angular 12 ng new myapp gives error The Schematic workflow failed

##### In my case i've tried everything with npm and no way out.

##### But with yarn worked with no worries!

##### I'm a windows user but you can find how to install in other OS in yarn website!

##### 1st - i downloaded yarn from website

###### 2nd - installed the global package with vs terminal: yarn global add @angular/cli

###### 3rd - still in vs terminal set: ng config -g cli.packageManager yarn

###### 4th - i created my app: ng new myapp

###### 5th - so you know te rest ...

yarn global add angular-cli-ghpages
ng build --prod --base-href="https://github.com/shruti1234627/todotrail8"
ngh
