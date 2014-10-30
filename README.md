# b.dot
Let's put the dot in b.lateral!

## Install
Install the module with bower:
```
bower install --save bdot
```

## Usage
Import the module into your main scss file:

```css
@import "<your_bower_components>/bdot/scss/bdot"
```

In your markup you can use this module like so:

```html
<a href="http://blateral.com" class="bdot">
	&bull;<span>b.lateral - creative agency</span>
</a>
```

## Config
For now you can set the size and the color of the dot:

```scss
$bdot__color: #ff0000; 	// default is #1fc2f4
$bdot__size: 24px; 		// default is 32px

@import "<your_bower_components>/bdot/scss/bdot"
```