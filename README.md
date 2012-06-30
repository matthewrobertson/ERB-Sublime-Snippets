ERB-Sublime-Snippets
====================

A collection of [Sublime Text](http://www.sublimetext.com/) snippets useful for writing [ERB](http://ruby-doc.org/stdlib-1.9.3/libdoc/erb/rdoc/ERB.html)

##Installation

Simply checkout the source code into Sublime Text's packages directory. The location is system specific:

### For OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    $ git clone git://github.com/matthewrobertson/ERB-Sublime-Snippets.git ERB_Snipptes

### For Windows

    $ cd %APPDATA%/Sublime Text 2/Packages/
    $ git clone git://github.com/matthewrobertson/ERB-Sublime-Snippets.git ERB_Snipptes

### For Linux

    $ cd ~/.Sublime Text 2/Packages/
    $ git clone git://github.com/matthewrobertson/ERB-Sublime-Snippets.git ERB_Snipptes

##Snippets and Bindings

<table>
  <tr>
    <th>Snippet</th>
    <th>Tab Trigger</th>
    <th>Output</th>
  </tr>
  <tr>
    <td>ERB tags</td>
    <td>__er__</td>
    <td>`<%  %>`</td>
  </tr>
  <tr>
    <td>print ERB tags</td>
    <td>__pe__</td>
    <td>`<%=  %>`</td>
  </tr>
  <tr>
    <td>`if` block</td>
    <td>__if__</td>
    <td>`<% if  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`if` / `else` block</td>
    <td>__ife__</td>
    <td>`<% if  %>...<% else %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`end` block</td>
    <td>__end__</td>
    <td>`<% end %>`</td>
  </tr>
<table>

##License

Released under [WTFPL, Version 2](https://raw.github.com/matthewrobertson/ERB-Sublime-Snippets/master/LICENSE.txt)