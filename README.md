# py-myopl-code

All code for my "Make your own programming language in Python" tutorial series on YouTube: https://www.youtube.com/playlist?list=PLZQftyCk7_SdoVexSmwy_tBgs7P0b97yD

This code is an interpreter for a BASIC-like language written in Python 3.

The latest code is in the folder which is for the latest episode (`ep14`).

I'm now finished with the development of this project, and the tutorials are complete on YouTube.

## Forks

Improvements have been made by others so I'll link to them here:

 - [AdrianGjerstad](https://github.com/AdrianGjerstad/py-myopl-code) - started on standard library and added string indexing

# Why OPLBasic?

For a long time I've dreamed have having a non-linear dialogue engine that instead of using plain text, would evaluate a code string. Unfortuntely because the risk of eval in JS and Python, you really can't do that. So I thought if I could make my own interpreted language that didn't have access to the os, maybe this could be a reality. 

So I found out that davidcallanan had built something already! To get some game dialogue started I just added a couple functions TO_STR() and RAND(). I hope to use OPLBasic to push a non-linear dialogue engine as far as I can. You can find the latest in 14.1. Any input anyone has would be greatly appreciated. Thank You.
