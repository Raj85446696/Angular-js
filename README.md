# AngularJS Feature Summary – Single Page Reference

This AngularJS app demonstrates basic event handling and data binding. Below are the key AngularJS directives used, with definitions and examples:

---

### ✅ `ng-app`
**Definition:** Bootstraps the AngularJS application.  
**Example:** `<html ng-app="myApp">`

---

### ✅ `ng-controller`
**Definition:** Attaches a controller to the view and defines the `$scope`.  
**Example:** `<body ng-controller="myctrl">`

---

### ✅ `{{ expression }}`
**Definition:** Binds AngularJS expressions to display dynamic content.  
**Example:** `<p>{{4+9}}</p>`

---

### ✅ `ng-click`
**Definition:** Calls a function when an element is clicked.  
**Example:** `<button ng-click="Done()">click Me</button>`

---

### ✅ `ng-dblclick`
**Definition:** Calls a function on double-click.  
**Example:** `<button ng-dblclick="dbclick()">dbclick</button>`

---

### ✅ `ng-mouseup` / `ng-mousedown`
**Definition:** Mouse up triggers on release; down triggers on press.  
**Example:**  
```html
<button ng-mouseup="counter('+')">+</button>
<button ng-mousedown="counter('-')">-</button>
✅ ng-mouseenter / ng-mouseleave / ng-mousemove
Definition: Handle mouse events entering, leaving, or moving over an element.
Example:

html
Copy
Edit
<button ng-mouseenter="MouseEnter()">MouseEnter</button>
<button ng-mouseleave="MouseLeave()">MouseLeave</button>
<button ng-mousemove="MouseMove()">MouseMove</button>
⚠️ ng-mousehover
Note: This is not a valid AngularJS directive. Use ng-mouseover instead.
Fix Example: <button ng-mouseover="MouseOver()">MouseOver</button>

✅ ng-focus
Definition: Calls a function when the input field is focused.
Example:

html
Copy
Edit
<input type="text" ng-focus="colorCh()" ng-style="{'background-color':color}">
✅ ng-style
Definition: Dynamically applies CSS styles.
Example: ng-style="{'background-color': color}"

✅ ng-copy / ng-paste / ng-cut
Definition: Handle copy, paste, and cut clipboard events.
Example:

html
Copy
Edit
<input ng-copy="cp()" ng-paste="pas()" ng-cut="cut()">
