### Programming Languages

* [(2020) Thriving in a crowded and changing world: C++ 2006–2020](https://dl.acm.org/doi/abs/10.1145/3386320):
  a medium-length (168 pages) retrospective on the evolution of C++ by Bjarne
  Stroustrup (creator of C++).  Title nominally says 2006-2020, but there's also
  good historical insights going all the way back to 1979.  Discusses the C++
  community and how changes make their way into the ISO standard.
* [(2020) Javascript: the first 20 years](https://dl.acm.org/doi/10.1145/3386327): a
  medium-length (189 pages) retrospective on the evolution of Javascript by
  Allen Wifs-Brock (Microsoft at the time) and Brendan Eich (creator of
  Javascript).  Covers history of how the initial language was written in 10
  days, and how it's evolved through ECMA over time.
* [(2019) Essential TypeScript](https://www.amazon.com/dp/B07WZXYTRH/):
  tutorial-style book describing the TypeScript language which "builds on the
  Javascript type system to create a safer and more productive development
  experience".  Book is heavily focused on practitioners, with follow-along code
  samples.  Also explains the ecosystem toolchain (npm, webpack, node, etc.) and
  illustrates how TypeScript can be integrated into common frameworks (Angular,
  React, Vue).

### Fonts

* [(2017) Font Rendering is Getting
  Interesting](https://aras-p.info/blog/2017/02/15/Font-Rendering-is-Getting-Interesting/):
  discusses techniques for efficiently rendering fonts at multiple scales
  (without needing high resolution textures), in the context of computer
  graphics.  The post itself is relatively brief, although contains many links
  to more details sources.

* [(2007) Improved alpha-tested magnification for vector textures and special
  effects](https://dl.acm.org/doi/10.1145/1281500.1281665): Valve paper
  describing the use of signed distance fields to efficiently represent "line
  art" images such as text/signs/UI elements in textures, in a way that scales
  well under heavy magnification.  Demonstrated in the context of text on a wall
  in a video game, where the text will get larger/smaller based on the player's
  position.

### Latency

* [(1996) Latency and the Quest for Interactivity](stuartcheshire.org/papers/LatencyQuest.pdf):
  whitepaper describing the lack of attention given to latency in computer
  modems at the time.  Includes some back-of-the-envelope calculations on where
  latency is introduced, and what latency thresholds are required for certain
  applications.  Briefly touches on latency hiding techniques.

### Domain-Specific Accelerators & Novel Computing Hardware

* [(2021) The Decline of Computers as a General Purpose
  Technology](https://cacm.acm.org/magazines/2021/3/250710-the-decline-of-computers-as-a-general-purpose-technology/fulltext):
  CACM article describing a trend away from general purpose CPUs to specialized
  processors.  Discusses the slowing rate of improvement in general purpose
  CPUs since around 1994, and slowing of virtuous cycle around universal processor
  development.  Also includes data on the dwindling number of leading-edge
  manufacturers (25 in 2003, 3 since 2017).
* [(2020) A Domain-Specific Supercomputer for Training Deep Neural Networks](https://cacm.acm.org/magazines/2020/7/245702-a-domain-specific-supercomputer-for-training-deep-neural-networks/fulltext):
  CACM article describing Google's TPU hardware architecture and supporting
  components such as compiler and bf16 float format.  Benchmarks against
  GPU-based solutions.
* [(2020) Domain-Specific Hardware Accelerators](https://cacm.acm.org/magazines/2020/7/245701-domain-specific-hardware-accelerators/fulltext):
  CACM article describing non-CPU hardware for performing fast and efficiency
  computation specific to a particular domain.  Highlights memory as a critical
  bottleneck for energy efficiency, performance, and chip area.  Claims that
  most programmers think about computational cost under the PRAM model:
  arithmetic functions and accesses to anywhere in a large global memory are all
  counted as unit-cost operations.  Points out that this model is highly
  unrealistic on modern hardware, especially GPUs.

### Effective Altruism

* [(2020) The Precipice: Existential Risk and the Future of
  Humanity](https://www.amazon.com/Precipice-Existential-Risk-Future-Humanity/dp/0316484911):
  discusses the risks of human extinction, with a particular focus on this century.
  .  Estimates the risk at 1 in 6, this century.  Concludes that anthropogenic
  (human-made) risks far outweigh natural risks.
* [(2019) Will Companies Make Good on Cage-Free
  Pledges?](https://www.openphilanthropy.org/blog/will-companies-make-good-cage-free-pledges):
  a status update on progress different companies have/have not made on their
  cage-free pledges.
* [(2017) Ending factory farming as soon as
  possible](https://80000hours.org/podcast/episodes/lewis-bollard-end-factory-farming/):
  broad discussion of animal suffering and how best to go about solving it.
  Among other things, describes how highly effective corporate campaigning has
  been per dollar spent.
* [(1975–2009) Animal Liberation](https://www.amazon.com/dp/0061711306/):
  describes the conditions of animals in factory farms, experimentation on
  animals, and makes a case for vegetarianism.

### Finance

**IRA**: Individual Retirement Account.  **Roth**: named after Senator William Roth.

| Account Type       | Tax-Free Contrib.          | Tax-Free Contrib. Withdrawal | Tax-Free Earnings Withdrawal |
| ------------------ | -------------------------- | ---------------------------- | ---------------------------- |
| Traditional 401(k) | Yes (to $19.5k limit)      | No                           | No                           |
| Roth 401(k)        | No                         | Yes                          | Yes                          |
| Traditional IRA    | Yes                        | No                           | No                           |
| Roth IRA           | No                         | Yes                          | Yes                          |
| Regular Income     | No                         | N/A                          | No                           |



* [(2019) Mad Fientist—Mega Backdoor
Roth](https://www.madfientist.com/after-tax-contributions/): 401(k) has a
pre-tax limit of $19.5k and an overall limit of $58k (2021).  Between pre-tax
and overall, it's possible to contribute as much as $58k - $19.5k = $38.5k
after-tax (assuming no company match).  The issue here is earnings on the
after-tax contribution will also be taxed upon withdrawal, making after-tax
contributions no more attractive than investing outside of retirement accounts
completely.  The mega backdoor enables shunting after-tax contributions into a
Roth IRA, where the earnings will not be taxed.
* [(2016) Investing Returns on the
  S&P500](https://github.com/zonination/investing/blob/master/README.md): a
  gallery illustrating the returns of the S&P500 over 145 years, including
  distributions of returns.
* [(2011) Mr Money Mustache—How Much is TOO MUCH in your
  401(k)?](https://www.mrmoneymustache.com/2011/11/11/how-much-is-too-much-in-your-401k/):
  401(k) withdrawals before age 59.5 incur a 10% withdrawal penalty.  Strategy 2
  and 3 in this article describe how to avoid the withdrawal penalty on a
  portion of one's 401(k) balance.
* [(1998) Retirement Savings: Choosing a Withdrawal Rate That Is
  Sustainable](https://www.aaii.com/files/pdf/6794_retirement-savings-choosing-a-withdrawal-rate-that-is-sustainable.pdf):
  a.k.a. "The Trinity Study".  This is the origin of "the 4 percent rule".
