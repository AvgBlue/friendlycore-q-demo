# FriendlyCore q(c) Demo

A tiny interactive page for understanding the simplified FriendlyCore keep probability `q(c)`.

- `n` is the dataset size.
- `c` is the number of friends a selected point has.
- `q(c)` is the probability that the point is kept in the FriendlyCore.

The demo shows the simplified rule from the lecture:

```text
q(c) = 0, if c <= n/2
q(c) = 1, if c = n
q(c) rises smoothly between n/2 and n
```

Published with GitHub Pages.
