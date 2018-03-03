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
* _The Go Programming Language_ by Alan Donovan & Brian Kernighan
* _[Starting FORTH](https://www.forth.com/starting-forth/)_ by Leo Brodie
* _Eloquent JavaScript_ by Marijn Haverbeke
* _Operating Systems Design and Implementation_ by Andrew Tanenbaum
* _Lions' Commentary on UNIX 6th Edition, with Source Code_ by John Lions
* _PoC || GTFO_ by Manul Laphroaig
* _xchg rax,rax_ by xorpd
* _Graphics Programming Black Book_ by Michael Abrash
* _Game Engine Black Book: Wolfenstein 3D_ by Fabien Sanglard
* _Writing An Interpreter In Go_ by Thorsten Ball
* _Build Your Own Lisp_ by Daniel Holden
* _The little book about OS development_ by Erik Helin & Adam Renberg
* _Game Programming Patterns_ by Robert Nystrom
* _Category Theory for Programmers_ by Bartosz Milewski
* _Structure and Interpretation of Computer Programs_ by Harold Abelson, Gerald Jay Sussman, Julie Sussman
* _Programming Languages: Application and Interpretation_ by Shriram Krishnamurthi

### Tools

* _Introduction to Operating Systems Abstractions Using Plan 9 from Bell Labs_ by Francisco J. Ballesteros
* _Absolute OpenBSD_ by Michael W. Lucas
* _Mastering Emacs_ by Mickey Petersen
* _sed & awk_ by Dale Dougherty
* _Unix Text Processing_ by Dale Dougherty and Tim O'Reilly

### Software design

* _The Mythical Man Month: Essays on Software Engineering_ by Frederick P. Brooks
* _The Peopleware Papers: Notes on the Human Side of Software_ by Larry Constantine
* _Hackers & Painters: Big Ideas from the Computer Age_ by Paul Graham
* _Pragmatic Thinking and Learning: Refactor Your Wetware_ by Andy Hunt
* _The Pragmatic Programmer: From Journeyman to Master_ by Andrew Hunt & David Thomas
* _The Cathedral & the Bazaar: Musings on Linux and Open Source by an Accidental Revolutionary_ by Eric S. Raymond
* _Joel on Software_ by Joel Spolsky
* _Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems_ by Martin Kleppman
* _Don't Make Me Think, Revisited: A Common Sense Approach to Web Usability_ by Steve Krug
* _The Design of Everyday Things_ by Don Norman

### Craftsmanship

* ~~_Apprenticeship Patterns_ by Dave Hoover & Adewale Oshineye~~
    * Completed Aug. 27 2017
* _The Timeless Way of Building_ by Christopher Alexander
* _Fifteen Craftsmen on Their Crafts_ by John Farleigh
* _Mastery: The Keys to Success and Long-Term Fulfillment_ by George Leonard
* _Software Craftsmanship: The New Imperative_ by Pete McBreen
* _The Craftsman_ by Richard Sennet
* _Coders at Work: Reflections on the Craft of Programming_ by Peter Seibel

### Mathematics / algorithms

* _The Algorithm Design Manual_ by Steven Skiena
* _The Tao of Physics: An Exploration of the Parallels Between Modern Physics and Eastern Mysticism_ by Fritjof Capra
* _A Discipline of Programming_ by Edsger Dijkstra
* _Selected Writings on Computing: A Personal Perspective_ by Edsger Dijkstra

#### Math curriculum, in order

1. _Number: The Language of Science_ by Tobias Dantzig & Joseph Mazur
2. _Innumeracy: Mathematical Illiteracy and Its Consequences_ by John Allen Paulos
3. _How Not to Be Wrong: The Power of Mathematical Thinking_ by Jordan Ellenberg
4. _Zero: The Biography of a Dangerous Idea_ by Charles Seife
5. _Calculus Made Easy_ 1910 edition by Silvanus Thompson
6. _A Tour of the Calculus_ by David Berlinski
7. _Elements of Euclid_ by Oliver Byrne
8. _Measurement_ by Paul Lockhart

### Philosophy

#### Introductory texts
* _Plato: Five Dialogues_ by Plato
* _The Problems of Philosophy_ by Bertrand Russell
* _The Pig That Wants to Be Eaten: 100 Experiments for the Armchair Philosopher_ by Julian Baggini
* _Think: A Compelling Introduction to Philosophy_ by Simon Blackburn
* _Utilitarianism_ by John Stuart Mill
* _Groundwork of the Metaphysic of Morals_ by Immanuel Kant
* _Nicomachean Ethics_ by Aristotle

#### Zen
* _Zen Mind, Beginner's Mind_ by Shunryu Suzuki

#### Stoicism
* _Meditations_ by Marcus Aurelius
* _Enchiridion_ by Epictetus
* _Discourses of Epictetus_ by Epictetus
* _Letters from a Stoic_ by Seneca the Younger
* _On the Shortness of Life_ by Seneca the Younger
* _Of Anger_ by Seneca the Younger
* _De Officiis_ by Marcus Tullius Cicero
* _Ego is the Enemy_ by Ryan Holiday
* _The Obstacle is the Way_ by Ryan Holiday
* _The Daily Stoic: 366 Meditations on Wisdom, Perseverance, and the Art of Living_ by Ryan Holiday

### Consciousness

* _Gödel, Escher, Bach: An Eternal Golden Braid_ by Douglas Hofstadter
* _I Am a Strange Loop_ by Douglas Hofstadter
* _The Society of Mind_ by Marvin Minsky
* _The Mind's I: Fantasies and Reflections on Self & Soul_ by Douglas Hofstadter & Daniel Dennett
* _The Systems View of Life: A Unifying Vision_ by Fritjof Capra & Pier Luigi Luisi

### Self-improvement
* _Catching the Big Fish_ by David Lynch
* _The Psychology of Computer Programming_ by Gerald Weinberg
* _King, Warrior, Magician, Lover_ by Robert Moore & Douglas Gillette
* _Soft Skills: The software developer's life manual_ by John Sonmez

### History

* _The Decline and Fall of the Roman Empire_ by Edward Gibbon

### Fiction

* _Shadow of the Torturer_ by Gene Wolfe
* _Claw of the Conciliator_ by Gene Wolfe
* _Sword of the Lictor_ by Gene Wolfe
* _The Citadel of the Autarch_ by Gene Wolfe
* _Mona Lisa Overdrive_ by William Gibson
* _Neuromancer_ by William Gibson
* _Count Zero_ by William Gibson
* _Idoru_ by William Gibson
* _Coin Locker Babies_ Ryu Murakami
* _Lucifer's Hammer_ by Larry Niven
* _Past Master_ by R. A. Lafferty
* _Eifelheim_ by Michael Flynn

### RFCs

* [RFC 707](https://tools.ietf.org/html/rfc707): A High-Level Framework for Network-Based Resource Sharing
* [RFC 2616](https://tools.ietf.org/html/rfc2616): Hypertext Transfer Protocol -- HTTP/1.1

### Papers

* [The Five Orders of Ignorance](http://www.la-acm.org/Archives/laacm0512-Article%2002%20The%205%20Orders%20of%20Ignorance%20OCT%202000.pdf) by Phillip G. Armour
* [Reflections on Trusting Trust](https://www.ece.cmu.edu/~ganger/712.fall02/papers/p761-thompson.pdf) by Ken Thompson
* Various from [_PoC || GTFO_](https://www.alchemistowl.org/pocorgtfo/)
* [Communicating Sequential Processes](http://www.cs.virginia.edu/crab/hoare1978csp.pdf) by C.A.R. Hoare
* [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf) by Satoshi Nakamoto
* [A Descent into Limbo](http://www.vitanuova.com/inferno/papers/descent.html) by Brian Kernighan

### Courses & online tutorials

* [Assembly Language Adventures](https://www.udemy.com/x86-asm-foundations/)
* [OpenGL Tutorial](http://www.opengl-tutorial.org)
* [Pete's Inferno OS guide](http://debu.gs/entries/inferno-part-0-namespaces)
