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

### Programming Concepts

* [Futures and Promises](http://dist-prog-book.com/chapter/2/futures.html):
  discusses the history of futures/promises going back many decades across a
  number of different programming languages.  Compares/contrasts the APIs
  provided by these different languages, and also discusses different execution
  models.
* [Semaphores and Condition
  Variables](https://cseweb.ucsd.edu/classes/sp17/cse120-a/applications/ln/lecture7.html): one of the
  better explantions/comparisons I've found online.  If you know of a better one
  please let me know.

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

#### Account Type Summary

**IRA**: Individual Retirement Account.  **Roth**: named after Senator William Roth.

| Account Type       | Tax-Free Contrib.          | Tax-Free Contrib. Withdrawal | Tax-Free Earnings Withdrawal |
| ------------------ | -------------------------- | ---------------------------- | ---------------------------- |
| Traditional 401(k) | Yes (to $19.5k limit)      | No                           | No                           |
| Roth 401(k)        | No                         | Yes                          | Yes                          |
| Traditional IRA    | Yes                        | No                           | No                           |
| Roth IRA           | No                         | Yes                          | Yes                          |
| Regular Income     | No                         | N/A                          | No                           |

#### Articles

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
* [(2021) Fuel for the F.I.R.E: Updating the 4% rule for early
  retirees](https://personal.vanguard.com/pdf/ISGFIRE.pdf): white paper
  discussing the 4 percent rule in the context of the F.I.R.E movement.
  Compares the 30-year time horizon of the original "trinity study" to the
  perhaps 50-year time horizon implied by F.I.R.E.  Discusses various
  assumptions and risks in the original trinity study.  Take this paper with a
  grain of salt.  The most surprising assumption is forecasted future returns
  that are far lower than historical returns, based off the Vanguard Capital
  Markets Model - a "proprietary financial simulation tool".

#### 401(k) Limits (2023, under 50 years of age)

$22.5k pre-tax, and an overall limit of $66k.  Between pre-tax and overall,
it's possible to contribute as much as $66k - $22.5k = 43.5k after-tax (assuming
no company match).

#### 401(k) Company Match Example (2023, under 50 years of age)

Assume company matches $1 for $1 up to 50% of IRS pre-tax limit.  In 2023, this
would be a company contribution of 0.5 * $22.5k = $11.25k.

* Company match **does not** contribute to the pre-tax limit.  i.e. individual
  can contribute $22.5k pre-tax plus get company $11.25k pre-tax for a total
  pre-tax of $33.75k.
* Company match **does** contribute to overall limit.  So after-tax
  contributions would be limited to $66k - $33.75k = $32.75k.

#### Social Security in Retirement

##### Qualifying for Social Security

To qualify at all, one needs ~10 years of cumulative work in the US.  It's based
on a "credit" system.  40 credits are needed to qualify for social security, and
you can earn at most 4 credits per year.  In 2023, every $1,640 earned in a year
earns 1 credit, up to a 4-credit per-year maximum
([source](https://www.ssa.gov/benefits/retirement/planner/credits.html)).

##### Maximizing Social Security

How much you're paid in social security is determined by your highest-earning 35
years of your career.  If you have less than 35 years, the value "0" is
substituted for each missing year.  There is a maximum social security tax each
year.  For example, in 2023, income up to $160,200 is taxable at a 6.2%
employee + 6.2% employer rate for a maximum tax of 160,200 * (0.062 * 2) =
$19,864.80 (employee paying half of that).  If you meet this maximum in a year,
then that maximizes that particular year's contribution (out of 35 years)
towards maximizing the overall benefit.  If you have at least 35 years that
reach this maximum tax contribution, then you can also maximize the social
security payout during retirement.

The specifics of how these calculations work can be found in [part 1 of Benefit
Calculation Examples for Workers Retiring in
2023](https://www.ssa.gov/oact/ProgData/retirebenefit1.html). Old year's
earnings are adjusted to bring nominal earnings up to near-current wage levels.
Based on taking the highest 35 years, an Average Indexed Monthly Earnings (AIME)
is calculated.  The AIME in turn is used to calculate the Primary Insurance
Amount (PIA), which is the the name for the main social security benefit.  See
[part 2 of Benefit Calculation Examples for Workers Retiring in
2023](https://www.ssa.gov/oact/ProgData/retirebenefit2.html). for an explanation
of how AIME feeds into the PIA calculation.

In 2023, here is the tl;dr on the maximum monthly benefit
([source](https://faq.ssa.gov/en-us/Topic/article/KA-01897)):

1. If you retire at "full retirement age" a.k.a. [Normal Retirement Age
   (NRA)](https://www.ssa.gov/oact/ProgData/retirebenefit2.html), which is
   currently 67 years for those born after 1960, then the maximum benefit is
   $3,627/mo = $43,524/annum.
2. If you retire at age 62 (earliest possible), the maximum benefit is $2,572/mo
   = $30,864.
3. Age 70 produces the highest ratio of retirement benefit to AIME ratio
   (i.e. retiring later doesn't improve things).  If you retire at age 70, the
   maximum benefit is $4,555/mo = $54,660/annum.

If one is concerned with maximizing benefits, there is a tradeoff to consider in
returing earlier vs later.  Earlier means less money per year, but some money in
more years.  Later means more money per year, but no money in some years.

##### Cost Of Living Adjustment (COLA)

A Cost Of Living Adjustment
([COLA](https://www.ssa.gov/oact/COLA/colaapplic.html)) is applied to social
security payments each year. For 2019 through 2022, the COLAs were 1.6%, 1.3%,
5.9%, and 8.7% respectively.

##### Social Security Trust Fund is Running Out of Money

Primarily due to lower birth rates, and secondarily due to increases in life
expectancy, the fund in projected to only remain solvent until 2035 unless
something is changed ([source](https://sgp.fas.org/crs/misc/IF10522.pdf)).
Quoting that article under the heading "What Can Be Done to Restore Balance?":

> Some of the more commonly discussed proposals
> include increasing the amount of covered earnings subject
> to the payroll tax (the taxable wage base), increasing the
> payroll tax rate, raising the retirement age, modifying the
> benefit formula, and changing the annual cost-of-living
> adjustment (COLA) calculation.
