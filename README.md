ERB-Sublime-Snippets
====================

A collection of [Sublime Text](http://www.sublimetext.com/) snippets useful for writing [ERB](http://ruby-doc.org/stdlib-1.9.3/libdoc/erb/rdoc/ERB.html)

## Installation

These snippets can now be installed via [Sublime Package Control](http://wbond.net/sublime_packages/package_control). If you do not use package control, simply checkout the source code into Sublime Text's packages directory. The location is system specific:

### For OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    $ git clone git://github.com/matthewrobertson/ERB-Sublime-Snippets.git ERB\ Snippets

### For Windows

    $ cd %APPDATA%/Sublime Text 2/Packages/
    $ git clone git://github.com/matthewrobertson/ERB-Sublime-Snippets.git ERB\ Snippets

### For Linux

    $ cd ~/.Sublime Text 2/Packages/
    $ git clone git://github.com/matthewrobertson/ERB-Sublime-Snippets.git ERB\ Snippets

## Snippets and Bindings

Snippet | Tab Trigger | Output
--- | --- | ---
ERB tags | __er__ | `<%  %>`
print ERB tags | __pe__ | `<%=  %>`
print ERB comment | __pc__ | `<%#  %>`
`if` block | __if__ | `<% if  %>...<% end %>`
`if` / `else` block | __ife__ | `<% if  %>...<% else %>...<% end %>`
`else` tag | __else__ | `<% else %>`
`elsif` tag | __elsif__ | `<% elsif %>`
`unless` block | __unless__ | `<% unless  %>...<% end %>`
`end` block | __end__ | `<% end %>`
`image_tag` helper | __it__ | `<%= image_tag ..., ... %>`
`cl_image_tag` helper | __cli__ | `<%= cl_image_tag 'path' {*options*} %>`
`submit_tag` helper | __st__ | `<%= submit_tag ..., ... %>`
`text_field_tag` helper | __tft__ | `<%= text_field_tag ..., ... %>`
`password_field_tag` helper | __pft__ | `<%= password_field_tag ..., ... %>`
`label_tag` helper | __lblt__ | `<%= label_tag ..., ... %>`
`link_to` helper | __lt__ | `<%= link_to ..., ... %>`
`each` helper | __each__ | `<% *@things*.each do |*thing*| %> ... <% end %>`
`form_for` helper | __ff__ | `<%= form_for(@*model* ) do |f| %> ... <% end %>`
`simple_form_for` helper | __sf__ | `<%= simple_form_for(@ ) do |f| %> ... <% end %>`
`f.input` helper | __fi__ | `<%= f.input ... %>`
`f.button` helper | __fs__ | `<%= f.button :input ... %>`
`time_ago_in_words` helper | __tw__ | `<%= time_ago_in_words(...) %>`
`t()` helper | __t__ | `<%= t('@*model*') %>`

## Resolve conflicting tab trigger

It is possible for the snippets in this package to conflict with other Sublime text plugins, such as the built-in Rails package or [Rails Developer Snippets](https://github.com/j10io/railsdev-sublime-snippets). You may want to disable unwanted snippets.

### For Sublime Text 2

Delete unwanted snippet files from `~/Library/Application\ Support/Sublime\ Text\ 2/Packages/<PackageName>/`

### For Sublime Text 3

1. Install the [PackageResourceViewer](https://github.com/skuroda/PackageResourceViewer) Package
2. Open unwanted snippets with `PackageResourceViewer: Open Resource` command and comment it out

##Questions, Comments, Concerns?

Feel free to submit a pull request with any snippets you would like to add to the project. If you have any problems or suggestions you can contact me [on twitter](https://twitter.com/mattdrobertson).

## License

Released under [WTFPL, Version 2](https://raw.github.com/matthewrobertson/ERB-Sublime-Snippets/master/LICENSE.txt)
