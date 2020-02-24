Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle and Daniel Cones (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

#### Citations

Getting rainbow text in `ugly.css` was accomplished with the help of: <br>
question : https://stackoverflow.com/questions/40557461/rainbow-gradient-on-text-in-css <br>
answer   : https://stackoverflow.com/questions/40557461/rainbow-gradient-on-text-in-css/40557564#40557564 <br>
Asker Eric NEMO https://stackoverflow.com/users/5762965/eric-nemo <br>
Answerer Pavel Shalamkov https://stackoverflow.com/users/6053654/commercial-suicide <br>

Modifications to Project Gutenberg HTML Files
=============================================

#### In all three files:

Added `<link rel="stylesheet" type="text/css" href="gutenberg.css">`

Adding `class="chapter_first_paragraph"` to the first `<p>` of every paragraph by replacing <br> `(.*<h2>\n.*CHAPTER(.*\n)*?.*<p).*(>)` <br>with<br> `$1 class="chapter_first_paragraph"$3`

#### In Moby Dick:

Commented out:

`/* body { background:#ffffff; color:black; margin-left:15%; margin-right:15%; text-align:justify } */`

`/* .mynote    {background-color: #DDE; color: #000; padding: .5em; margin-left: 10%; margin-right: 10%; font-family: sans-serif; font-size: 95%;} */`

#### In The Problems Of Philosophy:

Commented out:

`/* body { margin:5%; background:#faebd0; text-align:justify} */`
