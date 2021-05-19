---
layout:     post
comments:   true
title:      GSoC Acceptance
date:       2021-05-18 06:00:00
author:     Sidharth Mundhra
summary:    GSoC '21 with SymPy!
categories: jekyll
thumbnail:  heart
tags:
 - gsoc
 - sympy
---

So, the results are finally out. My project proposal has been selected for GSoC '21,
and I will be spending my summer with SymPy!

![Thumper](https://i.imgur.com/jYY26JT.png)

I cannot wait to get started with the project! Here is my project in brief -

The current implementation of series expansions in SymPy is developed to a large extent, but not complete. There are a few limit failures that need to be addressed, for which the series module is the backbone. This project aims to fix the computation of leading term methods and make them more robust, which will fix many outstanding issues. This project will also add series and asymptotic expansions support to all special functions, and fix some long standing issues with AccumulationBounds and Order terms.

You can find my full Project Proposal [here](https://drive.google.com/file/d/1Ce7PGHu-9YRRf06aHHqcaPPJQU_N5Sp4/view?usp=sharing)

I will also be adding blog posts about my journey so far soon!

{% if page.comments %}

<div id="disqus_thread"></div>
<script>
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://0sidharth-github-io.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

{% endif %}

[1]: http://www.github.com/sympy
