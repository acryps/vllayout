# Layout

Every page has `<ui-root>` inside of `<body>` as its root.

```
<!doctype html>
<html>
	<head>
		<title>vllayout example</title>

		<!-- make the layout adapt on mobile devices -->
		<meta name="viewport" content="width=device-width, initial-scale=1">

        <!-- include your compiled style sheet -->
		<link rel="stylesheet" href="/styles.css">
	</head>

	<body>
		<ui-root></ui-root>
	</body>
</html>
```