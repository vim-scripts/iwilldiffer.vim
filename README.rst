========
Overview
========

iwilldiffer is a vim plugin that shows you vcs diff add/mod/del lines
in the gutter.

iwilldiffer supports git, hg, bzr

Dependencies
============

You need diff, python (2.6+), vim, and whichever supported vcs tool you
wish to use.


Usage
=====

Install the plugin (TODO: describe the magic which is installing vim plugins)


You might want the following in your `.vimrc`:

::
    
    let g:iwilldiffer_check_on_open=1
    let g:iwilldiffer_check_on_save=1

Gutter Color
============

Gutter background color is controlled by value for `highlight SignColumn`.  Change
this value in your colorscheme or add to your `.vimrc`:

::
    highlight SignColumn guibg=foo ctermbg=foo


Contributors
============

  * `Shu Zong Chen`_

.. CONTRIBUTORS

.. _`Shu Zong Chen`: http://freelancedreams.com/
