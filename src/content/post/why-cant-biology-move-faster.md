---
title: "why can't biology move faster?"
description: "things that sometimes frustrate me about biology research but also make it the most fun"
publishDate: "Mar 28 2025"
tags: ["metascience"]
---

## **Table of Contents**

* Long iteration cycles
  * Timescale and variability of biological processes  
  * Work culture  
  * What counts as work is different  
* Designed vs. evolved systems
* Barrier to Tinkering
* Knowledge silos
* Scaling problems  
* Risk aversion and funding models
* What I’m looking forward to
* Why I still love biology

## Introduction

I've been reading *Liftoff* by Eric Berger, which chronicles SpaceX's remarkable trajectory from a struggling startup to a revolutionary force in aerospace. What struck me most is the sheer pace at which SpaceX engineers iterated and progressed. It made me think about my field—molecular biology research—where timelines unfold at a very different pace despite equally important and urgent applications.

My perspective is shaped not just by *Liftoff* but also by living in the San Francisco Bay Area. In classes and my lab at Berkeley, I’m mostly around other molecular biologists and bioengineers. But being in the Bay Area also means absorbing Silicon Valley's startup culture by osmosis. I find myself drawn to the rapid prototyping, continuous deployment, and fast iteration of software development—so much so that I've learned web development, command-line tools, and Vim in my spare time. I love the immediate feedback in web dev (change CSS → instantly see a prettier button ✨) and the efficiency gains from using command-line interfaces and Vim. 

Moving between tech culture and biology labs shows me how different they are.

Software teams deploy features daily. SpaceX fails fast and learns faster. Biology, though, proceeds at its own deliberate pace.

So why does biological innovation follow such different rules? 

Biology is slow not from a lack of ambition, but from the inherent constraints of living systems and the long, careful journey from discovery to application.

## **Long iteration cycles** 

#### **Timescale and variability of biological processes**

What stands out most in Berger's book is the blistering pace at which SpaceX tests and implements ideas. Biological research operates in a different reality. And while a programmer can write code and see results instantly, biologists face inescapable time constraints. Cells need weeks to grow, organisms develop on their own schedules, treatments require hours or days to take effect, and multi-day experimental protocols can't be compressed without compromising results. 

Some biological processes simply refuse acceleration.

