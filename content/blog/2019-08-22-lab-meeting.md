---
title: "Lab Meeting on 22 August 2019"
date: 2019-08-22T00:00:00+00:00
draft: false
authors: ["kirstiewhitaker"]
categories: blog
tags: [lab-meeting]
---

There were SO many great questions and conversations at this week's lab meeting that we ran over time and ended up chatting for more than 2 hours.

There are lots of updates here, and some really fascinating questions that we didn't manage to answer, but please do scroll to the end to see a few of Ruslan Yermakov's excellent brain visualisations for the `scona`🍪 (Structural Covariance Network Analyses) project ([https://github.com/WhitakerLab/scona](https://github.com/WhitakerLab/scona)).

## Celebrations and cool things to share

**Patricia** is starting a new job in September and her new team is running a survey on FAIR data policies and practices.
It would be great for everyone to complete it and share widely!
* [https://www.fairsfair.eu/fairsfair-open-consultation-fair-data-policies-and-practices](https://www.fairsfair.eu/fairsfair-open-consultation-fair-data-policies-and-practices)

**Maxine** is back on track with thesis writing after a rough few weeks of re-running _all_ of her analyses because there was a mistake at the very start 😱
This week she's writing new analyses (rather than re-writing the chapters that had to be updated).
Kirstie is wildly proud that a whole PhD can be re-run in just a few weeks!
Reproducible research FTW ✨ 🙌 🚀 😻

In contrast, **Josh** has been busy incorporating feedback for his thesis _proposal_.
He also took a break from his PhD by writing a blog on [Four things I wish I'd known before starting a PhD](https://medium.com/josh-cowls/four-things-i-wish-id-known-before-starting-a-phd-9e80f89ae04e).
(With the excellent subtitle: _Some Of Which I Probably Could Have Guessed And Most Of Which I Was Probably Told At Some Point, But Now Know For Sure._)

**Sarah** is much more organised with her post-it to-do list method 💖

**Christina** is working on a fascinating project thinking about the ethics of machine learning in children's social care.
Good luck with the tight deadline Christina!!

**Louise** shared a new colourmap from Google: [Turbo: An improved rainbow colormap for visualisation](https://ai.googleblog.com/2019/08/turbo-improved-rainbow-colormap-for.html).
The linked blog is great discussion of the pros and cons of rainbow colourmaps 🌈

**Yini** is "Learning Python the Hard Way" (via [the book](https://smile.amazon.co.uk/Learn-Python-Hard-Way-Introduction/dp/0321884914/ref=smi_www_rco2_go_smi_g8682124849?_encoding=UTF8&%2AVersion%2A=1&%2Aentries%2A=0&ie=UTF8) by Zed A Shaw recommended by Sarah and Georgia.
She found this video on youtube really helpful: [https://www.youtube.com/watch?v=9k8s8r5DXNU](https://www.youtube.com/watch?v=9k8s8r5DXNU).

Yini also recommended the "Tell me a story" point of view article by Joshua Sanes at eLife (doi: [10.7554/eLife.50527](https://doi.org/10.7554/eLife.50527)).
Sanes suggests starting with the introduction and results sections of a paper and leaving the figures to later.

(Side note: This is not Kirstie's style at all, she's super into figures to tell the story, but its worth reading and seeing what fits your workflow best!)

**Malvika** is enjoying getting to know [_The Turing Way_](https://github.com/alan-turing-institute/the-turing-way) better, and would love to hear about your contributions and ideas for the project.

**Ang** is really happy to get a revise and resubmit re-consideration by the editor for his first first author paper.
Fingers crossed 🤞 🤞

**Yo** is having tonnes of fun interviewing participants for her PhD research study.
About 10 hours so far, and at least as much more over the next few weeks.
She's feeling happy and excited that people are so ready and willing to help 💖
Good luck on all the transcriptions Yo!

Yo also shared [http://citeas.org](http://citeas.org) as a really useful page to know how to cite something (dois, urls and arXiv ids all included).

**Elizabeth** was sad to miss Fernando Perez's live stream at the American National Science Foundation last week, but recommends going through the 🌟 amazing 🌟 slides:
* [https://speakerdeck.com/fperez/open-source-academic-science-and-the-public-mission-of-research-reflections-from-the-field](https://speakerdeck.com/fperez/open-source-academic-science-and-the-public-mission-of-research-reflections-from-the-field)

**Georgia** is excited that we have some of our first contributions to the [citizen science project](https://speakerdeck.com/fperez/open-source-academic-science-and-the-public-mission-of-research-reflections-from-the-field) from our [survey](https://bit.ly/AutisticaTuringCitSciForm) and [mailing list](https://tinyletter.com/AutisticaTuringCitizenScience) ✨

## Questions we're thinking about

**Sarah** asked "What are the lab's tips for keeping your energy/interest going through a conference?"

We recommended taking breaks and feeling ok with skipping some sessions.
A tired researcher sitting at the back of a hot conference hall isn't learning anything, and if you're fresh then you're able to be present and focus on the talks.

**Patricia** asked for the group's recommendations on keeping desktops (in physical and virtual space) decluttered?
How do you make time for that in your calendar?
Every 6 months?

Yini pointed out that it helps that the Turing only has hot desks so you _have_ to tidy up every evening 😕

**Christina** is learning about different types of machine learning - supervised, unsupervised, semi-supervised or reinforcement - and the different ways they can be applied.
Specifically she's interested in thinking about the ethical considerations that differ across the different types of analyses.
She's had lots of useful conversations at the Turing, and we had some great discussion at the end of lab meeting.
This is going to be an awesome paper that she's currently writing!

**Georgia** is working out comms strategies for the [citizen science project](https://github.com/alan-turing-institute/AutisticaCitizenScience/).
She'd love suggestions how to engage and involve people?

**Elizabeth** is brainstorming what an ideal Jupyter "authoring experience" could look like.
She'd love comments on [this initial sketch of a workflow](https://github.com/jupyter/jupyter-book/issues/236)!

**Ang** wonders if there's a better way to test the heterogeneity of one-dimensional continuous data across two groups?
The goal is to test whether one measurement is more heterogeneous than another (instead of, for example, performing an F-test, which comparing the variance of two distributions).

**Yo** is wondering about tips for applying for research fellowships?

## Anything else

We didn't answer many of our own questions, because Google Summer of Code student Ruslan Yermakov joined us to present his work on [`scona`🍪](https://github.com/WhitakerLab/scona).

You can read [his final report](/blog/Ruslan-Final-Report-GSoC19) and check out the fantastic tutorials he made in Binder:

* [Global measures visualisation](https://mybinder.org/v2/gh/WhitakerLab/scona/master?filepath=tutorials%2Fglobal_measures_viz.ipynb)
* [Interactive 3D visualisations](https://mybinder.org/v2/gh/WhitakerLab/scona/master?filepath=tutorials%2Finteractive_viz_tutorial.ipynb)

Here are a few lovely images to close out the blog.

<figure class="half">
  <img src="/images/lab-meeting/2019-08-22/modules.png" alt="Network nodes coloured by module">
  <img src="/images/lab-meeting/2019-08-22/left-brain-right-brain.png" alt="Network nodes coloured by hemisphere">
</figure>
<figure class="half">
  <img src="/images/lab-meeting/2019-08-22/network-edges.png" alt="Top 5% of network connections">
  <img src="/images/lab-meeting/2019-08-22/neon-connections.png" alt="A slightly ridiculous plot of too-large nodes with neon green edges">
  <figcaption>Top left: Network nodes coloured by module.
              Top right: Network nodes coloured by hemisphere. (Go bears!)
              Bottom left: Top 5% of network connections.
              Bottom right: A slightly ridiculous plot of too-large nodes with neon green edges.
  </figcaption>
</figure>
