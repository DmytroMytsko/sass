My Sass template (by akella), or boilerplate, whatever =) I should invent some cool name later on.
=============

I'm using this as a starting template for almost any project now.
It includes sprites, assorted mixins (aka code snippets), file structure, jquery+cycle+scrollto (most usable these days).
And, that's it.

You need to have Compass installed for it to work properly.

Structure
=============
_/sass/libs_ - all the mixins and libs needed for us.

_/sass/_mixins.scss_ - agregates all those libraries and some common styles

_/sass/screen.scss_ - agregates all .scss files.

Naming blocks
=============
I use BEM naming, meaning _.block_ for independent block. .block__element for elements inside that block. And _.block_modification_ for modification of the block.

_layouts.css_ consists of all the columns-header-footer stuff, all with _.l-*_ prefixes. So you know its layout.

States of the blocks use prefix _.is-*_. For example .is-running, .is-hidden, .is-open.

Hooks for js should use prefix _.js-*_.
