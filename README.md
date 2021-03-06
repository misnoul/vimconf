vimconf
=======
* Super easy to install
* Everything in vimrc is explained
* Autocomplete, syntax checker, plugin manager and much more

Installation
------------
**Required packages:** clang, ctags, jedi, ruby

    git clone https://github.com/timss/vimconf.git
    ln -s vimconf/.vimrc ~/.vimrc

Run vim and it'll download and install all plugins for you!

Configuration
-------------
If you choose to symlink your `~/.vimrc` you can easily maintain an updated
version of this vim configuration by using the local additions.

`~/.vimrc.bundles`  Add your personal bundles here.   
`~/.vimrc.first`    Prerequisites only, as it will be overwritten by whatever below.   
`~/.vimrc.last`     Overrides everything. Generally use this.   

Even if this configuration can be used out of the box or tweaked using
the local files, I urge you to build your own if you have the time and
energy to do so. Only then will you be able to properly understand the
reasoning behind each setting and tailor it to your personal workflow.

However I still believe my Vim setup will help you get a basis configuration
for your own, introducing core ideas such as a plugin manager and
`.vimrc` structure. Use this configuration well, but do not blindly trust it to
suit you perfectly. It's intended to be played with!

Preview
-------

\(somewhat outdated, different statusline, ...)   
![Preview](http://i.imgur.com/L0axH7e.png "Vim screenshot, C++ autocomplete")

\(pretty outdated...\)    
[Writing a small perl-script using Vim](http://youtu.be/DrzAuLsxgwU)

Suggestions and questions
-------------------------
Feel free to give me suggestions, ask questions or point out things that needs
to be fixed by adding an [issue](https://github.com/timss/vimconf/issues).

Todo
----
* Potentially add [YouCompleteMe](https://github.com/Valloric/YouCompleteMe),
which would replace [clang\_complete](https://github.com/Rip-Rip/clang_complete), 
[supertab](https://github.com/ervandew/supertab) and maybe even 
[jedi-vim](https://github.com/davidhalter/jedi-vim)
* Better/more plugins and binds for Python
* Statusline:
    * Previously used vim-powerline, then airline and now lightline.
    * Lightline is much easier to configure, but missing some functionality
      out of the box.
    * Interact with tagbar (etc)?
    * Override tabline changes?
