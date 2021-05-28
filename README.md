# vllayout
[![npm version](https://badge.fury.io/js/vllayout.svg)](https://badge.fury.io/js/vllayout)

Layout/Design framework based on tag/attribute styling

<a href="https://vlvt.in/dev/vllayout/">
	View documentation and examples
</a>

## Usage
Install the npm package in your client project
```
npm install vllayout
```

Create your own style root, lets call it `app.scss`
You can configure your colors and other variables here
```
// import vllayout
@use "../node_modules/vllayout/main" with (
	$page-color: #000,
	$page-background: #fff,
	$page-border-color: #ccc,
	$page-hover-background: #ddd,

	$page-accent-background: #007afa,
	$page-accent-color: #fff,
	$page-accent-active-background: #007afa,
	$page-accent-active-color: #fff,
	$page-accent-hover-background: #466079,
	$page-accent-hover-color: #fff,
);

// add custom elements, styles, imports, ...
```

Build your stylesheet with sass (`npm install -g sass`)
```
sass app.scss dist.css
```

Include `dist.css` in your webpage and have fun!