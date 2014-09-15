# jQuery Sanitize
#### A jQuery plugin for stripping tags and attributes from markup
#### Supports whitelists

### Usage

```javascript
// strip all tags
$('#container').stripTags();

// strip all attributes
$('#container').stripAttributes();

// strip all tags except paragraphs and links
$('#container').stripTags('p, a');

// strip all attributes except href and id on links
$('#container').stripAttributes([
	{
		tag: 'a',
		allowedAttributes: ['href', 'id']
	}
]);
```

© 2014 [Greg Rotter](http://www.ocf.berkeley.edu/~grotter/). Released under the [MIT
License](http://www.opensource.org/licenses/mit-license.php).
