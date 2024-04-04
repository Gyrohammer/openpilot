# SP Build to fix Low Speed Error on newer VW EPS Systems

I've been wanting to try SunnyPilot (SP) for quite some time, but have been unable to due to some EPS faults. The error in particular is [#30495](https://github.com/commaai/openpilot/issues/30495), the pull request to fix it is, [#31450](https://github.com/commaai/openpilot/pull/31450). I understand that development takes time, so after waiting about a month with little activity I decided to create my own fork and implement the required changes. 

## How does it drive? Does it work? 

Yes! I've driven two days of normal routes, with stops starts and everything in between with zero issue. No errors or strange behaviour what-so-ever. 

### Installation
If you'd like to install this branch, use the following URL in your C3X:

``` https://smiskol.com/fork/Gyrohammer/dev-c3 ```

Shortened Link:

``` https://ishortn.ink/Wb8wHCb ``` [^1]

## Future
I lack the skills to continue to update this, so this will be a one-off unless any major changes occur. If it needs to be updated I'll sync with the main branch and make the adjustments again. I wont be doing anything custom, save for this fix.

[^1]: I'm unsure as to how long this shortened link will stay 'alive'. If it doesnt work use the long link.
