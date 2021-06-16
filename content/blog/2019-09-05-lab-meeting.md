---
title: "Lab Meeting on 5 September 2019"
date: 2019-09-05T00:00:00+00:00
draft: false
authors: ["kirstiewhitaker"]
categories: blog
tags: [lab-meeting]
---

We were in a tiny meeting room at the Alan Turing Institute today because the Institute was hosting a [Data Study Group](https://www.turing.ac.uk/collaborate-turing/data-study-groups).
Many apologies to Konrad Adler-Wagstyl and Hannah Spitzer who had lots of questions from the many lab members who connected through Zoom rather than over fill the room with CO2!
Thank you so much for coming and presenting your work on the amazing [MELD](https://meldproject.github.io/) project ([see below](#konrad-and-hannah-presenting-on-the-meld-project) for more details.)

## Celebrations and cool things to share

This was **Maxine's** last meeting.
She's finished her [enrichment year](https://www.turing.ac.uk/work-turing/studentships/enrichment) at the Turing and is now writing up her thesis from her home in Oxford.
Thank you so much for being part of the group, Maxine!
We'll miss you 💖

**Kirstie** had some really fun conversations at the [INCF Assembly](https://www.neuroinformatics2019.org/) in Warsaw this week (including finding out that the team who collected the [Study Forrest](http://studyforrest.org/) dataset have never analysed it, and never intended to!).
She gave a talk on "Ten Simple Rules to Run an Open and Inclusive Project Online" (slides doi: [10.5281/zenodo.3383062](https://doi.org/10.5281/zenodo.3383062), [tweet thread](https://twitter.com/kirstie_j/status/1168138654650372097?s=20)) and made the picture below that she's particularly proud of 😂.
She was also really proud to be a member of the Turing Safe Haven project team who published their design paper on arXiv this week ([arxiv: 1908.08737](https://arxiv.org/abs/1908.08737)).
Kirstie ran the first _Turing Way_ [online Collaboration Cafe](https://github.com/alan-turing-institute/the-turing-way/blob/master/project_management/online-collaboration-cafe.md) this week and so appreciated Nadia, Jez and Malvika joining her to develop the _Turing Way_ project (video: [https://youtu.be/I0z7OEbBzes](https://www.youtube.com/watch?v=I0z7OEbBzes)).
Finally, she shared [this blog post](https://patricia.no/2018/09/06/survival_tips_for_women_in_tech.html) on survival skills for women (and other URMs in tech).
A depressing but very useful read.

<figure >
  <img src="/images/lab-meeting/2019-09-05/ten-simple-rules.png" alt="One icon to describe each of the ten simple rules in Kirstie's talk.">
  <figcaption>Icons for each of the 10 simple rules to run an open and inclusive project online (doi: <a href="https://doi.org/10.5281/zenodo.3383062">10.5281/zenodo.3383062</a>.
  </figcaption>
</figure>

**Sarah** and Kirstie [submitted a request](https://github.com/jupyterhub/mybinder.org-deploy/issues/1124) for a portion of the [Microsoft Azure credits donation](https://www.turing.ac.uk/news/alan-turing-institutes-data-science-research-be-boosted-5m-microsoft-cloud-computing-credits) to the Turing Institute to be used to build a BinderHub cluster at the Turing that will receive traffic from [mybinder.org](https://mybinder.org/) and be a part of the [Binder Federation](https://blog.jupyter.org/the-international-binder-federation-4f6235c1537e)! 🎉🎉🎉

She also shared a website (HT [Erik Sundell](https://github.com/consideRatio)) that shows the cleanliness of a country's energy generation and how the import/export of cleaner energy can effect the emission outputs of other countries that may use dirtier resources: [https://www.electricitymap.org](https://www.electricitymap.org/?page=map&solar=false&remote=true&wind=false) It's an excellent piece of scientific communication: the colour scheme is easily understood, and leads to great discussions about which countries you could pair up to reduce the international level of emissions.

**Elizabeth** shared [a very cool tool](https://microsoft.github.io/gather/) to "Manage Messes in Computational Notebooks".

**Ang** promoted a [project](http://www.ia.cas.cn/qtgn/zpzs/201909/t20190903_5375263.html) run by his PhD research institution (Institute of Automation, Chinese Academy of Sciences) to hire some excellent early career researchers in AI.

**Patricia** is settling into her new job and is celebrating the office having separate [crisps package recycling](https://www.terracycle.com/en-GB/brigades/crisppacket) bin 😋

**Yini** shared a paper showing that Wednesday is a lucky day to submit your paper to a journal!! doi: [10.1016/j.physa.2016.10.078](https://doi.org/10.1016/j.physa.2016.10.078),  [author accepted version](http://cer.ihtm.bg.ac.rs/bitstream/handle/123456789/3012/14_0907_10.1016j.physa.2016.10.078.pdf;jsessionid=0D41C7DDA729E7DBB8986FC3FC6680B7?sequence=1).

**Malvika** celebrated being accepted to co-lead a [Mozilla Open Leadership program in 2020](https://medium.com/read-write-participate/meet-the-open-leaders-x-cohort-1dc230a4c56a) with **Yo** and Berenice Batut.
They will be receiving training in the next months.
She also shared some recent blog posts on community building:

* [5 tips to promote ‘water cooler effects’ at informal discussion sessions](https://www.open-bio.org/2019/08/27/tips-for-informal-discussions)
* [How to be a pessimistic organiser for successful events](https://software.ac.uk/blog/2019-09-02-how-be-pessimistic-organiser-successful-events)

## Questions we're thinking about

**Maxine** read this article asking ["Do You Want to Be Known For Your Writing, or For Your Swift Email Responses?"](https://catapult.co/stories/do-you-want-to-be-known-for-your-writing-or-for-your-swift-email-responses) and is wondering about the liberation of not having to aim for inbox zero all the time?
Or is that just rude to colleagues and collaborators?

**Patricia** is trying to start some really organised habits for her new job and is looking for tips for collecting her notes together regularly.

**Yini** has been thinking about the work of the of the Brain Imaging Data Structure (BIDS, [https://bids.neuroimaging.io](https://bids.neuroimaging.io)) community in trying to unify the format of MRI data.
Having data in one harmonised format makes it much easier to run analyses, but she's wondering about the effects of a prevalent analysis pipeline that may have different preprocessing choices than other research groups would implement.
These decisions will always influcent the results.
How can we make sure that certain research questions are not ignored because the tools do not exist to ask them?

**Ang** has noticed that in many regions the individual measures for cortical thickness produced by Freesurfer correlate with the group patterns, but that isn't always the case.
It is probably a spatial bias in the accuracy of the recon-all algorithm.
How can we (should we) detect subtle mis-alignments?

**Malvika** is still struggling to get some interviews transcribed.
Does anyone have any suggestions to do this on and off line?
(Some data can be used online, others can only be processed locally).
Any motivation tips?

## Konrad and Hannah presenting on the MELD project

We zoomed through all the updates above, and commented in our shared HackMD notepad before the meeting, because we wanted to have lots of time to learn more about the [Multi-centre Epilepsy Lesion Detection (MELD)](https://meldproject.github.io) project

The goal of the project is to use machine learning to identify structural abnomalities on MRI for people with treatment resistant epilepsy.
Sophie and Konrad analysed a smaller dataset a few years ago and managed to do very well on that cohort (doi: [10.1016/j.nicl.2016.12.030](https://doi.org/10.1016/j.nicl.2016.12.030)).

They now have 450 participants from [18 different research groups](https://meldproject.github.io//groups/) around the world.

<figure >
  <img src="/images/lab-meeting/2019-09-05/meld_groups_coloured.png" alt="World map with pins dropped at each of the data sharing locations.">
  <figcaption>The MELD project has collected brain imaging data from 450 participants thanks to their collaborators at 18 different research institutes around the world.
  See details of each of the teams at <a href="https://meldproject.github.io//groups/">https://meldproject.github.io/groups</a>.
  </figcaption>
</figure>

As data on patients with epilepsy is very sensitive - individual participants could be much more easily identified than people who do not have a neurological disorder - all the data processing happens locally at the sites where data was collected.
Only fully anonymised data is transferred to the MELD team.
Their collaborators around the world follow the detailed study protocols which are publicly available and licenced for re-used through [protocols.io](https://www.protocols.io): [https://www.protocols.io/researchers/meld-project/protocols](https://www.protocols.io/researchers/meld-project/protocols).

Cortical lesions are very small and it takes a traned expert to identify them.
These labels are shipped with the anonymised data.
You can see the location of the lesions across all members of the cohort in the picture below.

<figure >
  <img src="/images/lab-meeting/2019-09-05/lesionmap.png" alt="Two brain images with yellow regions in frontal and temporal cortex indicating high numbers of participants with cortical lesions in those regions, and blue regions elsewhere indicating fewer participatns with lesions in primary motor and sensory regions.">
  <figcaption>Location of cortical lesions in the MELD cohort on a symmetrical brain parcellation in standard space.
  </figcaption>
</figure>

The lab meeting was rather like a second PhD viva for Konrad, with questions on MRI processing, quality control, data transfer and security, patient consent in a future national health service with interoperable data access, deep learning with mesh convolutions, normative modelling to avoid hand labelling of the data, and the benefits of multi-modal data 🙀🙀🙀.

Thank you so much Konrad and Hannah for coming along and sharing your work with us.

**If you are interested in getting involved in this collaboration please do not hesitate to contact the MELD team at [MELD.study@gmail.com](mailto:MELD.study@gmail.com).**
They are always looking for interested epilepsy centres as well as research scientists, developers and database managers.
