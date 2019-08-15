---
layout: post
title: Google Summer of Code - Monica's Final Report
categories: blog
excerpt: As summer comes to an end, so does GSoC. Monica reflects about her time here.
image:
  feature:
link:
date: 2019-08-14
modified:
share: true
author: monicayao
---

## Questions and Answers about this Summer

First, let me bring back an excerpt from my introduction:

> From this summer, I wish to achieve a couple of things: 
> 1. Learn about the awesome and neat science behind multi-echo fMRI
> 2. How this library could be advanced in the future, should there be a new publication about denoising ME fMRI data
> 3. Adding lots and lots of tests to the library so that contributors in the future could extend the library without worries
> 4. Familiarizing myself with open source, and continue adding onto libraries as a regular contributor!

This is what I wanted to do this summer! It's time to reflect.

### What I wanted to do

I wanted to add a unit test to all the different functions in the tedana library, making it future proof for those who contribute to it in the future. 

My project with `tedana` was to make the testing deck more robust. The project was trying to make contributing more friendly for everyone!
One big reason being that many who utilize `tedana` in publications are neuroscientists who do not regularly code, but the `tedana` community members want to welcome them to!

This project acheives that goal because it would be a lot more welcoming to have simple unit test functions that not only show them what the functions are doing, but also catch any potential bugs or silly mistakes they could make.

### What I did 

In the end, I added a "smoke test" to all the functions. Smoke tests simply test the different I've recently started on adding a unit test for all the functions.

Links of some of the pull requests and issues! 
https://github.com/ME-ICA/tedana/pull/313
https://github.com/ME-ICA/tedana/pull/314
https://github.com/ME-ICA/tedana/pull/366
https://github.com/ME-ICA/tedana/pull/367
https://github.com/ME-ICA/tedana/issues/290
https://github.com/ME-ICA/tedana/issues/335
https://github.com/ME-ICA/tedana/issues/376

I don't have a comparison of the before/after of test coverage but a recent screenshot from a recent code coverage graph!
<figure>
  <img src="/images/codecoverage.jpg"
       alt="hometown">
  <figcaption> Screenshot of code coverage! </figcaption>
</figure>

### What I didn't do 

Did not acheive all my hope and dreams - adding a unit test to every single function.

The reason was simple, lots in my life happened this summer. Many different times, I wanted to flat out quit GSoC and focus on managing the stress that came from life's challenges. 
Nonetheless, I'm extremely grateful to Kirstie and the `tedana` members for allowing me to stay onboard for the project, and guiding me along the way!


### What was hard

Getting used to the workflow. Open source is extremely independent but also extremely dependent on the members of the community. A big problem I had was wanting to work by myself to understand the library and overcome the different roadblocks I encountered. Many of those would have been solved by the members, yet I was stubborn. 

### What I learned

Testing!!! There are so many different ways to test functions. Just in the tedana library, there are break tests, smoke tests, unit tests, integration tests. Quality assurance isn't as easy as it seems. 
In addition, I learned that the use of github isn't just version control, it is for you to make a pull request from your code, so others can review it. So what if it is rejected?!

### What I’m going to do next (not related to the project!)
As cheesy as it sounds, this summer made me realize that a lot of what you plan do not come to actualization. So many different circumstances appeared, and I have learned to deal with some stressful real-life experiences. The next step for me is to focus on myself. I don’t think I’m at a good stage for more work, and I want to take a break from school (for a semester or a year). It may be too late for the fall semester, but I think that I will take the spring off to go back to China and spend a lot more time with family and getting to know my culture! 

