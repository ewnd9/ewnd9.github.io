---
layout: post
title: Angular $resource safari bug
date:  2015-08-07
description: "Angular $resource safari bug 'Requested keys of a value that is not an object'"
keywords: "angular, $resouce, resource, safari, requested, keys, value, object"
---

Recently i've stuck with `Requested keys of a value that is not an object.` exception
in angular code using $resouce in safari though code works in chrome.

Solution was change

```javascript
$scope.object.$update($scope.object.id)
```

to

```javascript
$scope.object.$update({ id: $scope.object.id })
```
