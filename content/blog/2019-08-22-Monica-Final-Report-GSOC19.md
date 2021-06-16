---
title: "Monica's GSoC Final Report"
date: 2019-08-22T00:00:00+00:00
draft: false
authors: ["monicayao"]
categories: blog
tags: [gsoc, tedana]
---

## Questions and Answers about this Summer

First, let me bring back an excerpt from my introduction:

> From this summer, I wish to achieve a couple of things:
> 1. Learn about the awesome and neat science behind multi-echo fMRI
> 2. How this library could be advanced in the future, should there be a new publication about denoising ME fMRI data
> 3. Adding lots and lots of tests to the library so that contributors in the future could extend the library without worries
> 4. Familiarizing myself with open source, and continue adding onto libraries as a regular contributor!

This is what I wanted to do this summer!
It's time to reflect.

### What I wanted to do

I wanted to add a unit test to all the different functions in the `tedana` library, making it future proof for those who contribute to it in the future.

My project with `tedana` was to make the testing deck more robust.
The project was trying to make contributing more friendly for everyone!
One big reason being that many who utilize `tedana` in publications are neuroscientists who do not regularly code, but the `tedana` community members want to welcome them to!

This project acheives that goal because it would be a lot more welcoming to have simple unit test functions that not only show them what the functions are doing, but also catch any potential bugs or silly mistakes they could make.

### What I did

In the end, I added a "smoke test" to all the functions.
Smoke tests simply test that the functions generate an output that is not null when random inputs are passed in.
I've recently started on adding a unit test for all the functions.

Links of some of the pull requests and issues!
1. [Updates to the home page of documentation](https://github.com/ME-ICA/tedana/pull/313)
2. [Clarification for the ME-fMRI section in documentations](https://github.com/ME-ICA/tedana/pull/314)
3. [Loading in current year during runtime for copyrights](https://github.com/ME-ICA/tedana/pull/366)
4. [Smoke tests for files](https://github.com/ME-ICA/tedana/pull/367)
5. [Issue addressing documentation](https://github.com/ME-ICA/tedana/issues/290)
6. [Issue addressing smoke test for first steps of `tedana`](https://github.com/ME-ICA/tedana/issues/335)
7. [Issue addressing smoke test for helper files of `tedana`](https://github.com/ME-ICA/tedana/issues/376)

I don't have a comparison of the before/after of test coverage but a recent screenshot from a recent code coverage graph!
<figure>
  <img src="/images/codecoverage.jpg" alt="codecoverage"
      >
  <figcaption> Screenshot of code coverage! </figcaption>
</figure>

This is also a screenshot of the different tests passing!
<figure>
  <img src="/images/Pytests.jpg" alt="pytests"
      >
  <figcaption> Screenshot of all the tests passing!
  Note: Warnings are suppressed for a better picture. </figcaption>
</figure>


### What I didn't do

Did not acheive all my hope and dreams - adding a unit test to every single function.

The reason was simple, lots in my life happened this summer.
Many different times, I wanted to flat out quit GSoC and focus on managing the stress that came from life's challenges.
Nonetheless, I'm extremely grateful to Kirstie and the `tedana` members for allowing me to stay onboard for the project, and guiding me along the way!
Josh and Taylor were also extremely helpful and patient with me, answering the sudden bursts of questions I would get at once!


### What was hard

Getting used to the workflow and understanding the technology behind `tedana`.

Open source is extremely independent but also extremely dependent on the members of the community.
A big problem I had was wanting to work by myself to understand the technology as well as the library itself.
`tedana` is a difficult project to understand!
I've tried to read the papers by [Kundu](https://www.ncbi.nlm.nih.gov/pubmed/28363836) many times, and it is still hard to grasp.
I was intimidated by the different building blocks of the library, but I had focused too much on the medical side, and forgot that I was supposed to handle more of the technological sides!

Even when encountering different roadblocks like understanding the library, I wanted to overcome it myself.
Many of those would have been solved by the members, I could have asked them for explanations, yet I was stubborn.

If I were to do things differently I would:
1. Reach out to the members... early. The sooner the better.
2. Understand that you have a mentor for a reason, and it is okay to ask for help.
3. The community chats are terrifying at times (toooons of messages and none that you understand) so sending a private message to a community member and asking them a question is totally fine too!

To the future GSoC students - don't be scared like I was, and starting late is better than starting never!

### What I learned

Testing!!! There are so many different ways to test functions.
Just in the tedana library, there are break tests, smoke tests, unit tests, integration tests.
Quality assurance isn't as easy as it seems.

In addition, I learned that the use of Github isn't just version control, it is for you to make a pull request from your code, so others can review it.
One helpful thing I have recently come to understand is that pull requests are helpful because it uploads your code to a place where all community members can see. They can then help you debug it by running it on their local machines!

So what if the PR is rejected?!
You will have an improved version of the code from the community member's reviews. That means it's time to open a PR that can be merged!

### What I’m going to do next
As cheesy as it sounds, this summer made me realize that a lot of what you plan do not come to actualization.
So many different circumstances appeared, and I have learned to deal with some stressful real-life experiences.
The next step for me is to focus on myself.
I don’t think I’m at a good stage for more work, and I want to take a break from school (for a semester or a year).
It may be too late for the fall semester, but I think that I will take the spring off to go back to China and spend a lot more time with family and getting to know my culture!
