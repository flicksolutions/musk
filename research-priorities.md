# Optimizing AI’s Economic Impact

Hier finden sich vorallem 2 Paper die Gefahren aufzeigen. Es geht dabei vor allem darum, dass dem Grossteil der Gesellschaft die Arbeitslosigkeit droht.

## Mokyr, J. 2014. Secular Stagnation? Not in Your Life.

[GDP ist falsches Messinstrument]: Why the gloominess of my colleagues? Part of the story is that economists are trained to look at aggregate statistics like GDP per capita and its derivatives such as factor productivity. These measures were designed for a steel-and-wheat economy, not one in which information and data are the most dynamic sector. Many of the new goods and services are expensive to design, but once they work, they can be copied at very low or zero costs. That means they tend to contribute little to measured output even if their impact on consumer welfare is very large. Dealing with altogether new goods and services was not what these numbers were designed for, despite the heroic efforts by BLS statisticians. The aggregative statistics miss much of what is interesting.

[Job loss]: Another characteristic of many of these goods is the ‘dumbing-down’ of the user; the ingenuity in a piece of modern technology such as a smartphone is fully frontloaded. A few thousand highly skilled and creative hardware engineers and a few tens of thousand software and application writers design it with incredible technical sophistication, so that hundreds of millions can use it without any. For that reason, there are few jobs in the high-technology sector, but those that are there pay well. Modern technology often leads to winner-take-all outcomes, and the inequality implications in terms of income – though not in terms of access to the good itself – are worrisome. What we gain as consumers, citizens, viewers and patients we may lose as workers. The demand for labour ‘hollows out’ and the demand for medium-skilled labour declines unless and until new jobs are created to absorb those replaced by automatons and robots.
It is impossible to know if such jobs will be created at a sufficient pace.

## The Second Machine Age: Work, Progress and Prosperity in a Time of Brilliant Technologies

[Power Law / Ersetzung]: Call it talent-biased technical change. In many industries, the difference in payout between number one and second-best has widened into a canyon. (...) Suddenly the top-quality provider can capture the whole market. The next-best provider might be almost as good, but it will not matter. Each time a market becomes more digital, these winner-take-all economics become a little more compelling.
A shift in the distribution of income to a power-law distribution would have important implications. For instance, Kim Taipale, founder of the Stilwell Center for Advanced Studies in Science and Technology Policy, has argued that, “The era of bell curve distributions that supported a bulging social middle class is over and we are headed for the power-law distribution of economic opportunities. Education per se is not going to make up the difference.”26 Such a shift disrupts our mental models for understanding the world. Most of us are used to reasoning by reference to a prototypical. Politicians talk about the “average voter” and marketing managers talk about the “typical consumer.”
Today the employment-to-population ratio is lower than any time in at least 20 years, and the real income of the median worker is lower today than in the 1990s. Meanwhile, like productivity, GDP, corporate investment, and after-tax profits are also at record highs.
That many Americans face stagnant and falling incomes is bad enough, but it is now combined with decreasing social mobility—an ever lower chance that children born at the bottom end of the spread will escape their circumstances and move upward throughout their lives and careers. Recent research makes it clear that the American Dream of upward mobility, which was real in earlier generations, is greatly diminished today.
(...) that productivity somehow inevitably leads to job creation, as technology boosters sometimes argue. However, as we saw in figure 11.1, the data also show that, more recently, job growth decoupled from productivity in the late 1990s.
The better machines can substitute for human workers, the more likely it is that they’ll drive down the wages of humans with similar skills. The lesson from economics and business strategy is that you don’t want to compete against close substitutes, especially if they have a cost advantage.  [@brynjolfssonSecondMachineAge2014, chap. 10 ]

## Disruptive technologies: Advances that will transform life, business, and the global economy

[Disruptive technologies]: The benefits of the mobile Internet and cloud computing are accompanied by rising risks of security and privacy breaches. Objects and machines under the control of computers across the Web (the Internet of Things) can also be hacked, exposing factories, refineries, supply chains, power plants, and transportation networks to new risks. Next-generation genomics has the potential to grant new powers over biology, but these powers could be abused to disastrous effect. Low-cost desktop gene-sequencing machines will not only put the power of genomics in doctor offices, but also potentially in the hands of terrorists. Even well-intentioned experiments in garages using inexpensive sequencing and DNA synthesis equipment could result in the production and release of dangerous organisms. And nanomaterials offer great promise, but more research will be required to fully ascertain their potential impact on health. It will be up to business leaders, policy makers, and societies to weigh these risks and navigate a path that maximizes the value of these technologies while avoiding their dangers.

# Computer Science Research for Robust AI

[Robustheit]: AI ist nicht robust und deshalb nicht sicher [@russellResearchPrioritiesRobust2015, p. 107]
[Verifikation]: Ganze AI-Agents sind nicht formal verifizierbar: 
we lack the formal algebra to properly define, explore,
and rank the space of designs.
Perhaps the most salient difference between verification
of traditional software and verification of AI systems
is that the correctness of traditional software is
defined with respect to a fixed and known machine
model, whereas AI systems — especially robots and
other embodied systems — operate in environments
that are at best partially known by the system designer. [@russellResearchPrioritiesRobust2015, p. 108]
Das Ganze gestaltet sich noch schwerer bei AI die learning Algorithmen anwendet.

[Validity]: Unsere Anforderungen an die AI können falsch formuliert sein und so könnten sich AI-Agents unpassend verhalten.
> Such specification errors are ubiquitous in software
> verification, where it is commonly observed that
> writing correct specifications can be harder than writing
> correct code. Unfortunately, it is not possible to
> verify the specification: the notions of beneficial and
> desirable are not separately made formal, so one cannot
straightforwardly prove that satisfying ψ necessarily
leads to desirable behavior and a beneficial
agent.
 [@russellResearchPrioritiesRobust2015, p. 108]
 
 [moral decisions sind notwendig]:
> But today’s systems are approaching a level of complexity that, we argue, requires the systems themselves to make moral decisions—to be programmed with “ethical subroutines,” to borrow a phrase from Star Trek.
[@wallachMoralMachinesTeaching2008, p. 4]

[Vorteile verhindern Moratorium]:
> However, it is not often possible to predict accurately the impact of a new technology on society until well after it has been widely adopted. Some critics think, therefore, that humans should err on the side of caution and relinquish the development of potentially dangerous technologies. We believe, however, that market and political forces will prevail and will demand the benefits that these technologies can provide. Thus, it introduction 7 is incumbent on anyone with a stake in this technology to address head-on the task of implementing moral decision making in computers, robots, and virtual “bots” within computer networks.
> — [@wallachMoralMachinesTeaching2008, p. 6]

[Abtreten von moralischen Entscheidungen]: 
>Some concerns, for example whether AMAs will lead humans to abrogate responsibility
to machines, seem particularly pressing.
> — [@wallachMoralMachinesTeaching2008, p. 9] & [@wallachMoralMachinesTeaching2008, chap. 3]

[Cyberattacken]:
> As AI systems are used in an increasing number of critical roles, they will take up an increasing proportion of cyberattack surface area. It is also probable that AI and machine-learning techniques will themselves be used in cyberattacks.
>(...)It is not implausible that cyberattack between states and private actors will be a risk factor for harm from near-future AI systems, motivating research on preventing harmful events.
> — [@russellResearchPrioritiesRobust2015, p. 109]
