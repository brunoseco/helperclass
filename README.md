# helperclass
A simpler class manager of your html

* Using only pure JavaScript

### Installation

```bash
$ npm install helperclass
```

### Example
```html
<script src="helperclass.js">
	var element = document.getElementById("my-id");

	windows.helperclass.has(element, 'class-name');
	windows.helperclass.add(element, 'class-name');
	windows.helperclass.remove(element, 'class-name');
	windows.helperclass.toggle(element, 'class-name');
</script>
```

OR

```js
import helperclass from 'helperclass'

var element = document.getElementById("my-id");

helperclass.has(element, 'class-name');
helperclass.add(element, 'class-name');
helperclass.remove(element, 'class-name');
helperclass.toggle(element, 'class-name');
```
element => params is the element to find, 'class-name' => params is will work

#### Props

| Name          | Description
| :------------ | :-----------
| has           | Verify element has class (true or false)
| add           | Add class to element
| remove        | Remove class to element
| toggle        | Add class to element if not exist ou remove if exist