In my work, I [am impatient](https://www.benkuhn.net/impatient/) because moving fast is an advantage that compounds. If I have data on a Friday, I'll spend a few hours on the weekend coding to extract meaning from it because I can’t wait to know what the results are. This immediacy is satisfying, but it's the exception rather than the rule in biology. More typically, weeks or months separate hypothesis from validation. When an experiment fails after weeks of work, troubleshooting is extra hard: you have to figure out which of dozens of steps went wrong. And then you have to wait again, often for weeks, just to find out if your guess was right.

I value efficiency in both my work and personal systems, so I find biology’s long iteration cycles somewhat frustrating. I use Vim keybindings in Obsidian, batch-cook meals, and listen to audiobooks and podcasts while cooking[^1]. But living systems often defy these efficiency ambitions. Cells misbehave, reagents degrade, and equipment needs recalibration. The unpredictability of living systems makes optimization far more challenging in biology than in the deterministic worlds of code or engineering.

#### **Work culture**

SpaceX operates at an intensity that Berger describes as extreme even by startup standards. Musk also tries to recruit people in their 20s, who tend to have minimal outside commitments and can pour their entire lives into work.

Academic labs follow a different rhythm, but they're far from relaxed. As economist Claudia Goldin points out in [*Career and Family*](https://www.goodreads.com/book/show/57570032-career-and-family), academia qualifies as a "greedy career"—one that demands "constant cerebral output" where researchers "never tune out of work” ([source](https://doi.org/10.23941/ejpe.v15i2.668)). 

This manifests in academics, especially women, delaying parenthood until their careers are established or choosing to have fewer children altogether. Among tenured faculty, 70% of men are married with children compared to only 44% of women ([source](https://www.nytimes.com/roomfordebate/2013/07/08/should-women-delay-motherhood/what-you-need-to-know-if-youre-an-academic-and-want-to-be-a-mom)). Female academics between the ages of 35 and 50 also have fewer children on average than women in other demanding professions, such as medicine, law, and business leadership ([source](https://www.jstor.org/stable/4127651)). 

The academic system also implicitly expects constant availability from researchers. In R1 university labs at UC Berkeley and UCSF where I’ve worked, I often still see my PI and colleagues on weekends. Plenty of people [work overtime](https://link.springer.com/article/10.1007/s10734-018-0247-0) in academic labs. In this way, academia’s work culture feels closer to that of a tech startup: demanding but not quite as intense as that of SpaceX.

I suspect academia’s work culture is more moderate compared to SpaceX’s because, as mentioned above, biological processes set their own pace. When key processes simply cannot be accelerated, working around the clock offers diminishing returns. The cell culture that needs a week to grow won't mature faster if you sleep under your desk. 

The unpredictable, non-compressible timelines of biological processes create a bursty pattern of intense 50-60 hour weeks, followed by periods of 30-hour work weeks spent waiting for cells to grow and catching up on reading papers.

#### **What counts as work is different**

Reading papers counts as work for a biologist, but it doesn’t count at SpaceX, where working means producing tangible components or prototypes. In biology, the tangible equivalent is experimental data. Biologists run experiments to generate data points that can confirm or disprove hypotheses, but their work also includes spending a few hours every week reading papers. 

Reading is how researchers stay current in a field where complexity requires collective intelligence and no lab can rediscover everything independently. 

Although reading papers doesn't yield immediate, visible outputs, biologists read to build the mental frameworks they need to design experiments, discover what hasn’t been explored, find potential collaborators, and figure out how their work fits into the broader picture. 

## **Designed vs. evolved systems** 

SpaceX confronts physics—a formidable opponent, but one bound by consistent laws. Rockets, complex as they are, are engineered by humans, built from well-understood components interacting predictably.

Biological systems weren't designed, though. They're evolved, products of billions of years of random variation and natural selection. While physics and engineering operate under relatively stable laws, biology is governed by a tangled web of cellular processes, genetic expression, environmental factors, and evolutionary quirks.

Consider CRISPR-Cas9 gene editing, where editing rates can vary between experiments despite following identical protocols. Great biologists develop intuitions about why outcomes differ: perhaps differences in cell passage number, culture conditions, or guide RNA quality are responsible, or perhaps they messed up by rushing a step or keeping a sample off ice for too long. 

What looks like unpredictability in experimental outcomes often reflects variables that aren’t explicitly tracked (e.g. differences in reagent batch) or understood. 

The difficulty isn’t that biological systems seem fundamentally random. It’s that they involve more interacting variables than engineered systems, so they require a different kind of precision and observation. Biology is something of a craft, where success depends on procedural expertise that is hard to fully codify in protocols. 

This complexity makes biology both challenging and intellectually rewarding. It’s why experimental skill in biology is not just following standardized protocols but also developing an intuition for living systems built through experience, failure, and careful observation. 

## **Barrier to tinkering**

Both SpaceX and tech culture embrace tinkering—building quick prototypes, testing ideas, and learning through failure. This ethos permeates SpaceX and Silicon Valley and explains much of their innovation velocity.

Biology resists this approach. The barriers to entry for biological experimentation include:

* Equipment costs: A basic molecular biology setup (PCR machine, centrifuge, incubator, microscope) easily exceeds $50,000  
* Consumables: Reagents for a single modest experiment might cost $500-$1,000  
* Safety requirements: Proper handling of biological materials requires training and institutional oversight  
* Regulatory compliance: Research involving certain organisms or techniques requires governmental approval  
* Space requirements: Experiments need dedicated, sterile environments

These barriers create a different innovation environment. A teenager interested in coding can download free tools and start experimenting immediately. Rocket enthusiasts can join amateur clubs or build model rockets. But there's no real way to start "garage biology" in high school if you don't have access to a lab since meaningful biological experimentation typically requires institutional access and years of formal training.

The consequences extend beyond individual opportunity. High barriers to entry create a culture that's more cautious, hierarchical, and traditional. When each experiment costs thousands of dollars and takes weeks, researchers naturally favor established approaches over risky innovations. When specialized training creates steep hierarchies between senior scientists and newcomers, fresh perspectives struggle to gain traction. 

## Knowledge silos

Software development benefits from open-source ecosystems where collective intelligence accumulates and compounds. Linux, Python libraries, and GitHub repositories provide building blocks that any developer can assemble into new applications.

Biology has no comparable knowledge ecosystem. Consider these structural barriers to collective intelligence:

* Publication paywalls restrict access to key findings  
* Methods sections in papers lack sufficient detail for reliable replication  
* Tacit knowledge about techniques isn't captured in formal documentation  
* Negative results rarely get published, leading to repeated failures

The incentives in biological research also actively work against sharing:

* Competition for grants and publications actively discourages sharing preliminary results since being first to publish leads to funding and career advancement  
* No academic credit for documenting negative results or failed approaches

In biology, there is no central repository where protocols, genetic constructs, and experimental data are easily accessible, well-documented, and version-controlled. 

Without this infrastructure for collective intelligence, biology loses the compounding benefits of shared knowledge that accelerate software development.

## **Scaling problems**

SpaceX faced regulatory hurdles with the FAA, but these pale in comparison to biology's regulatory landscape. A new therapeutic follows a gauntlet of escalating tests: 

1. In vitro studies  
2. Preclinical animal studies  
3. Phase I clinical trials (safety)  
4. Phase II clinical trials (initial efficacy)  
5. Phase III clinical trials (large-scale efficacy)  
6. FDA review and approval

Each stage of this development pathway consumes years, collectively demanding a decade and approximately $900 million per approved therapeutic2. Even modest modifications to existing treatments typically require repeating substantial portions of this exhaustive process.

Fyodor Urnov's article "[Give Cas a Chance](https://www.liebertpub.com/doi/10.1089/crispr.2024.0082)" highlights an example of this regulatory inefficiency. When developing CRISPR therapeutics, changing only the guide RNA sequence—while keeping all other components identical—still requires complete recertification. This forces gene therapy companies like Beam Therapeutics and Prime Medicine to undertake separate approval processes for each variant, which dramatically multiplies costs and development timelines for what should be straightforward iterations.

The "idea → product → revenue → reinvestment" cycle that powers rapid advancement in technology becomes dramatically extended in biotech. When a breakthrough concept requires a decade-long journey to market, innovation naturally proceeds with greater caution, making fewer bets and taking smaller risks.

## **Risk aversion and funding models** 

Elon Musk investing $100 million of his personal fortune into a wildly ambitious venture with no guarantee of success made SpaceX possible. He combined technical expertise, long-term vision, and personal capital in a way that allowed SpaceX to take enormous calculated risks.

SpaceX's early success rested on a funding model that biology can't easily replicate. Developing a single successful drug typically costs around ten times SpaceX's early funding requirements. This order-of-magnitude difference transforms the innovation equation entirely. While thousands of individuals worldwide might command $100 million in investment capital, we find virtually no one who has the necessary trifecta to be biotech’s Elon Musk: billion-dollar resources they're willing to risk, comfort with extraordinary uncertainty, and sufficient scientific sophistication to evaluate unproven biological approaches. 

This capital intensity drives conservatism throughout the funding ecosystem. Venture investors naturally favor established therapeutic modalities with proven regulatory pathways over truly novel approaches—the biological risks are already so high that adding technical or regulatory uncertainty feels imprudent. Academic grant systems similarly push researchers toward incremental advances with a high likelihood of success rather than transformative but risky proposals.

The result is a funding environment misaligned with biology's potential for radical innovation. While tech and SpaceX embrace the "fail fast, fail often" approach, biology's funding structures treat failure as waste rather than learning. When each experiment costs thousands and each development program costs millions, the incentives inevitably favor cautious incremental progress over bold exploration.

Another reason funding in biology is conservative has to do with how investors see risk. Funding biotech ideas feel like placing very large bets with uncertain outcomes because we still struggle to predict how drugs will interact with biological systems. This uncertainty means biotech often gets serious money only when there's nowhere easier to invest. If interest rates are high, investors usually put their money somewhere safer. 


## **What I’m looking forward to** 

These emerging trends could change the pace of biological research: 

* **AI** (like AlphaFold and EVO) will hopefully reduce iteration cycles. Future models might simulate cellular processes before we run any experiment, focusing wet lab work on only the most promising approaches  
* 🤖 **Lab automation** increases throughput. Robotic systems can run hundreds of parallel experiments 24/7 without fatigue or variation. Despite all the talk about automation, biology labs today look and function almost the same way they did thirty years ago. We've just added fancier assay machines. The field needs serious investment of both money and talent into creating automation that works for biology's unique challenges. 
* **Open science infrastructure**. Initiatives like Addgene (for sharing DNA constructs) and [protocols.io](http://protocols.io) (for standardized methods) create the collaborative foundations biology has lacked. Organizations like Arcadia Science are pioneering new publication models that emphasize “transparency, utility, and interactivity” ([source](https://research.arcadiascience.com/reimagining-scientific-publishing))  
* **New funding approaches** are emerging that tolerate higher failure rates in exchange for breakthrough potential. The Arc Institute in Palo Alto, CA, for example, provides long-term, unrestricted funding that liberates scientists from grant cycles.

## **Why I still love biology** 

I share these reflections not as complaints, but as observations from someone who's spent 4 years in research labs and hopes to spend many, many more in them. The complexity that makes biology challenging also makes it endlessly fascinating. 

The intrinsic meaning I find in this work is unmatched by anything else. 

Biology is on the verge of something big. The convergence of computational modeling, lab automation, and open science will create unprecedented opportunities for discovery. 

The field may never move at SpaceX or software speed, but it will find its own path to accelerated progress. 

---
Thanks to Alexey Guzey for reading an early draft. Thanks to Eryney Marrogi for thoughtful feedback and Elliot Hershberg for insights into biotech funding dynamics.

[^1]: There is value in boredom / doing nothing, too. 