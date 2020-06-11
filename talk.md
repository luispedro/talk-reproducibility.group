# Reproducible computational research reading group

- Anyone is welcome (semi-public)
- _Journal club rules_: if you attend, you need to volunteer
- Wednesdays at **noon UTC**.
- One presenter. Ideally, short sessions.

---

## Today's paper

> _Reproducible Research in Computational Harmonic Analysis_ by Donoho et al.,
> 2009

- An older paper
- Methods described are not up to date (Sourceforge as a new thing!)
- But conceptually/management still relevant

---

## Introduction (I)

> The traditional image of the scientist working in a laboratory with beakers
> and test tubes is long obsolete. The more accurate image—not yet well
> recognized—depicts a computer jockey working at all hours to launch
> experiments on computer servers
> [...]
> In fact, today's [2009] academic scientist likely has more in common with a
> large corporation’s information technology manager than with a philosophy or
> English professor at the same university."

- I think this is now recognized

---

## Introduction (II)

> Like deduction and empiricism, computation is also highly error-prone. From
> the newcomer’s struggle to make even the simplest computer program run to the
> seasoned professional’s frustration when a server crashes in the middle of a
> large job, all is struggle against error.

- In the meanwhile, we've had the "reproducibility crisis"

---

## Why do it? (I)

> Donoho didn’t trust himself to turn out good work unless his results were
> subject to the open criticism of others. He also learned from experience not
> to believe that graduate students were doing the work they believed they were
> doing unless he studied and ran the code himself
> [...]
> If everyone on a research team knows that everything they do is going to
> someday be published for reproducibility, they’ll behave differently from day
> one. Striving for reproducibility imposes a discipline that leads to better
> work.


- The general concept that reproduction is also about internal communication,
  though, I find it very important.

---

## Why do it? (II)

> For a senior researcher running a lab in which doctoral students come for a
> time and then leave, the only way to actually ensure the creation of valuable
> capital is to require students to work reproducibly.

---

## Why do it? (III)

> In pursuing full reproducibility, we  produce code for strangers to use.
> Although it might seem unnatural to help strangers our term stranger really
> means anyone who doesn’t possess our current short-term memory and
> experiences
> [...]
> It’s not uncommon for a researcher who doesn’t follow reproducibility as a
> personal discipline to forget how the software in some long-ago project was
> used, what its limitations were, or even how to generate an example of its
> application

- _Your worse collaborator is "you in six months": not only do you have no idea
  what was done, the original author doesn't even answer email._

---

## Why do it? (IV)

> A researcher who has worked reproducibly can actually go to the Internet,
> find his own long-ago work there, download it, and use it in the same way
> that anyone else could.
> [...]
> Tech support is both a burden and an opportunity. We often assign tech
> support tasks to graduate students who are just starting their doctoral
> research.

---

## When Did It not Work? (I)

> - **Postdocs**. By and large, postdocs are in a hurry to publish and would
>   prefer to work the way in which they’re accustomed rather than absorb some
>   new way of working—and who can blame them?

- This is less true today! Incentives have become better.
- Incentives are important, but, *we are the incentives*.

---

## When Did It not Work? (II)

> - Theorists. For the most part, a theory paper might have a few diagrams in
>   it and perhaps a numerical calculation, but the theory student probably
>   hates computing anyway and sees no need to develop more disciplined ways of
>   doing computational research.

- Probably true.

> - One-off projects. We did a few computational projects that might have
>   benefited from reproducibility, but were too small-scale to justify
>   building an entire toolbox that must then be maintained. Also, there was no
>   prospect of any of the authors continuing their research in the given
>   direction, so motivation for the required investment was very weak.

- "Extended methods vs. tools"

---

## Quick Answers to Knee-Jerk Objections

> _Reproducibility takes time and effort_. Response: Undeniably true. If our only
> goal were getting papers published, we would get them published sooner if we
> didn’t have to also worry about publishing correct and polished code.
> Actually, our goal is to educate future researchers; this takes time and
> requires effort.

- Agree

> _No one else does it, so I won’t get any credit for it._ Response: Partly
> true.

- Less and less true. And more and more, reviewers ask for it!

> _Strangers will use your code to compete with you._ Response: True.

- Still true 

---


## Sober Answers to Thoughtful Objections (I)

> _Reproducibility undermines the creation of intellectual capital._ Instead of
> building up a comprehensive set of tools in a lab over years, you give the
> tools away for free, before they ripen.

- Again, I think this misses the "extended methods" vs. "tools" distinction.
  Tools seem very much scoop-proof.

> _Reproducibility destroys time-honored motivations for collaboration._

- This is a Good Thing.

---

## Sober Answers to Thoughtful Objections (II)

> **Reproducibility floods journals with marginal science.** People will just
> download reproducible papers, make one tweak, and then modify the original
> paper in a few lines and resubmit a new paper.

- This already happens anyway. It happened a lot in fields with strong
  anti-reproduction norms too (image processing, back in the day).
- Actually, there is a big issue that _the right kind of incremental work_ is
  not so valued (merging upstream to widely-used tool, instead of using your
  own—that's how we ended up with 100s of unmaintained, barely-working,
  short-read aligners).

---

## Sober Answers to Thoughtful Objections (III)

> **True reproducibility means reproducibility from first principles. It proves
> nothing if I point and click and see the numbers I expect to see. It only
> proves something if I start from scratch and build my version of your system
> and get your results with my implementation.**


- This is a deeper discussion.
