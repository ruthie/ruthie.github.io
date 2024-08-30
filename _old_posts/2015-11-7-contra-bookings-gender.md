---
layout: post
title: Contra Dance Bookings and Gender
excerpt_separator: <!--more-->
---

I [promised a while ago]() I would write a post analyzing gender in the context of contra dance bookings.  This post keeps that promise.  I was hoping to be able to draw more interesting conclusions, but alas, my dataset was too small to do so with any confidence.

<!--more-->

## tl;dr

Women called 47% of dances in my sample, and were about a third of musicians (weighted by gigs).  This is compared to a baseline of about 54% women in the Bay Area contra dance community.

There are a few trends you can find if you break this up into subgroups, but they seem to be mostly driven by a few outliers, so I won't point them out.  Overall, the sample size is small and dominated by a relatively small number of very active people, so it's hard to draw conclusions from the sort of small-percentage-point differences between subgroups that I was able to find.

## Implementation Notes

I obviously don't know the genders of every person in my dataset.  My dataset contains people I've never met with non-gender-signalling names, people who I know or suspect have identities different from what one would guess based on their names, and many many people who I only know from seeing perform.  Most of the gendering was done using a [name-to-likely-gender mapper I found on the internet](https://pypi.python.org/pypi/SexMachine/).  I special-cased several people who (a) had ambiguous names and unambiguous presentations or (b) had unambiguous names but I have reason to believe that the lack of ambiguity is misleading.

People who I believe to be neither men nor women were counted as half a man and half a women.  I realize this may not accurately represent the genders of those people, and I'm sorry they're misrepresented in this statistic.

## Baseline

I have access to exactly one statistic on the gender ratio in the Bay Area contra dance community in general, which is that 42% of attendees at this year's non-gender-balanced Balance The Bay were men and 54% were women (the rest declined to state).  This matches my anecdotal impression that there are slightly more women than men in the community.

## Discussion

It's clear that men both call and play a disproportionate number of dances, but it's hard to tell what to make of these statistics without a lot more context.  The gender disparity could reflect a difference interest, or skill, or confidence, or perceived skill, or availability, or any number of other things.

One interesting note is that these statistics only reflect the people who had enough of all of those things to play at least one dance over two years, which cuts out the vast majority of potential contra dance musicians and callers.  I was playing folk music for more than 10 years before I first played for a contra dance; some of that time I was playing other styles, some of it I was too busy, and most of it I didn't have the skill yet.  To better understand why we see big gender disparities, I'd have to compare the number of people playing or calling gigs to the people who request to be booked, or the number of people at slow jams or callers workshops, or compare those actively playing dances to those who have played at least once.
