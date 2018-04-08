# form-style
Simple HTML Form style

Form-style is a very simple css/javascript plugin to style your forms.

## Installation
Install this module and its dependencies using bower:
```
bower install --save form-style
```
Or yarn:
```
yarn add form-style
```

## Features
Override variables (SASS):
```
$postfix: '¥';
$success-color: rgba(60, 118, 61, 0.7);
$error-color: rgba(169, 68, 66, 1);
@import '~form-style/scss/form-style';
```


#### Automatically highlight required form elements
When the form element is marked required (`requred="required"`), it automatically mark a red left-border when the value is empty. The left-border turns green automatically once there is value filled in the element.
