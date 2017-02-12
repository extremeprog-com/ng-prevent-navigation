# ng-prevent-navigation
Angular directive for prevent navigation out of the page.

## Usage

```javascript
var app = angular.module('myApp', ['preventNavigation']);
```

```html
<div ng-prevent-navigation="vm.pageShouldBeReloaded"
     ng-prevent-navigation-text="Payment form has unsaved changes. 
     If you leave the page now you will lose those changes."
></div>
```