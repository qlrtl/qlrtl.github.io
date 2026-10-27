# Vixy Rivera, academic site

Personal academic website, served by GitHub Pages at https://qlrtl.github.io

All files sit at the top level of the repository; keep them there.

- `index.html`: the whole page (content, styling, and the interactive indexical-field figure)
- `cv.pdf`: the CV linked from the page; upload a newer file with the same name to replace it
- `portrait.jpg`: profile photo
- `favicon.svg`: browser-tab icon

To edit text, open `index.html` on GitHub, click the pencil icon, make the change, and commit. The live site updates within a minute or two. Lines marked `EDIT:` are spots meant to be filled in.

## The indexical-field figure

The wordings, clashing pairs and open questions all live in the `<script>` near the bottom of `index.html`:

- `single`: the wording for each quality on its own
- `pairs`: the wording for each pair; `null` marks an open question that visitors can answer
- `incompatible`: pairs that gray each other out
- `compose()` and `FRAMES`: the rules that build wordings for three or four qualities. The sentence's mood is fixed first (bare noun, imperative or question), then the strongest question frame, then one typical device per remaining quality. A combination becomes an open question if it contains an open pair, leaves a selected quality unexpressed, or stacks more than three devices. Composed wordings are marked ? (three qualities) or ?? (four).

Visitor suggestions for open questions arrive by email: the "Suggest a wording" link opens the visitor's mail app with the pair already filled in. To change the address, edit `SUGGEST_TO` at the top of the script. To collect suggestions in a form instead, point that link at a form service's URL.
