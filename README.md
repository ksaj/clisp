# Common Lisp / Lisp / LISP / CL / clisp / (◔_◔) 

> whatever it is you're doing would be done better in LispLanguage. Why? Don't ask, they can't explain it to the rest of us. 

I'm re-learning clisp after being away from it since the early 90's. If you know what alife or strange attractors are, you'll instictively know why I was surrounded by robots, NiTi muscle wires, random electronic ittybits, and LISP! To add something to the community, I'll be pointing out a lot of Lisp programming gotcha's... especially where security is involved. Eventually this will culminate in a couple of projects I have in mind that are very LISPy in nature. Including one I started back then, but seemingly only now is of technical interest.

I interchange all the terms in the title, even if it pisses off certain overly-bespectacled nerds who talk some of the talk, but walk little of the walk. If you are at a point where different flavours matter, you still should be able to fully grok everything I ever write on the subject. Leave the religious naming crap for reddit. You won't appeal to my interests on that level.

This is all pure Common Lisp, and I simply use clisp on my Raspberry Pi. It will surely work under any OS that even remotely looks and smells like Linux, and should work with little to no modification under anything that looks and smells like LISP. Except when I post my GPIO stuff which is rather rpi-centric. But it'll all be very documented anyway. I've been using clisp on my Mac, too, so... no excuses mmkay?

Everything is executed as a script. For example:  clisp 1.lisp

But read the code first. Truly. Yeesh.

> Once you get over the ugly parts, you can get actual work done -- even with Common Lisp.

I'll add stuff here that I think is good for learning the Lisp language, but not stuff that you find repeated everywhere else. That's just repetitive and boring. And repetative. I don't know why there are [500 "tutorials" with exactly the same content](http://wiki.c2.com/?SmugLispWeenie), yet so little genuinely usable Lisp content out there that didn't originate from black-and-white television days. Shameful really. It's like learning one song on violin just so you can teach that violin song while preaching the violin's many sonic wonders, yet never actually getting around to presenting any functional knowledge and skill outside of blatantly echoing the previous 499 people who also only know that song. It doesn't make for a very compelling argument for Lisp's utility at all. No wonder people keep tuning out whenever you mention violin. Have I mentioned how repetitive this mentality is?

That's enough of my bitching. Use this in combination with whatever tutorial you choose to learn from, as a way to learn genuinely useable code without making the same mistakes that have propogated this know-it-all history of "hackers" pretending they understand how powerful the language is, yet seemingly unable to get outside their regurgitation skills. And <i>Bloody L</i> don't write yet another copy of that same "tutorial" unless you actually <i>add</i> something that isn't in the 499 other "tutorials" you are aping!

## [1.lisp](https://github.com/ksaj/clisp/blob/master/1.lisp)
Asks your name, then gives a friendly hello. Documents a bizarrely wide-spread Lisp coding flaw that can really mess up your day. I'll revisit this issue later, since my usual fix is probably superceded by something way more slick these days. Here you can see an example of how to exploit it in 90% of the tutorials out there (mainly because they are all passively reworded copies).

# 
#### PS: I am almost nearly kidding with my rant. Lisp is surely a great language. But so far, everyone seems stuck at Eliza and the ubiquitous tutorial. I'm just as sardonic about the state of Lisp in the world as every other cynical Lisper out there. Entertain me...
