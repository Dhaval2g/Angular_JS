# AngularJS is a *JavaScript Framework.*
> It can be added to an HTML page with a ```<script>``` tag, same as we use for **JavaScript**.

> AngularJS exteds HTML attribute with **Directives**, and binds data to HTML with Expressions.
```javascript
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>
```
# AngularJS Extends HTML
> AngularJS entends HTML with **ng-directivevs.**

> The **ng-app** directive defines and AngularJS application.

> The **ng-model** directive binds the value of HTML controls (input, selcet, textarea) to application data.

> The **ng-bind** directive binds application data to the HTML view.

# Example 
```JavaScript
<!DOCTYPE html>
<html>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>
<body>

<div ng-app="">
  <p>Name: <input type="text" ng-model="name"></p>
  <p ng-bind="name"></p>
</div>

</body>
</html>
```
> Explanation:

> * AngularJS starts automatically when the web page has loaded.

> * The **ng-app** directivee tells AngularJS that the ```<div>``` element is the "owner" of and AngularJS **Application**.

> * The **ng-model** directive binds the value of the input field to the application variable **name.**

> * The **ng-bind** directivve binds the **innerHTML** of the ```<p>``` element to the applicaiton variable **name**.
