---
layout:     post
comments:   true
title:      Community Bonding Period Ends
date:       2021-06-07 06:00:00
author:     Sidharth Mundhra
summary:    Work done so far and plan ahead
categories: jekyll
thumbnail:  heart
tags:
 - gsoc
 - SymPy
---

The community bonding period officially ended on June 7. During this time, I had
setup this blog and started work on my open PR [#21253](https://github.com/sympy/sympy/pull/21253).

This PR fixed leading term methods of Add and Pow in core, and also tan and cot
in trigonometric functions. Some regression tests were also added for already
fixed issues.

This PR went on for a much longer time than I had expected (~2 months), but I
learned a lot about various simplification methods of SymPy, and also now have
a clear understanding of how leading term methods fit in with series expansions.
I now have a good base to proceed with my project.

I discussed the plan ahead with my mentors, and we felt no need to change the
timeline from the proposal, so my first task would be to fix some special function
leading term methods, and add `LambertW` leading term method.

I have been contributing to SymPy for about 7 months now, so I got a headstart
on my work in the community bonding period. I have fixed the leading term methods
of `besselj` and `bessely`, and also added `LambertW` leading term method. A minor
change of making `Expr.series` call `aseries` in the case of infinities, rather than
the previous implementation of calling `series` with `1/x` instead of `x`, as
x->0, was also made.

I would be opening a PR with these changes and also zeta function leading term
methods in this week, and then move on to other special functions simultaeously
while this is being reviewed.

Overall, I would say the community bonding period went smoothly and I am ahead
of schedule currently :) Hoping to continue this streak throughout the summer!
