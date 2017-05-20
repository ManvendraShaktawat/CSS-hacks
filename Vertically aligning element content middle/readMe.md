## DOM stucture (Cannot be altered)

	<div>
		<div>1</div>
		<div>2</div>
		<div>3</div>
		<div>4</div>
	</div>


## WireFrame

![Alt text](/wireframe.jpg)

## Main points

1. **Vertical align middle - child div's text**
Aligning text vertically is usually achieved by "display: table-cell; vertical-align: middle;". But in this case, "float: left" was also declared which was ignoring display property. So the ":before" element on div is given "height: 100%; vertical-align: middle;".

2. **Achieving the given layout**
All the inner divs are floated left. For the even divs, "clear: left" is defined, so that it will start from the new line instead of floating in the same line.
