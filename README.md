# Mave Media

I build and run my own websites. Everything here is solo work: Python data
pipelines, WordPress, MySQL, and the SEO that holds it together.

## Projects

### [Parkzie](https://parkzie.com)
Comparison site for Dutch holiday parks. Trilingual (nl/de/en), with over
3,000 accommodations imported daily from eleven affiliate XML feeds and
merged into one page per park.

What happens when one of those feeds silently changes shape: [My pipeline ran green for 8 days while importing nothing](https://dev.to/mavemedia/my-pipeline-ran-green-for-8-days-while-importing-nothing-mec).

### [Skizie](https://skizie.com)
Comparison site for winter sports chalets and apartments in the Alps. Weekly
prices including ski pass for over 1,000 accommodations, rebuilt every
morning, with open price research on top: which weeks are cheapest, how much
more the school holidays cost, and which ski areas give the most slopes per
euro. See [when winter sports is cheapest](https://skizie.com/wintersport-goedkoopst/).

The underlying data is published as an open dataset: [wintersport-prijzen](https://github.com/mavemedia/wintersport-prijzen).

### [Daily Sport Pick](https://dailysportpick.com)
Football predictions from a model ensemble (gradient boosting, Poisson,
Dixon-Coles), published daily with settlement tracked against results.

### [Welke Online Datingsite](https://www.welkeonlinedatingsite.nl)
Comparison of Dutch dating platforms.

## Writing

I write up the things that break, mostly about feed parsing, silent failures, and numbers
that look right and aren't: the distance between "the script finished" and "the script worked".

* [February looked 59% more expensive than March. It was 40%.](https://dev.to/mavemedia/february-looked-59-more-expensive-than-march-it-was-40-2b2)
* [My pipeline ran green for 8 days while importing nothing](https://dev.to/mavemedia/my-pipeline-ran-green-for-8-days-while-importing-nothing-mec)

More at [dev.to/mavemedia](https://dev.to/mavemedia).

## Stack

Python, MySQL, WordPress, nginx, Ubuntu. Cron for everything that repeats.

---

Mave Media, Netherlands. [mave-media.nl](https://mave-media.nl)
