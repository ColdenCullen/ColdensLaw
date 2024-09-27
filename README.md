---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: All Code is Tech Debt
description: Colden's Law
permalink: /
github.is_project_page: false
---

All code written must be maintained (and ultimately replaced).
Therefore, all engineers must do their best to not write code that does not need to be written.

## Some cases where Colden's Law applies

### 1. Dependencies

Yes, dependencies count as code, and therefore count as tech debt. [Exhibit A](https://en.wikipedia.org/wiki/Npm_left-pad_incident).

### 2. The Standard Library

You are not smarter than the authors of the STL (unless you are the author of EASTL, in which case this page does not apply to you).
You should use it unless you have a _very_ good reason not to.

## Some cases where Colden's Law does _not_ apply

### 1. Copy-Pasting Code

DRY is a great approach, right up until it isn't. If you find yourself writing a library function to consolidate 2 blocks of code that are similar but not the same, then you've created a library function with an API surface area you are now responsible for.
See [Hyrum's Law](https://www.hyrumslaw.com/) for why this is bad.

### 2. Tests

If you have ever said or thought out loud "wow all of these tests are tech debt" then I guarantee you that at some point in your career, someone you've worked with has spit in your coffee.

## Alternatively

> Red Code is Best Code

> The fastest code is the code you don't write

> No code? No bugs.

> "Delete as much code as possible, but no more" - Drew Solomon

## Who is Colden?

Nobody knows. If you figure it out, please alert the authorities.
