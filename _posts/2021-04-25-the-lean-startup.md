---
title: "Dealing with Ambiguity – The Lean Startup"
layout: posts
---

_The Lean Startup_ introduces a framework for creating something new under conditions of extreme uncertainty.
It describes how you can avoid wasting time on features that nobody wants and learn what customers _actually_ want through an iterative approach inspired by lean manufacturing. The model applies to startups in the traditional sense as well as intrapreneurship, non-profits and other groups faced with extreme uncertainty on what problems to solve and how to solve them.

In this article I share some of my favorite passages and takeaways from the book. For a general introduction I recommend a talk from the author linked in the final section.

---

> The big question of our time is not 'Can it be built?' but 'Should it be built?' (p.273)

> Customers don’t care how much time something takes to build (p.109)

> I make a habit of asking startups whenever we meet: are you making your product better? They always say yes. Then I ask: how do you know? I invariably get this answer: well, […] (p.115)

## Identify and test the critical assumptions

At the core of every startup are a series of key assumptions or beliefs on how it creates value for customers (value hypothesis) and how it acquires or retains customers (growth hypothesis). These are a primary source for uncertanity and the earlier you can identify and test them, the earlier you can make informed decisions to pivot or keep going.

> The goal of a startup is to figure out the right thing to build—the thing customers want and will pay for—as quickly as possible. (p.20)

The first step is to identify all elements in your plan that are assumptions rather than facts. Once you are clear on the key hypotheses, you can work backwards and define [actionable metrics](https://www.linkedin.com/pulse/great-results-focus-inputs-output-amit-somani/) around them. The main purpose of the [minimum viable product (MVP)](https://en.wikipedia.org/wiki/Minimum_viable_product) then becomes to establish a baseline for the metrics, which in turn enables experimentation against the baseline, iteration, and [validated learning](https://en.wikipedia.org/wiki/Validated_learning).

## How to think of WIP and batch sizes in software

Manufacturing concepts such as [work in progress (WIP)](https://en.wikipedia.org/wiki/Work_in_process) and [batch sizes](https://en.wikipedia.org/wiki/Batch_production) can be hard to conceptualize in the context of software development. WIP in a factory piles up on the floor, whereas for software it is intangible and there is no canonical definition of done.

The book offers a compelling definition: A feature or change is considered WIP until you have achieved validated learning. This generally requires you to put it in front of customers and test how it compares to the baseline, f.ex. through A/B testing. By this definition, any "internal milestone" is in fact part of a bigger batch that is still in progress. Similarly any incomplete designs, business plans, untested assumptions, etc., can all be considered WIP.

Limiting WIP and working in small batches help teams achieve validated learning faster and identify problems more quickly. Large batches tend to have the opposite effect and break down under high uncertainty.

## Avoid "Achieving Failure"

To achieve failure is to successfully execute a flawed plan. In software this can mean pouring months or years of work into building clean, extensible, highly scalable, etc., systems that nobody wants. Terms like “opportunity cost” or “throwaway effort” may come to mind, but the lean movement calls it what it is: [waste](<https://en.wikipedia.org/wiki/Muda_(Japanese_term)>).

> "There is surely nothing quite so useless as doing with great efficiency what should not be done at all."
> ―[Peter F. Drucker](https://hbr.org/1963/05/managing-for-business-effectiveness)

There are painful examples of such waste in the book, and I'm sure every software professional has some examples of their own. How can you avoid ending up in this situation? A common fallacy is to think the answer lies in more upfront planning and analysis, that it lies in further increasing the batch size. Situations of extreme ambiguity call for the opposite: [ship early, ship often](https://www.ycombinator.com/library/40-the-art-of-shipping-early-and-often).

To maximize their chances of success, builders need to balance between a "just do it" mentality and analysis paralysis: Move fast but make sure that success can be measured unambiguously. This requires extra work in some areas, f.ex. to define and collect actionable metrics, and to implement practices such as A/B testing. At the same time builders need to overcome their innate fear of releasing “low quality” products and simplify when in doubt, because everything that doesn't contribute to validated learning can be waste.

## Recommendation

I recommend _The Lean Startup_ to anybody who operates in a highly ambiguous space where neither the business problem nor the solution are well defined.

Eric's [2011 talk at Google](https://www.youtube.com/watch?v=fEvKo90qBns) (45 min plus Q&A) is a good starting point and also works as a supplement after reading the book, adding color to key examples.

---

_The Lean Startup: How Constant Innovation Creates Radically Successful Businesses, by Eric Ries. Published by Penguin Business. 320 pages. ISBN: 978-0-670-92160-7_
