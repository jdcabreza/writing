---
title: "Some Code-Level Lessons Over The Years"
date_created: 2025-05-13
---

# Some Code-Level Lessons Over The Years

I'm still relatively new to software engineering (a bit short of 4YOE at the time of writing), but I've learned some lessons over the years that have stuck. These lessons aren't focused on syntax and whatnot, it's more generally about how I now write code. 

Some of these I've learned from just being in the trenches, some from amazing developers, and others from various resources (podcasts and books, usually. Reddit too.)

## 1. Your Code isn't for You

"Code is read more than it is written" is a common adage in the field for good reason. Whenever you write code, it's always best to assume that other people will either read and/or use it. This is most obvious at work --- you're probably in a team that works together on shared codebases. Therefore, it's in your best interest to make your code as clean as possible (unless you want your teammates to be cursing you under their breath when they see your code).

Writing clean code doesn't just affect time to understand, it also directly impacts how often your code breaks and how fast it is to fix. If you write clean code, it's usually easy to see where bugs can pop up and you can prepare for them in advance. If you're writing obscure, complex code, then it becomes harder to spot where things can go wrong (especially if you yourself don't fully understand the implications of your code).

Of course, apply this within reason. If you just need a one-off hacky script, then it's probably fine to just throw things together. If you're coding a service to be used by hundreds to thousands (or even millions) of people, well, maybe think twice about what you're writing. 

## 2. Things Almost Always Change

Requirements change, people change, even the business itself can change. Therefore, your code must also change. One big takeaway I got from the [Pragmatic Programmer book](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/) is that code should be easy to change. This encompasses a lot of other usually talked about principles like DRY, YAGNI, KISS, etc. and I think it does a good job of doing so too.

If you're just starting out in the software engineering realm, then you probably might find that you yourself change quickly in terms of the code you write. At least, that was the case for me. Whenever I used to look at code I wrote 3, 6 months ago I just cringe. It's a bit better nowadays given that I know more now, but it still happens at times.

In a more practical sense, a lot of work in software engineering is adapting to change. If we initially had wrong assumptions, well, we're going to need to change this part of the codebase then. Leadership now wants a different feature? That's more things to change in your code. Following the "easy-to-change" idea is going to make your life so much easier down the line (and it'll probably help keep you sane too).

## 3. Code is Not The Product

Unless you're running an open source, build-it-yourself thing, then you're shipping a product that creates value. Your code is just a means to an end --- it doesn't have to be perfect, it just has to be good enough.

There isn't a universal definition for "good enough". In a startup where everyone is scrambling to get a product out, good enough can be a scrappy MVP. In a larger enterprise, good enough might mean fully-tested and following known conventions.

This was another painful lesson that I've come to learn. If your code doesn't generate value, then it's practically useless. All that mattered to me when I first started was technical excellence. Make code run fast, make it look nice. Eventually, that led me to a lot of effort that didn't do me or the business any good --- it was practically useless.

There is value in the pursuit of technical perfection, but we're not here to do that. You're there to create value for your company and your code doesn't have to be shining and shimmering. It just has to be, well, good enough.

## Coding Isn't Everything

People often think that all software engineers do is write code all day, but that isn't exactly true. The real work is in the conversations, the design documents, and the alignments you have with people who may not even write code at all.

It takes a village to ship anything meaningful. There are so many people to consider --- PMs, designers, QAs, infra, leadership, and, of course, other engineers. We're all (hopefully) collaborating to solve real problems and to, eventually, get something out there.

Good engineers can code, yes. Great engineers, though, they're also good at communicating and coordinating with others. That's what actually makes the code we write matter in the end.
