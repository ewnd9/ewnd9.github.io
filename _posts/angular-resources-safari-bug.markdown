---
layout: post
title: Angular $resource safari bug
date:  2015-08-07
categories: javascript angular safari
---

Recently i've stuck with `Requested keys of a value that is not an object.` exception
in angular code using $resouce in safari though code works in chrome.

Solution was change

```
$scope.object.$update($scope.object.id)
```

to

```
$scope.object.$update({ id: $scope.object.id })
```
