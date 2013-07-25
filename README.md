jQuery MultiTypeahead Plugin
===============

TODOs
-----
* Documentation (fiddle, examples, etc)
* Offer a minimum style (if you are not using FlatUIPro)
* Code cleanup - its my first jQuery plugin :)
* ...

Depends on:
----------
* [jQuery]
* [Bootstrap]
* [typeahead.js]

Features:
----------
* Multiple typeaheads
* Remote sources (like typeahead.js)
* Tokenize (allows only existing entries)
* Flat-UI-Pro classes
* ...

Examples
---------
[Simple]

Just a bunch of tags:

    $('#tags').multiTypeahead({
      name: "tags",
      valueKey: "name",
      remote: 'tags.json?q=%QUERY'
    });

Tokenizer allows existing entries only:

    $('#recipients').multiTypeahead({
      name: "recipients",
      valueKey: "name",
      remote: 'users.json?q=%QUERY',
      tokenizer: true,
      delimiter: [",", " "] // default
    });


Version
--------
0.1.1


## License
MIT License, full text of license see [here][License]

*Free Software, Fuck Yeah!*

[License]: https://github.com/kendrikat/jquery-multi-typeahead/blob/master/LICENSE "LICENSE"
[jQuery]: https://github.com/jquery/jquery
[Bootstrap]: https://github.com/twitter/bootstrap
[typeahead.js]: https://github.com/twitter/typeahead.js
[Simple]: http://jsfiddle.net/everyman/M9ncv/
