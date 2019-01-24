# Go Template

1. Use tab
1. Always put EOL
1. Left indent for flow-control code (eg. if, range, with)

	```html
	<div>
		<div>
			<p>xxx</p>
		{{if .ShowDiv}}
			<div>
				{{.Text}}
			</div>
		{{end}}
		</div>
	</div>
	```

1. Multi-line attributes

	```html
	<input
		type="number"
		class="class-1 class-2 class-3"
	{{if .Disable}}
		disabled
	{{end}}>
	```
