[//]: #@corifeus-header


[![Build Status](https://travis-ci.org/patrikx3/ng2-compile-html.svg?branch=master)](https://travis-ci.org/patrikx3/ng2-compile-html)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/patrikx3/ng2-compile-html/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/patrikx3/ng2-compile-html/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/patrikx3/ng2-compile-html/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/patrikx3/ng2-compile-html/?branch=master)  [![Trello](https://img.shields.io/badge/Trello-p3x-026aa7.svg)](https://trello.com/b/gqKHzZGy/p3x)


[//]: #corifeus-header:end


# ng2-compile-html

Angular 2 Service/Attribute to compile an HTML into a component

It is only using ```TypeScript``` right now. It can be built though.

##Install
  
```bash
npm install p3x-ng2-compile-html
```

## Dev environment end test
   
```bash
git clone https://github.com/patrikx3/ng2-compile-html.git
cd ng2-compile-html
npm install
node_modules/.bin/webdriver-manager update
grunt run
```

[http://localhost:8080](http://localhost:8080)

##Usage

###HTML
  
```html
 <div #container></div>
 <div [p3x-compile-html]="data2" [p3x-compile-html-ref]="ref" [p3x-compile-html-imports]="importsLikeMaterialEtc"></div>
```

###TypeScript
Check out the example, here [test/angular2/app/Page.ts](test/angular2-webpack/app/Page.ts).

###Info
Angular 2 tries to camelCase all attributes, for me it is still HTML, so my selectors always ```kebab-case```.



[//]: #@corifeus-footer

[by Patrik Laszlo](http://patrikx3.tk)

[//]: #@corifeus-footer:end