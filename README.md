# book-quotes
A collection of quotes from books I've read organized as flat files & folders

## Motivation
After trying many times to switch to reading books parimarily on an ereader or tablet I've found I just don't enjoy it as much. They do provide one great convenience though - capturing all my highlights and notes in one place and having them be searchable.

## Organization
To get the best of both worlds, I type out quotes or passages that stand out to me along with any notes I may have. Each quote is stored as a flat text file in a subdirectory for that particular book, which may include a directory for chapters. I had originally been doing something similar with Emacs and Org-mode but would rather not rely on having to use Emacs to comfortably search and organize the quotes, especially since it is not my primary text editor.

The general structure is as follows:

`classification/genre or topic/title/(chapter)/.quote files`

The first and sometimes only file in a book's directory is the `_info` file. These files include book title, author(s), and ISBN number.

I add the `.md` suffix to all `.quote` files to make them nicer to read on github.

The title of a `.quote` file is what the quote is about to me. Since I haven't been keeping track of page numbers up until now many quotes won't have them, but going forward I'll add page number as a prefix like so: `241_duality.quote`.

I intend to include chapters subdirectories from now on. Unfortunately, like page numbers, I haven't been keeping track of chapters, so some books will be missing them.

Any notes I have appear in the `.quote` file below the quote itself, on a new line.

## Reading list

### Programming

* _Programming Pearls_ by Jon Bentley
* _More Programming Pearls_ by Jon Bentley
* _Refactoring: Improving the Design of Existing Code_ by Fowler, Beck, Brant, Opdyke, Roberts
* _The Art of Computer Programming_ by Donald Knuth
* _Code Complete: A Practical Handbook of Software Construction, Second Edition_ by Steve McConnell
* _Etudes for Programmers_ by Charles Weatherell

### Software design

* _The Mythical Man Month: Essays on Software Engineering_ by Frederick P. Brooks
* _The Peopleware Papers: Notes on the Human Side of Software_ by Larry Constantine
* _Hackers & Painters: Big Ideas from the Computer Age_ by Paul Graham
* _Pragmatic Thinking and Learning: Refactor Your Wetware_ by Andy Hunt
* _The Pragmatic Programmer: From Journeyman to Master_ by Andrew Hunt & David Thomas

### Craftsmanship

* _The Timeless Way of Building_ by Christopher Alexander
* _Fifteen Craftsmen on Their Crafts_ by John Farleigh
* _Mastery: The Keys to Success and Long-Term Fulfillment_ by George Leonard
* _Software Craftsmanship: The New Imperative_ by Pete McBreen
* _The Craftsman_ by Richard Sennet


### Mathematics / algorithms

* _The Algorithm Design Manual_ by Steven Skiena

### Philosophy

* _Zen Mind, Beginner's Mind_ by Shunryu Suzuki
* _The Psychology of Computer Programming_ by Gerald Weinberg

### RFCs

* [RFC 707](https://tools.ietf.org/html/rfc707): A High-Level Framework for Network-Based Resource Sharing
* [RFC 2616](https://tools.ietf.org/html/rfc2616): Hypertext Transfer Protocol -- HTTP/1.1

### Papers

* [The Five Orders of Ignorance](http://www.la-acm.org/Archives/laacm0512-Article%2002%20The%205%20Orders%20of%20Ignorance%20OCT%202000.pdf)

