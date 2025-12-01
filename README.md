# You May Peek at Your Data

The Horizon Lecture at the
[Australian Statistical Conference 2025][asc2025],
given by [Damjan Vukcevic][damjan] on 1 Dec 2025.

[asc2025]: https://www.asc2025.net/
[damjan]: http://damjan.vukcevic.net/


## Abstract

Data dredging, data snooping, p-hacking. These familiar terms remind us how
easily statistical inference can be misused. The pursuit of “statistical
significance” can lead to inappropriate multiple testing and selective
reporting. One safeguard is to follow a strict pre-specified analysis plan,
waiting until all data are collected. A more flexible alternative are methods
that allow interim analyses. Taking this idea to the extreme are methods that
allow you to “peek” at your data any time at all, or even to decide to collect
more.

Such methods trace back to Wald’s sequential probability ratio test and fall
under the broader umbrella of sequential analysis. Though rarely covered in
standard curricula or applied routinely in practice, they are attracting
renewed attention as tools for “safer” statistical inference.

I will outline recent developments in this area and demonstrate how we have
used these tools to construct methods to verify the outcomes of preferential
elections through efficient post-election audits. This application poses a
high-dimensional inference problem, which we can now address in a
“stop-whenever-you-like” manner.


## Licence

[![Creative Commons License][cc-img]][cc]  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc].

[cc]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-img]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
