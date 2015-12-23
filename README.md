SublimeText 3 Snippets
======================

Installation
------------

    cd %USERPROFILE%\AppData\Roaming\Sublime Text 3\Packages\User
    git clone https://github.com/mac2000/Snippets.git

Sublime Settings
----------------

    {
        "default_line_ending": "unix",
        "ensure_newline_at_eof_on_save": true,
        "highlight_line": true,
        "ignored_packages": ["Vintage"],
        "word_wrap": false,
        "show_encoding": true,
        "show_line_endings": true,
        "trim_automatic_white_space": true,
        "fallback_encoding": "Cyrillic (Windows 1251)",
        "trim_trailing_white_space_on_save": true
    }

Keybindings
-----------

    [
        { "keys": ["ctrl+,"], "command": "expand_selection", "args": {"to": "scope"}, "context": [{"key": "selector", "operator": "not_equal", "operand": "text.html.basic"}] }
    ]


Remapped selection expand to be `ctrl+,` like in [Emmet](https://packagecontrol.io/packages/Emmet)

Plugins
-------

* [Emmet](https://packagecontrol.io/packages/Emmet)
* [Smart Delete](https://packagecontrol.io/packages/Smart%20Delete)

Usefull shortcuts
-----------------

`ctrl+shift+'` - rename tag

`ctrl+,` - expand selection (by Emmet only in HTML scope)

`ctrl+shift+space` - expand selection to scope
