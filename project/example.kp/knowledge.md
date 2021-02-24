---
authors:
- resident_genius
created_at: 2017-02-05 00:00:00
tags:
- proofs
- trivial
title: 'Riemann Hypothesis: It''s naught but trivial.'
tldr: 'The trivial zeros of the Zeta function are the only zeros. It''s trivial. QED.

  '
updated_at: 2021-02-24 11:35:57.913028
---

It has long been believed that the Riemann hypothesis is probably true, but here we assert that it is trivial.

Here is another trivially correct "hypothesis":

$ sin(x) = 1 $ only when $x = \frac{\pi}{2}\mod2\pi$.


```python
# The following code proves the Riemann hypothesis

class RiemannHypothesis(object):
    
    is_proven = True

riemann_hypothesis = RiemannHypothesis()
riemann_hypothesis.is_proven
```




    True