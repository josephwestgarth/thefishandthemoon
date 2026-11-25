# The Fish and the Moon

The website at https://thefishandthemoon.com. Plain HTML, no build step.

- `index.html`: the whole site (home, theory map, /theory-001 and the coming-soon pages).
- `_redirects`: sends every path to `index.html` so /theory-001 links work.
- Netlify deploys this repository (thefishandthemoon/thefishandthemoon) automatically on every push to `main`. Keep it public: the free Netlify plan blocks pushes from non-members on private repos.

The newsletter signup goes in the `#beehiiv-slot` div in `index.html`.
