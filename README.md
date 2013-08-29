dix
===

Call me Ishmael. Dix is a utility for quantifying large amounts of plaintext data using a revolutionary metric: Moby-Dicks.

Motivation
----------
Have you ever found yourself analyzing text data and thinking, "Wow, this data is **BIG**. This is some **BIG DATA**"?

Of course you have. And if you're like us, you're frustrated with the current tools and metrics at your disposal. How do you quantify how **big** your data is? Bits and bytes and word counts just don't cut it in the fast moving Data Age.

It's time for a new standard. One that's timeless, yet fully capable of expressing **big**ness. That's why we created `dix`.


About
-----
`dix` is a command line utility that quantifies the size of plaintext data in relation to Herman Melville's classic novel [*Moby-Dick; or, The Whale*](http://www.gutenberg.org/files/2701/2701-h/2701-h.htm), first published in 1851 and considered to be one of the Great American Novels.

![Moby Dick is a sizeable book.](http://i.imgur.com/OCpXRf2.jpg)


Installation
------------

**Prerequisites: Python 2.6+, [wc](http://en.wikipedia.org/wiki/Wc_) (which is included on most *nix OSs)**

Run `sudo pip install dix` to install dix from PyPI (`dix` needs sudo access to set permissions so you can run it from anywhere).

More installation options coming soon.


Examples
--------
`dix` is run from the command line on a plaintext file, as follows.

`$> dix text.txt`

You can also pipe things into dix if desired:

`$> echo “for there is no folly of the beast of the earth which is not infinitely outdone by the madness of men” | dix`

`dix` also supports a multitude of options. For example, if you feel bad about the size of your data, choose a smaller unit of comparison:

`$> dix --tiny text.txt`

You can see all the options and how to use them by calling `dix -h`.


Contribution
------------

We welcome issues and pull requests if you find problems with dix or want to enhance it! You can also reach its creators at dix.heads@datascopeanaytics.com.

