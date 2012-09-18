highlighter.js
==============

A jQuery plugin that allows for enabling tooltips on user selected text


Usage
-----

Include the script on your page (make sure to use the correct path here)

```
<script type="text/javascript" src="/js/jQuery.highlighter.js"></script>
```

Activate the highlighter on the element of your choice, e.g.

```
$('.article').highlighter();
```

to deactivate it, use

```
$('.article').highlighter('destroy');
```

### Options

On init you can pass in a settings object that will recognize two parameters:

```
$('.article').highlighter({
                           'selector': '.highlighter-container',
                           'minWords': 0
});
```

Where ```selector``` is the jQuery selector string of the element that you want to show upon text being selected, and ```minWords``` is the minimum number of words that have
to be selected in order for the tooltip to appear. The defaults are ```'.highlighter-container'```, and ```0```, respectively.


Compatibility
------

This plugin has been tested in Chrome, Firefox, Safari and IE 9.



Authors
-----

- Matthew Conlen, matt.conlen@huffingtonpost.com

License
-----
Copyright © 2012 Huffington Post Labs. 

This program is free software. It comes without any warranty, to
the extent permitted by applicable law. You can redistribute it
and/or modify it under the terms of the WTFPL, Version 2, as
published by Sam Hocevar. See http://sam.zoy.org/wtfpl/
for more details.
