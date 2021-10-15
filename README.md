# multitail (pcre2)

This is a fork of the original `multitail` made from the [most recent fork by @halturin](https://github.com/halturin/multitail), with some [bug fixes by @actuday6418](https://github.com/actuday6418/multitail).

It was created mainly because I wanted to have better (e.g. non-greedy) regular expressions in `multitail`, and switching to `pcre2posix` was pretty easy. This is a non-breaking change, and it will let you simplify your syntax schemes.

I have no plans for future development or refactoring because `multitail` has been feature-complete for many years now, but I will probably merge in bug fixes from other forks every now and then.
