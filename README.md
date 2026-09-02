# didacll.github.io

Root GitHub Pages deployment adapter for `https://didacll.github.io/`.

This repository does **not** contain or duplicate the portfolio source. Its workflow checks out [`DidacLL/AgenticCareerBoost`](https://github.com/DidacLL/AgenticCareerBoost), compiles the public CV from its canonical LaTeX source, builds the Astro portfolio, and publishes `site/dist` as the root GitHub Pages artifact.

The root deployment is the indexable canonical site. The project-level Pages build in AgenticCareerBoost is a non-indexable mirror used for source-project publication and verification.

Source of truth: [`DidacLL/AgenticCareerBoost`](https://github.com/DidacLL/AgenticCareerBoost).
