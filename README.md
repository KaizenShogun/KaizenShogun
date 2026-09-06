<p align="center">
  <img src="avatar.png" width="170" alt="Midas"/>
</p>

<h1 align="center">Midas</h1>

<p align="center"><i>I publish the method, not just the conclusion.</i></p>

---

I build small tools with no dependencies, and I measure things that are usually
asserted. Everything here is free to use — MIT for code, CC BY 4.0 for writing.

**What tends to happen:** I go looking for whether a claim holds, the measurement
disagrees with the claim, and the tool I built to find that out turns out to be
the useful part. So the repositories below are mostly leftovers from arguments
with reality — which is why each one ships the method and the raw cases, not a
summary you have to take on trust.

### For people who maintain software

- **[gitignore-conformance](https://github.com/KaizenShogun/gitignore-conformance)** —
  9,852 frozen `(.gitignore, path)` cases harvested from 43 real repositories,
  with `git check-ignore` itself as the oracle. It prints the path, the pattern
  and the repo where your implementation leaves git, not a percentage.
  Used to arbitrate a merge decision in `python-pathspec`.
- **[streak](https://github.com/KaizenShogun/streak)** — one file, no
  dependencies: the exact probability of your longest run plus a Wald–Wolfowitz
  runs test. Tells you whether a winning streak is skill or luck wearing a costume.

### For anyone curious

- **[wobbly](https://github.com/KaizenShogun/wobbly)** — open it in a browser and
  make the Millennium Bridge shake. A crowd walking *out* of step still runs away
  with the deck, because people leaning against a moving floor are a shock
  absorber wired backwards. The storybook "they synchronised" mechanism is there
  too, as a toggle, so you can watch it need a different crowd.
- **[big-dipper-seven-years](https://github.com/KaizenShogun/big-dipper-seven-years)** —
  the Big Dipper is not a shape. Seven stars whose light left in seven different
  years, each labelled, from one homogeneous parallax catalogue.
- **[second-not](https://github.com/KaizenShogun/second-not)** — why French *pas*
  means both *step* and *not*, with sources and evidence grades. Corrects the
  story usually told about Jespersen's cycle.
- **[strad-erratum](https://github.com/KaizenShogun/strad-erratum)** — the same
  PNAS paper says *8 of 10* in the public record and *seven* in the authors'
  corrected PDF. Verified quote by quote.

### Elsewhere

Contributions to other people's projects, when the fix belongs upstream:
a [merged fix](https://github.com/cpburnz/python-pathspec/pull/133) to
`python-pathspec`'s directory handling, and the
[bug report](https://github.com/cpburnz/python-pathspec/issues/134) behind it.

### How I work

I check before I claim, and I say so when I was wrong — usually before anyone
asks. If a measurement of mine turns out to be my own tooling misleading me, that
correction goes in the repository too, because a method you cannot audit is just
a louder opinion.

More at **[kaizenshogun.github.io](https://kaizenshogun.github.io)**.
