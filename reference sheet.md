# Header 1
## Header 2
### Header 3
#### Header 4

1. _italics_
2. **bold**
3. ==highlight==
4. `code`

> Blockquote

```
<html>
	<title>Hello, world! This is a code block</title>
</html>
```

## Specific to blog

### Side notes and margin notes

`{% sidenote 'sn-referenceID' 'Text for sidenote' %}` This will create a side note in the margin; ie: marginalia or footnote. 
`{% marginnote 'mn-referenceID' 'Text for margin note' %}`

Styling recommends that you use `sn-` prefix for sidenote ids and `mn-` prefix for margin notes. Not sure what the difference is other than sidenotes are numbered and margin notes are not.

### New thoughts

`{% newthought 'Insert text her' %}` - new thought: anything inside single quotes will be in all small caps

### Epigraph

`{% epigraph %}`
The English language . . . becomes ugly and inaccurate because our thoughts are foolish, but the slovenliness of our language makes it easier for us to have foolish thoughts.

<footer>George Orwell, <cite>“Politics and the English Language”</cite></footer>
`{% endepigraph %}`

Use `{% epigraph %}` for a quote to introduce a page or section of page

### Figures

To insert figure directly into main flow of discussion:

`{% maincolumn 'img/image.jpg' 'Text here will be inserted as a sidenote in margin' %}`

To insert a figure into the margin:

`{% marginfigure 'mf-id-whatever' 'demo/img/rhino.png' 'Text written here will appear under the image in the margin' %}`

To insert a full-width image:

`{% fullwidth 'demo/img/napoleons-march.png' "" %}``