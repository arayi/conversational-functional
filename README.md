# Intro
## Welcome
Hi, I'm Ara, and I'm a lot of things: female-bodied, queer, autistic, a [gamer](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=0ahUKEwie5v6tsOPRAhXJwVQKHVNsCsgQyCkIHzAA&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DAjmJCy1ksYY&usg=AFQjCNGmFzoWKGXuA0WN_KyuNu7BMm0zkQ&sig2=Cfb1HHlebXM8j_4rJf7f7g), a middle school dropout and self-taught web-developer-turned-software-engineer, and part of the last generation of outcast nerds. :]

I love code because it allows us, as human beings, to specifically direct information processing in a much more detailed way than most of us can do with our minds. We've modeled the computers after us; they're "thinking" about the same things. We simply use them to outsource our own processing.

So, surprisingly, we can learn a lot about communicating with computers from human behavior, and vice versa. I find computers intuitive and humans only barely so; I'd like to think I'm in a unique position to translate. I am not remotely joking about this. I might secretly be an AI. Ok, now I'm joking. Do you get it, human?

But seriously, my goal in writing this is not just to make it possible for newbies to understand my favorite paradigm. It's also to allude to the potential that will arise once we use machine learning to create a truly universal human-computer API. The singularity doesn't look a damn thing like the sci-fi movies.

## Who is this tutorial for?
This work aims to be a practical introduction to functional programming concepts for the average web developer with a basic command of how to use JavaScript, but maybe a little confusion about what goes on under the hood. We'll be using Node.js and ES6 in the simplest configuration possible: just running files from the terminal.

I'd feel remiss if I didn't mention that you should probably practice TDD in general, but this tutorial isn't about getting right answers or getting tests to pass. It's about playing with code so that we understand it better.

If you're having trouble, try changing and breaking the code. You can always `git reset --hard HEAD` if you need to start from the beginning again. If you see a concept or phrase you don't understand, don't forget that you can always just google it.

And, because you deserve to hear it: I love you, and you're a good developer. <3

## Why learn functional programming?

First, the concepts involved will help you be a better programmer no matter what language or paradigm you use. Programming is a unique field in that it involves such a multitude of different implementations of the same concepts and logic in different ways. Each language really is a language, just like Spanish, Korean, or that weird, unintelligible shit that twins say. (Okay, so the last one might not be Turing-complete. I can't tell.)

Anyway, that makes the job of the programmer one of translation.

See, coding isn't some special, super-technical, complicated thing. It uses the same concepts as any other language, and it's made for communication! The difference is, once we get a few levels above assembly, these languages are designed for communicating with both humans AND computers.

Second, the further you get into functional programming, the more you gain the habit of separating the things themselves (data) from the relationships between the things (functions). To see how this is a good thing, we don't even need to look at programming. Just think about the last time your best friend said something angry to you when she was frustrated about something else in her life. You knew not to take it personally, because the action she was performing had nothing to do with you; you just happened to be there.

In coding terms, you were passed as an argument to her frustration-handling function, and that function DID NOT change (or mutate) her concept of you as a person. And it's definitely a good thing that you're both interacting functionally, because not only do you know not to take it personally, SHE also knows that you're not an inherent part of her frustration. It will pass (its return value into the next function she uses to interact with the world).

Yeah, the language starts to blur a little there. See how you weren't sure which definition of "functional" I was using in "interacting functionally?"

Imagine, then, what happens when you're interacting with your worst enemy. They're probably doing the opposite of your best friend. Not only is it personal (mutable data), but they're gonna hold a grudge (maintaining state).

This is also reflected in the religious concept of detachment, but I'm not gonna go there right now. I'm a programmer, not the Pope. Anyway, the point is, if you scale the functional version, you get community. If you scale the non-functional version, you get war. It kinda works like that in programming, too: functional code is particularly scalable and maintainable.

Third, functional programming can be a highly intuitive way of developing programs written in natural language. Yeah, yeah, I get it, FP sounds all scary and math-y and academic and stuff the way most people write about it. But I've personally found that it's an incredibly powerful way of iteratively building grammar from root words and concepts in order to improve readability and make it supremely easy for other devs (or yourself in n months) to contribute. And I'm gonna teach you how, with nothing more than a paper clip and a small twig! Or, uh, an `{}` and a `() => {}`, hah.

***FUTURE SECTIONS***
# The Basics (Minus the Pumpkin Spice)
## Everything in JavaScript is an Object
## Functions are people...er, I mean Objects, too!
## Seriously, I mean EVERYTHING, even that variable
## Shut the front door: what the what is a closure?
## An excursion into recursion that won't make you curse
## Functionception, or functions all the way down

# Curried Vegetables Are Delicious

# Composing Beautiful Functional Music

# Map, Reduce, and Filter

# Monads

# Appendix: Toybox
