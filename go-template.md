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
