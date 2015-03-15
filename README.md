# AngularJS-Examples
List of examples to understand and practice AngularJS...

#Using ng-model directive
- Official Documentation: https://docs.angularjs.org/api/ng/directive/ngModel
- The directive ['ng-app'] [1] means that we are in an AngularJS application
- Hello yourName example:
```html
<html>
<head>
	<title>AnguleJS -Examples</title>
</head>
<body ng-app>
	<input type="text" ng-model="yourName" />
	Hello {{ yourName }}

	<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.3.14/angular.min.js"></script>
</body>
</html>
```

#Using ng-init directive
- Official Documentation: https://docs.angularjs.org/api/ng/directive/ngInit
- Display list values:
- Example #1
```html
<html>
<head>
	<title>AnguleJS -Examples</title>
</head>
<body ng-app>
	<h1>ng-init directive</h>
	<div ng-init="myList=['My', 'Name', 'Is', 'Ala', 'Eddine', 'Jebali']">
		myList = {{ myList }}
	</div>

	<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.3.14/angular.min.js"></script>
</body>
</html>
```
- Example #2
```html
<html>
<head>
	<title>AnguleJS -Examples</title>
</head>
<body ng-app>
	<h1>ng-init directive</h>
	<div ng-init="myList=['My', 'Name', 'Is', 'Ala', 'Eddine', 'Jebali']"></div>
	<ul>
		<li ng-repeat="itemValue in myList">{{itemValue}}</li>
	</ul>

	<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.3.14/angular.min.js"></script>
</body>
</html>
```






#Thank you!
- Ala Eddine JEBALI
- http://jebalialaeddine.com
- (+216) 96 529 067
- jebali.alaeddine (att gmail dot com)
- Edited using http://dillinger.io/


[1]: https://docs.angularjs.org/api/ng/directive/ngApp
