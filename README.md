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
