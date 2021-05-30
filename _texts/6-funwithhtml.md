---
layout: narrative
title: Fun with HTML and a Footnote
author:
editor: Sabina Pringle
rights:
source:
toc:

---
This is a footnote [^1]

[^1]: No, THIS is a footnote.

---

The text files on this site are written in kramdown. The great thing about kramdown is that I can write human readable text. kramdown (sic, not Kramdown or KramDown, just kramdown) is a free MIT-licensed Ruby library for parsing and converting a superset of Markdown. It is completely written in Ruby, supports standard Markdown (with some minor modifications) and various extensions that have been made popular by the PHP Markdown Extra package and Maruku.

Sometimes I want to do something I haven't figured out how to do with kramdown (this has often been because I didn't research enough - kramdown has excellent documentation). kramdown supports HTML, so I can use HTML. 

<p style="margin-left:10%; margin-right:10%;">This is to see what a little HTML can do</p>

<p style="margin-left:15%; margin-right:10%;">Because I might want to nest. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Est sit amet facilisis magna. Nulla facilisi nullam vehicula ipsum a arcu cursus vitae. </p>

<p style="margin-left:20%; margin-right:10%;">And nest. Turpis tincidunt id aliquet risus feugiat in ante. Enim nulla aliquet porttitor lacus luctus accumsan tortor. Enim nunc faucibus a pellentesque. </p>

<p style="margin-left:25%; margin-right:10%;">A whole load. Maecenas ultricies mi eget mauris. Nullam ac tortor vitae purus faucibus ornare suspendisse sed. </p>

<p style="margin-left:25%; margin-right:10%;">And on and on. Faucibus ornare suspendisse sed nisi lacus sed. Consequat interdum varius sit amet. </p>

<p style="margin-left:15%; margin-right:10%;">From level to level. Vitae tempus quam pellentesque nec nam aliquam sem et tortor. Aliquet risus feugiat in ante metus dictum at tempor commodo. Fusce id velit ut tortor pretium viverra suspendisse.</p>

Until I choose to stop nesting altogether. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Est sit amet facilisis magna. Nulla facilisi nullam vehicula ipsum a arcu cursus vitae.

---
