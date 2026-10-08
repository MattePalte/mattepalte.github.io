---
layout: post
title: "Lessons from my PhD in quantum software engineering"
date: 2026-10-01
comments: false
tags: [phd, research, quantum]
published: false
---

I finished my PhD this year. When people ask me if I would do it again, my honest answer is: yes, but I would do a few things very differently. Here are the lessons that stuck.

### Pick a problem where being wrong is cheap

I work on testing quantum software. The beautiful thing about testing is that the ground truth is free: either the program crashes, or two platforms disagree, and you have a bug. Compare that to fields where "is this result good?" takes a committee and six months. If you are starting a PhD, pick a problem where reality can tell you that you are wrong quickly. Fast feedback beats brilliant ideas.

### Build the tool, don't just study the problem

My first paper was an empirical study of 223 bugs in quantum platforms. Useful, cited, fine. But nobody writes you an email about a taxonomy. People write you emails about a tool that found a bug in *their* code. LintQ, MorphQ, IterTestQ — every time I shipped something that ran on real code and found real bugs, interesting things happened: collaborations, internships, job conversations. A paper describes; a tool convinces.

### Numbers get you published. One good story gets you remembered

IterTestQ found 23 bugs across five quantum platforms, 17 confirmed or fixed. Those numbers are in the abstract because reviewers like numbers. But what I actually remember is bug #12: a platform's own optimizer silently producing a wrong circuit, caught only because we shuttled the program through a *different* platform. That single story explains the whole paper better than any table. When you write, find your bug #12 and put it on page one.

### Write the paper you wish you could read

Most papers in my field read like they were written to survive review, not to be understood. I started writing mine the other way: concrete example first, abstraction second. If a smart master's student can't follow page two, page seven doesn't matter. Reviewers are tired humans reading at midnight — clarity is a competitive advantage.

### Your advisor is a multiplier, not a manager

The best thing my advisor did was not telling me what to do. The second best thing was telling me, bluntly, when something I wrote was unclear or when an idea was too small. A PhD is the only job where your boss's main task is making *you* good. Use that. Bring drafts early, bring half-baked ideas, and don't hide the weeks where nothing worked — that's where the advice actually helps.

---

That's it. Five lessons, five years. If you're starting a PhD in software engineering — quantum or otherwise — I hope at least one of these saves you a semester. And if you disagree with all of them, even better: write your own list. :)
