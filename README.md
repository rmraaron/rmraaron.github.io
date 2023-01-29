# rmraaron.github.io
BLOG


My Blog address: https://rmraaron.github.io


local dir: Projects/rmraaron.github.io

ruby -v 3.1.3p185 (2022-11-24 revision 1a6b16756e) [arm64-darwin21]

gem -v 3.3.26

jekyll -v 4.3.2



sudo bundler install

run in the local: bundler exec jekyll serve



deploy remotely: bin/deploy --user (
### source branch is projects not master - should be changed in deploy file)

gh-pages branch will be generated in remote server automatically and deployment in Actions will succeed (settings -> Pages -> Branchs(choosing gh-pages))
