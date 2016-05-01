# webapp_browser_file


#### Define Document

```
<!DOCTYPE html>
```

#### Set Up Angular 
```
<html lang="en" ng-app="demo" ng-controller="Ctrl">
```

#### HTML Page Head 
```
<head>
```

#### Character Set
```
<meta charset="UTF-8">
```

#### Mobile View Port 
```
<meta name="viewport" content="width=480; user-scalable=no" />
```

#### Page & Site Title
```
<title>{{ page_name }} - {{ Site }}</title>
```

#### CSS Style Code 
```
<style type="text/css">
body { padding: 0; margin: 0 ; }

</style>
```

#### Traffic Analytics
```
{{ analytics|safe }}
```

#### Angular.js Script Files
```
<script type="text/javascript" src="../../files/angular.min.js"></script>
<script type="text/javascript" src="../../files/angular-sanitize.min.js"></script>
```

#### Angular Module JS App
```
<script>
var demo = angular.module("demo", ['ngSanitize'],
  function($interpolateProvider) {
    $interpolateProvider.startSymbol('[!');
    $interpolateProvider.endSymbol('!]');
}) ///

```

#### Angular Controller
```
demo.controller('Ctrl', function($scope, $http) {
```

#### Open User Function
```
  $scope.openUser = 'yes';
  $scope.hideUser = function () { $scope.openUser = 'no'; };
  $scope.showUser = function () { $scope.openUser = 'yes'; };
```

#### Slide Menu Function
```
  $scope.openMenu = 'yes'; $scope.menu_icon = '&#8602;';
  $scope.slideMenu = function () { 
    if ($scope.openMenu == 'yes') { $scope.openMenu = 'no'; $scope.menu_icon = '&#10155;'; }
    else if ($scope.openMenu == 'no') { $scope.openMenu = 'yes'; $scope.menu_icon = '&#8602;'; };
  };
```

#### Close Angular Controller Sccript & Open Body
```
}) /// - demo.controller('Ctrl',

</script>
</head>
<body>
```


