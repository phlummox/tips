---
title: viewing Markdown files in GitHub repositories, with line numbers visible
---

appending `?plain=1` gives you an un-rendered view of the markdown file with
line numbers.

appending `?plain=1#L52` will do the same, and highlight line 52.

appending `?raw=1` will redirect you to the "raw" view of the file.

(source: <https://stackoverflow.com/a/68204783>)

NB: an initial google search will likely find you [this GitHub issue][issue-297],
but the link to the StackOverflow answer is buried fairly deep in there
and isn't obvious at first glance.

[issue-297]: https://github.com/isaacs/github/issues/297
