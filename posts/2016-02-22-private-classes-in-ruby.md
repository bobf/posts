---
created_at: 2016-02-22 11:49:07 +0100
publish: true
author: Robert Pankowecki
tags: [ 'ruby', 'private', 'class' ]
newsletter: clean
---

# Private classes in Ruby

One of the most common way to make some part of your code more understandable and explicit is to extract a class.
However, many times this class is **not intended for public usage**. It's an implementation detail of a bigger
unit. It should not be used be anyone else but the module in which it is defined.

So how do we hide such class
so that others are not tempted to use it? So that it is clear that it is an **implementation detail**? You don't! That's a stupid idea anyway.
