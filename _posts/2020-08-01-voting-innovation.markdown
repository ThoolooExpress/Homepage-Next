---
layout: post
title:  "The Voting Booth is not the Place for Innovation"
date:   2020-08-01 12:00:00 -0400
categories: update
author: Richard Morrill
---

In a hotly contested election, accusations of fraud can be just as dangerous as
real fraud.  Observe the behavior of developing-world despots for long enough
and you will see, if you can't change the results of an election, the next best
thing is to convince everybody that they cannot trust its results.
<!--more-->It's all too easy to get hung up on whether or not a new form of
voting like vote-by-mail, or electronic voting machines is "safe," and overlook
the ways that a corrupt politician desperately clinging to power could convince
the public that their opponent committed election fraud.  In this post, I'm
going to briefly look at some of the issues with vote-by-mail, but my primary
focus is going to be on whether it _will be trusted_ not if it _can be trusted_.
Even if you and I do our research, and decide to entrust your vote to the postal
system, if enough of the rest of the country decides they cannot, it will be
child's play for Trump (or another politician down the line), to convince them
that their loss was fraudulent.

Vote-by-mail is simply not as easy to trust as a traditional in-person system.
In his [excellent argument against online
voting](https://www.youtube.com/watch?v=w3_0x6oaDmI), Tom Scott lays out the
primary goals of any voting system:

- Anonymity: Nobody can see how you voted, and once a ballot is cast, voters
  have no way to prove who they voted for.
- Trust: It must be extremely difficult to create fake votes or prevent
  legitimate votes from being counted, and everybody with a stake in the
  election must trust the system enough to believe its results.

A traditional paper ballot system accomplishes this by having every voter place
a ballot (which must not contain any individually identifiable marks) into a
tamper-evident ballot box, which is only opened for counting in the presence of
a member of every party involved in the election.  Although there are plenty of
attacks that can be made against this system, in Tom's words they, "do not scale
well," as almost every conceivable attack involves manipulating people, not
technology, and would need to be repeated for every opposition party
representative at every place that votes are counted.  Trust in the system is
achieved through an utter lack of trust in any individual.  At every stage, the
voter is the only person ever allowed to be alone with a ballot, and even then,
only inside the controlled environment of a voting booth.  Importantly, every
voter can readily understand why this form of security is effective.

When you cast a ballot by mail, however, numerous individuals, primarily in the
postal system, have time alone with your ballot to read, modify, or destroy it.
Although the final counting procedure ends up being fairly similar to in an
in-person election, how can you trust that your ballot actually made it into the
pile?  Also, what's to stop voters from showing their ballot to others before
sending it off, thus proving who their voted for, to potentially receive a
financial reward, or to avoid threatened violence?

I've only scratched the surface of holes that can be poked in vote-by-mail. Some
of these issues can be at least partially resolved with tamper-evident
envelopes, special anonymous confirmation codes, and other band-aid solutions.
However, the issue here is largely the same one that would arise if I were to
create, using my knowledge of cryptography, a "mathematically perfect"
public-key-based voting system.  I could trust it, anybody with a background in
mathematics or computer science could trust it, but could hundreds of millions
of technophobic and poorly-educated voters trust it?  Everybody understands that
it's hard to tamper with a box of ballots if you're being observed from every
angle by people who are unlikely to conspire together due to their opposing
political interests.  Every change you make to the existing system invites new
theories about how it can be defrauded.  Although most of the fears will be
unwarranted, if they can't be immediately dismissed, their long-term effect on
our democracy can be just as damaging as actual election fraud.

