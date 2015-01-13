## jQuery Name Badges Plugin
A simple jQuery Plugin for creating name badges.

### Example
This plugin turns elements like this:
```html
<div class="name">Bill Gates</div>
```
Into something like this:  
![Example0](https://raw.githubusercontent.com/SrcFlux/jquery-nameBadges/master/examples/example0.png)

### Usage
#### With default settings:
```js
$('.name').nameBadge();
```
![Example1](https://raw.githubusercontent.com/SrcFlux/jquery-nameBadges/master/examples/example1.png)

#### With custom settings:
```js
$('.name').nameBadge({
	border: {
		width: 0
	},
	colors: ['#FAD089', '#FF9C5B', '#F5634A', '#ED303C', '#3B8183'],
	text: '#333',
	margin: 15,
	size: 120
});
```
![Example2](https://raw.githubusercontent.com/SrcFlux/jquery-nameBadges/master/examples/example2.png)
