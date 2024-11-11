### Programming Languages

* [(2022) Practically Correct, Just-in-Time Shell Script
  Parallelization](https://www.usenix.org/conference/osdi22/presentation/kallas):
  describes a just-in-time shell-script compiler (PaSh-JIT) that can offer
  significant speedups when parallelization is possible.  Unlike reworking a
  script to be explicitly parallel using commands like `parallel`, PaSh-JIT is
  designed to be a drop-in replacement.
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
| Traditional 401(k) | Yes (to $23k limit)        | No                           | No                           |
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

#### 401(k) Limits (2024, under 50 years of age)

$23k pre-tax, and an overall limit of $69k.  Between pre-tax and overall,
it's possible to contribute as much as $69k - $23k = 46k after-tax (assuming
no company match).

#### 401(k) Company Match Example (2024, under 50 years of age)

Assume company matches $1 for $1 up to 50% of IRS pre-tax limit.  In 2024, this
would be a company contribution of 0.5 * $23k = $11.5k.

* Company match **does not** contribute to the pre-tax limit.  i.e. individual
  can contribute $23k pre-tax plus get company $11.5k pre-tax for a total
  pre-tax of $34.5k.
* Company match **does** contribute to overall limit.  So after-tax
  contributions would be limited to $69k - $34.5k = $34.5k.

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
2023](https://www.ssa.gov/oact/ProgData/retirebenefit2.html) for an explanation
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

##### Payments are A Non-Linear Function of AIME

Note that per [Primary Insurance
Amount](https://www.ssa.gov/oact/ProgData/retirebenefit2.html), the retirement
amount does not grow linearly with AIME.  There are "bend points", where the
payout has diminishing returns with increasing AIME.  E.g. 90% of the first
$926 of AIME, 32% of the next ($5,583 - $926) of AIME, and 15% of the the next
($10,503 - $5,583) of AIME.

As an example, assume one worked only 10 years between 2013--2022 inclusive, at
maximum contribution during those 10 years (e.g. $150,000 each year).  Their
AIME would thus be `MAX_AIME` / 3.5 (10 years out of 35).  But the benefit would
still be more than 1/3.5th (28%) of the maximum.  This example can be input into
the [Online Benefits
Calculator](https://www.ssa.gov/benefits/retirement/planner/AnypiaApplet.html),
with a retirement age of 70 years, and shows an estimated montly retirement
benefit of $2,213/mo = $26,556.  This is 48% (not 28%) of the $4,555/mo number
quoted earlier.

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

#### Mortgage Tax Deductions

Interest paid on the first $750,000 of a mortgage can be deducted from taxable
income (married filing jointly).  E.g. imagine a home bought for $937,500 with a
20% downpayment of $187,500, and thus a $750,000 mortgage.  Assume an interest
rate of 7%, for an annual interest payment of $750,000 * 0.07 = $52,500.  To
maximize deduction in this example, assume highest possible tax rate of 37%.  In
this scenario, taxable income can be reduced by $52,500 * 0.37 = $19,425.

##### Compared to the Standard Deduction

In 2025 the standard deduction for married filing jointly is $30,000.  In other
words, taking the mortgage tax deduction yields an improvement of $52,500 -
$30,000 = $22,500 in money that can be deducted from taxable income.  Expressed
as an absolute tax saving, this is $22,500 * 0.37 = $8,325 over taking the
standard deduction.

##### Attenuating Factors

* The above example assumes the deduction is all coming from the highest tax
  bracket: 37% for income over $751,601 for married filing jointly in 2025.  In
  other words, the maximum $8,325 tax saving cited above is only realized on a
  taxable income of $751,601 + $52,500 = $804,101 or more. Measured against
  lower brackets the deduction will be worth less.
* The Standard Deduction tends to increase over time, which should make it
  increasingly attractive relative to the mortgage tax deduction as the years
  go by.

##### Amplifying Factors

If mortgage interest rates were higher than the 7% quoted above.

##### 2017 Changes with the Tax Cuts and Jobs Act

Everything above is post-December 16, 2017.  Prior to this date, you could
deduct interest on the first $1 million of the loan.  That was revised in the
Tax Cuts and Jobs Act of 2017, down to $750,000.  The standard deduction was
also substantially increased in the Tax Cuts and Jobs Act.  These two factors
combined made the mortgage tax deduction less attractive, with the Tax Policy
Center estimating that the number of taxpayers who take the mortage-interest
deduction will fall from [34 million (20% of returns) in tax year 2017 to 14
million (8% of returns) in
2018](https://www.brookings.edu/articles/chipping-away-at-the-mortgage-deduction/).

#### Taxation Underpayment Penalty

In addition to always owing underpaid taxes, a penalty is charged on tax
underpayments unless either:

1. `>= 90%` of owed taxes were paid.
2. `>= 110%` of tax owed on the prior year's return has already been paid on
   this year's return (`>= 100%` if AGI was `<= $150,000`).

A meaningful enough lift in income year-over-year will tend to exempt a person
from paying the penalty under the 110% rule described above.  E.g. if they paid
$10k in taxes in the prior year, and $11k in taxes in the subsequent year, they
would not be charged a penalty, even if their total tax bill was something much
larger like $100k. i.e. $89k would be owed, but no additional penalty
([source](https://turbotax.intuit.com/tax-tips/small-business-taxes/estimated-taxes-how-to-determine-what-to-pay-and-when/L3OPIbJNw#:~:text=you%20will%20have%20to%20pay%20in%20110%20percent%20of%20your%20previous%20year%27s%20taxes%20to%20satisfy%20the%20%22safe%2Dharbor%22%20requirement.%20If%20you%20satisfy%20this%20test%2C%20you%20won%27t%20have%20to%20pay%20an%20estimated%20tax%20penalty%2C%20no%20matter%20how%20much%20tax%20you%20owe%20with%20your%20tax%20return.)).
In 2023 this penalty is higher than in the recent past due to higher interest
rates; it [is now
7%](https://www.forbes.com/sites/nataliecolley/2023/07/29/selling-employer-stock-in-2023-beware-of-steep-irs-tax-penalties/).

Note: there are some less common penalty exemptions other than 1 and 2 mentioned
above, which aren't covered here.

#### Checking Accounts vs. Savings Accounts and Regulation D

On April 24th, 2020 [the Federal Reserve amended Regulation
D](https://www.govinfo.gov/content/pkg/FR-2020-04-28/pdf/2020-09044.pdf) by
removing the "six convenient transactions per month" limit on savings accounts.
This was partly in response to COVID-19 to give depositors better access to
their savings.  Following the suspension, banks were *allowed* but no longer
*required* to enforce the six transaction limit.  Some banks continued to
enforce the rule, while others did not.

Savings accounts tend to earn higher interest than checking accounts.  The
removal of the six convenient transaction limit makes savings account more
attractive to use *like* a checking account.  For example, have employment wages
deposit into a savings account rather than a checking account, and setup auto
payments for credit card bills and other expenses from the savings account
([discussion](https://www.cbsnews.com/news/maximize-your-savings-account-with-this-one-feature-experts-say/)).

At time of writing, the Federal Reserve has no concrete plans to bring back the
six transaction limit,
[stating](https://www.federalreserve.gov/supervisionreg/savings-deposits-frequently-asked-questions.htm):

> The Board does not have plans to re-impose transfer limits but may make
> adjustments to the definition of savings accounts in response to comments
> received on the Board’s interim final rule and, in the future, if conditions
> warrant.
