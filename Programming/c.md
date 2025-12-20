##### Inspired by [this website](https://haglobah.github.io/Mastering-42/holy_graph/cpp00-04.html)

### What is C like and when would you want to use it?

C is incredibly powerful. It is so powerful you could use it for literally anything. It is the key to all doors. However, it might not always be a good fit.

You can imagine C being like your great grandfather. You have heard many great things about him, but when you talk to him you get little out of it. You start talking with your family about him and you hear you have to talk in a very specific manner for him to understand things. This 'specific manner' is very slow and tedious. yoooouuuuu haaaaaavveeee tooooo taaaaaaalk veeeeeryyyyyy sloooooow foooooor hiiiiiiiiim toooooo uuuuuundeeeeersssstaaaaaaand. At first you are baffled how much work it is to make him say something every so slightly comprehensable. But the more you talk to him, the more he starts to show of himself. 

C has many tricks up its sleeve. But you need to do things in a very specific manner if you want it to work.

Let's say you want to store some books, not digitally but just in real life. You want to store some books in a shelf. if you (as an analogy) want to do that in C, you will have to learn how to build a shelf before you can even think about storing anything. And even then you should consider yourself lucky you don't have to chop the wood yourself (this would be writing in assembly, an even lower-level language).

So the benefits of C is you have a lot of control. You don't have to do everything yourself, but rest assured that if something goes wrong it is almost 99% sure a flaw in your design and not the language.

Like Spiderman said, with great power comes great responsibility. Writing a simple program can already become very tedious in C. You will have every bit of control over it and most likely understand exactly what is happening under the hood but it will have taken you many trips through the jungle of gdb and valgrind in order to get there. And if time is of the essence, C is probably one of the worst choices you could make.

### How does C shape the way you think?

C is at the same time horrible and excellent for writing code. When you write in C you need to know precisely what your intended end result should look like. It is almost like you have to write the program before you can think about writing the program. If you want to save yourself some time in the long run you will need to write code in a very abstract way and write many, many helper functions. In fact it is probably easier to not do this and keep helper functions specific to your specific case. This has the unfortunate side effect of reinventing the wheel over and over again for your particular use case. 

C is therefore terrible for experimenting but it does force you to think of the end result which is an amazing skill to learn. 
