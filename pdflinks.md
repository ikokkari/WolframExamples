# Links to PDF versions of my Wolfram Mathematica documents

[Ilkka Kokkarinen](http://www.scs.ryerson.ca/~ikokkari/), _ilkka.kokkarinen@gmail.com_ 

This document contains links to educational documents about the [Wolfram Mathematica](https://www.wolfram.com/mathematica/) programming language, written by [Ilkka Kokkarinen](http://www.scs.ryerson.ca/~ikokkari/). All these documents are free to read and distribute with proper attribution. If you spot an error or some potential places for improvement anywhere in these documents, please let me know. These documents are available on DropBox in PDF format.

Wolfram Mathematica is my absolute favourite programming language. Unlike other languages, the download and installations costs money, but you can make yourself a free account to [Wolfram Cloud Development Platform](https://www.wolframcloud.com/) and try out the entire language interactively for free, keeping [the language documentation](http://reference.wolfram.com/language/) open in another tab, with some usage limitations that are large enough to be practically meaningless. I wholeheartedly recommend anybody getting to know this wonderful language and use it to solve actual problems.

**_My Wolfram language "for bright beginners" tutorial_**

This five-part tutorial goes through the various aspects of the Wolfram programming language, illustrating the ideas and features with both practical and theoretical examples. It would be suitable to read after the official "[Elementary Introduction to Wolfram](https://www.wolfram.com/language/elementary-introduction/2nd-ed/)" for non-programmers or "[Fast Introduction to Wolfram](http://www.wolfram.com/language/fast-introduction-for-programmers/en/)" for programmers. Many of these examples go much deeper than could be achieved in a typical introductory programming language such as Java or even Python, covering many topics that one would typically encounter in the third or fourth year of a typical computer science undergraduate curriculum. Together these five parts comprise a virtual textbook on Wolfram Mathematica and computer science in general with about 250 pages of material in PDF format.


*   [Expressions](https://www.dropbox.com/s/b2xdxb5afpvrfv0/Expressions.pdf?dl=0)
*   [Lists](https://www.dropbox.com/s/werrh8ybqfjnpqg/Lists.pdf?dl=0)
*   [Patterns](https://www.dropbox.com/s/e3u0jyltgtvszlh/Patterns.pdf?dl=0)
*   [Algebra](https://www.dropbox.com/s/hautwscqd2srua7/Algebra.pdf?dl=0)
*   [Geometry](https://www.dropbox.com/s/u1920ubevuffmnz/Geometry.pdf?dl=0)

**_My Computational Art created with Wolfram Mathematica_**

I have published some computational art at [ilkkakokkarinen.blogspot.com](https://ilkkakokkarinen.blogspot.ca/), including the printable PDF versions and the full Wolfram source code for all images. This blog has been dormant since January 2018 since I have been busy with teaching Java, Python and artificial intelligence this semester.

My older art tumblr of animated gifs of algorithmic art from a couple of years ago was called [Quickly Colourful Theorist](http://qctimages.tumblr.com/), for the three random words that Imgur suggested for me when I signed up and I thought were too good not to keep. Some good tags would be [black and white](http://qctimages.tumblr.com/tagged/black-and-white), [fractal](http://qctimages.tumblr.com/tagged/fractal), [turtle](http://qctimages.tumblr.com/tagged/turtle) and [pixelsort](http://qctimages.tumblr.com/tagged/pixelsort).

**_My other Mathematica documents_**

"[Solving The Lab Problems of Introductory Java Course in Wolfram](https://www.dropbox.com/s/2qtw7whzv8zfn0z/JavaExercises.pdf?dl=0)" details my experiences in trying to solve [the lab problems of my CCPS 109 course](https://docs.google.com/document/d/1l9IeT9brVc1Hwbip5rpTNEvIje3rfet_j37DgoVUyUI/edit?usp=sharing), originally in Java in a functional programming fashion using Wolfram. Solving these 42 lab problems will at some point visit basically every part of the Wolfram core language.

"[Snakes and Ladders](https://www.dropbox.com/s/b95dt077ugta6eh/SnakesAndLadders.pdf?dl=0)" shows how to use both the symbolic equation solver or the linear algebra engine of Wolfram to solve the game (well, more accurately an automaton) of Snakes and Ladders. We then additionally solve this problem with straightforward numerical simulation.

"[Satisfiability](https://www.dropbox.com/s/xhlg37rjaa9qjxc/Satisfiability.pdf?dl=0)" demonstrates the general technique to encode problems such as Sudoku or Conway's Game of Life as sets of clauses of propositional logic variables, and solve those problems in that domain. Since propositional logic has no concept of direction of time, Game of Life can be executed backwards in time using the same set of clauses but this time solving for the propositions that encode the game state at the previous moment. The last test of propositional logic is encoding the problem "[Crack-free tiles](https://projecteuler.net/problem=215)" of Project Euler to such clauses, where this technique fares pretty badly compared to the memoized backtracking solution using higher level algorithmics.

"[Superformulaic art](https://www.dropbox.com/s/nsi2q12crc3gg4a/SuperEllipse.pdf?dl=0)" first looks at the mathematics of superellipses. After filling an area with randomly chosen superellipses expanded to kiss each other, we move into the mathematical and computational steps required to produce a repeating animated gif that is an endless loop without any visible seam in the jump back to the first frame. Along the way, perspective projections, motion smoothing techniques and image processing deconvolution tricks are also discussed.

"[Brainfilling segments](https://www.dropbox.com/s/3as63gnz5w3y78g/BrainFilling.pdf?dl=0)" defines a general scheme and the necessary functions that subdivide the given line segment into a higher-dimensional fractal pattern, as explained in the excellent online bestiary "[Brainfilling Curves](http://www.brainfillingcurves.com/)". The resulting fractals are then rendered in various more or less artistic ways.

"[Those Dreaded Word Problems](https://www.dropbox.com/s/awhaeebupkxmsea/WordProblems.pdf?dl=0)" demonstrates a whole bunch of string processing operations to  solve several classic computations of English text, using both _War and Peace_ and the _Mathematica_ English wordlist as sources of data. String problems are solved with associations, regular expressions, graph algorithms and propositional logic satisfiability, which hopefully makes all these techniques clearer for the reader.
