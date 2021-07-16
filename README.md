bookmarks.public
================

This repository allows you to save your bookmarks under revision control,
via a simple combination of HTML, CSS & Javascript.

* You add your bookmarks to the file `bookmarks.data`.
* Then view them by opening `index.html` in your browser.
    * The file `bookmarks.css` is used to style the presentation.
    * The file `bookmarks.js` makes the bookmarks interactive.




Browser Limitations
-------------------

Because the javascript attempts to open the `bookmarks.data` file via a
`file://` URI this "application" will __not__ work on all browsers.

The author is happy that it works on Firefox/Iceweasel, and would welcome
any operational improvements for other browsers.  Currently this is __known to
fail__ upon Chrome and Safari.



Rationale
---------

I didn't like any of the online bookmark-syncing plugins/addins/tools I tested.

The idea of hosting an online bookmark server is appealing, but using the
power of `git` it seems that having a local bookmark file should be pretty robust:

 * New items are added, generally one per line.
 * Existing items can be edited to add new tags.
 * Merges should be painless.

The included javascript magic is present solely to make the bookmarks
manageable, in my private copy I have 400+ bookmarks and with the
tagging support present here they will continue to work for me easily.


Usage
-----

If you wish to use this bookmarks script, and are happy for your bookmarks
to be public, then just fork [this repository](https://github.com/skx/bookmarks.public) and you're done.

If you prefer to keep your bookmarks private, as I do, then you'll need to
host your repository somewhere private.

To get started you might wish to examine contributed importers found beneath the [importers directory](importers/), which might be of interest.

For advanced usage you can see:

* [Adding/Editing bookmarks via your browser](Browser.md)


Contributing
------------

If you wish to submit improvements to the javascript, or the CSS, then I welcome forks & pull requests.

>**NOTE**: If you submit a change feel free to add a link to your homepage/blog/whatever as part of that.  The included bookmarks are only examples.


Steve
--
# Changes Log

# 2021-07-16
Osiris Berbesia
23e85bb2f2f6f23835ed0c36ff0892e2a844dcd5
### se modifican los botones de editar y borrar
### se agrega tooltip a los botones de guardar e ir arriba
845f082
# 2021-07-16
Osiris Berbesia
7a8dc7d9c87908f5c7683404854c3c68fd379542
### se agregan boton de guardar y de ir arriba, se agrega color a los tags para diferenciarlos
58bf2d0
# 2021-07-13
Osiris Berbesia
eb4bb8b5b76c10d371f856b4befa48c3187a2174
### boton inicio + cambio de layout
54c916b
# 2021-07-12
Osiris Berbesia
6466914932ab31b78dd3e33d1eb401bfbde4586e
### edits
851b78e
# 2021-07-11
Osiris Berbesia
775a06fc0305259e5fae0d71a71f970b8fddc47f
correcciones2
90e722f
# 2021-07-06
Osiris Berbesia
35f28247399aab960a4e7974030a54268946a3bb
### f5
4985973
# 2021-07-06
Osiris Berbesia
121373ba10208ccd4c1d25bcf146d58f7405b81d
### public.bookmark
e293299
# 2021-07-06
Osiris Berbesia
1c7364bf31554871ad38b730ec2cbc051c746a37
### direccion absoluta
b83762c
# 2021-07-06
Osiris Berbesia
c0368cf1f7b57e4aa85e10dc0222b30cfccd4480
### agregar archivos
1c8375c
# 2021-07-06
Osiris Berbesia
ff62b6813b3f35471accb65865f72821c7129d99
### first commit
5c9dff4





# DEMO

[LINK](https://osirisberbesia.github.io/all_repo/repository/bookmark.public/index.html)
