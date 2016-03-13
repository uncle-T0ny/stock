Configuration:
add extension to .hgrc
[extensions]
rebase =

//squash 2 commits
hg rebase --dest .~2 --base . --collapse
