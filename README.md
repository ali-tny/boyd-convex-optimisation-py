# boyd-convex-optimisation-py
This repo contains jupyter notebooks with solutions and commentary on the homework assignments for
the excellent [Stanford Convex Optimisation course taught by Stephen Boyd (via edX)][1].

The homework in the course is intended to be done via Matlab, but fortunately the main library used
(CVX) has [a python implementation that's almost identical][2].

Largely solutions will be the same in Matlab vs python, but the notebooks here contain the problem
ta translated into python ready-to-use, and a workaround in the final assignment where a feature of
the Matlab package isn't available in the python implementation.

The first couple of homeworks are just theory so don't have any practical work (I think... can't
quite remember) so are omitted here.

Notes:
- Often if the questions don't require computation they aren't included in the notebooks.
- I think for a couple of the assignments I skipped a question if I was busy - definitely in
  homework 8 I skipped one.
- If the input data uses the (seeded) Matlab random number generated, then I can't recreate it in
  python, so naturally the input is different in these notebooks. In those cases, the homework
  answers unfortunately won't align with the answers in the notebooks.

## Installation
Setting up this environment should be pretty simple (you just need cvxpy and jupyter, basically),
but you can just use [poetry][3] with the included requirements here. Just install poetry and
`poetry install`.


[1]: https://www.edx.org/course/convex-optimization
[2]: https://github.com/cvxgrp/cvxpy/
[3]: https://python-poetry.org/docs/#installation
